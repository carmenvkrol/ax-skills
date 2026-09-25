---
name: ax-link-library
description: Look up, add or edit links in Carmen's Accessibility Link Library; use when the user asks about saved accessibility links or resources, or (for the library's owner) shares an accessibility link with a comment to save.
---

# Accessibility Link Library

Carmen keeps a curated library of web resources about digital accessibility (web and mobile, WCAG, assistive technology, law, AI, disability culture). Each link has her own comments plus an AI-written summary of the page. It lives in the shared database of this artifact:

- Library page: https://claude.ai/artifact/4TAhPF8ZT7MFNRETm52zQS
- Database collection: `links` (one document per link, doc id `l` + 3-digit zero-padded number, e.g. `l165`)

Read and write it with the `ArtifactData` tool (load it with ToolSearch if deferred), always passing the URL above. The page updates live when a document changes, so never republish the page to add a link.

## Who can do what

- **Anyone Carmen has shared the page with** can look things up and ask questions.
- **Only Carmen** can add, edit or remove links. If a write is refused, tell the user the library is read-only for them. If they want their own editable library, point them to "Start your own library" in this plugin's README.
- If the page can't be read at all, the user probably doesn't have access yet. Tell them to ask Carmen to share it.

## Document fields

```
id            integer, next number after the current highest
section       "General accessibility links" (default) or "Mobile AX coursework links"
title         page title
url           the link (use the final URL if it redirects)
original_url  only if the saved link moved
my_comments   array of the owner's comments, VERBATIM - never reword, fix or summarize them
my_label      optional short label the owner gave instead of a comment
author        author and/or publisher, e.g. "Adrian Roselli" or "Ela Gorla (TetraLogical)"
date          publish date YYYY-MM-DD if known
type          article, guide, documentation, tool, video, news, report, standard, etc.
summary       2-3 factual sentences on what the page says
key_points    3-5 short strings
tags          1-4 from the fixed list below
page_status   ok | moved | blocked | unreadable
status_note   short reason when page_status isn't ok
related       optional {title,url,summary} for a second link inside the owner's comment
added         today's date YYYY-MM-DD
```

Omit fields that are empty.

## Tags (use only these)

AI; ARIA; Android; Cognitive, reading & mental health; Community & careers; Deaf & hard of hearing; Focus & keyboard; Forms; HTML & components; Images & alt text; Law & policy; Learning resources; Lived experience & culture; Mobile apps; Overlays; Programs & process; Screen readers & braille; Statistics; Testing & auditing; Visual design & color; Voice & switch control; WCAG & standards; iOS

If nothing fits, suggest a new tag rather than inventing one silently.

## Answering questions about the library

Query or list the `links` collection, then answer from it. Cite links as [title](url), and say which parts come from Carmen's comments and which from the page summary. If the library doesn't cover the question, say so rather than answering from general knowledge.

## Adding a link (owner only)

1. Take the URL and the comment exactly as written. If there's no comment, ask once whether they want to add one; save without it if not.
2. Check for a duplicate: `ArtifactData` `query` on `links` with `where: [["url","==",<url>]]`. If it exists, show the entry and ask whether to add the new comment to it (append to `my_comments`) instead.
3. Read the page with WebFetch and write the title, author, date, type, summary and key points from what the page actually says. Stay neutral on opinion pieces. If it redirects, follow it and store the final URL (old one in `original_url`). If it can't be read, save it anyway with `page_status` and `status_note`, no summary, and tell the user so they can ask for the summary later.
4. Find the next id: `query` `links` with `order_by: {field: "id", direction: "desc"}, limit: 1` and add 1.
5. Pick 1-4 tags.
6. Write it with `ArtifactData` `set` (collection `links`, doc id `l` + 3-digit id).
7. Confirm in one or two lines: the number, title and tags, and that it's on the library page. Don't paste the whole record.

Several links at once: do steps 2-5 for each, then write them in one `batch`.

## Editing or removing (owner only)

- To change a comment, tags or section: `get` the document, then `update` only those fields, passing `if_version`. Keep the owner's wording exactly as given.
- To fill in a missing summary: re-read the page, then `update` summary, key_points, title, date and set `page_status` to `ok` (remove `status_note`).
- To remove a link: confirm first, then `delete` it.

## Exporting for other AI tools

For a file to use in ChatGPT, Copilot, NotebookLM or similar, point the user to the page's "Download as Markdown" or "Copy as Markdown" buttons. Or list the collection and write a Markdown file with a short instructions header for the AI, then one section per link (URL, source, tags, comments, summary, key points, page status), and send it.
