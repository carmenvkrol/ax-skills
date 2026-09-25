# Accessibility Link Library skill

I collect articles, standards, tools and personal stories about digital accessibility, with my own comments on each one. This skill lets Claude search that collection and answer questions from it, citing the links.

The library itself is a page on claude.ai: [Accessibility Link Library](https://claude.ai/artifact/4TAhPF8ZT7MFNRETm52zQS). It has search, topic filters, an "Ask the library" box, and buttons to download everything as Markdown for other AI tools.

## Using it

1. **Ask me for access.** The page is shared by invitation, so the skill can only read it once I've shared it with your Claude account.
2. **Install the skill** (see the [main README](../../README.md)).
3. **Ask Claude**, for example:
   - "What's in the accessibility library about focus management in dialogs?"
   - "Which links did Carmen like on testing with AI?"
   - "Find resources on Dynamic Type for iOS."

You can read and search the library, but only I can add or change links. The skill will tell you if you try.

## Start your own library

If you'd like an editable library of your own:

1. **Publish your own page.** Give Claude the file [`templates/library-page.html`](templates/library-page.html) and ask it to publish the page as an artifact with these capabilities:
   `{"db": {"rules": [{"path": "", "read": "view", "write": "admin"}]}, "sample": {}, "downloads": true}`
2. **Optionally start from my links.** Download my library as Markdown from the page and ask Claude to load the entries into your page's `links` collection, keeping the same fields. Replace or clear my comments, since they'd otherwise appear as yours.
3. **Point the skill at your page.** In your copy of `skills/ax-link-library/SKILL.md`, replace my library URL with your page's URL, and replace my name with yours.

After that, paste a link and a comment into Claude and it will read the page, summarize it, tag it and add it to your library.

## What's in this folder

```
ax-link-library/
├── .claude-plugin/plugin.json      plugin details
├── skills/ax-link-library/SKILL.md the skill
└── templates/library-page.html     the library page, for starting your own
```
