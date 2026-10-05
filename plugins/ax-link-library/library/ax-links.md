# Carmen's Accessibility Link Library

*166 links · last updated 2026-10-05*

A curated collection of resources on digital accessibility: web and mobile apps, WCAG and other standards, assistive technology, testing, law, AI, and disability culture and lived experience. Each link has my own comments plus a short summary of the page.

## For AI assistants using this file

- **My comments** are Carmen's own notes on why she saved the link. Treat them as her opinions and give them priority when asked what she thought or recommended.
- **Summary** and **Key points** were written by AI from the page on or after the date it was added. Use them to answer what a resource says, but the linked page is the authority.
- **Page status** `ok` means the summary came from the page. `moved`, `blocked` or `unreadable` means there is no summary; rely on the title and comments.
- Cite links by title and URL, say whether an answer comes from Carmen's comments or the page summary, and say so when the library doesn't cover a question.

A machine-readable copy with the same content is in `ax-links.json` next to this file.

## Topics

AI (22), Android (11), ARIA (9), Cognitive, reading & mental health (7), Community & careers (7), Deaf & hard of hearing (2), Focus & keyboard (10), Forms (5), HTML & components (23), Images & alt text (6), iOS (18), Law & policy (8), Learning resources (23), Lived experience & culture (16), Mobile apps (27), Overlays (2), Programs & process (13), Screen readers & braille (24), Statistics (7), Testing & auditing (24), Visual design & color (17), Voice & switch control (10), WCAG & standards (25)

## General accessibility links

### 1. User 'wants' versus accessibility

- **URL:** https://www.tempertemper.net/blog/user-wants-versus-accessibility
- **Source:** Martin Underhill (tempertemper) · 2024-07-28 · article
- **Tags:** Programs & process, Lived experience & culture
- **My comments:** User ‘wants’ versus accessibility | Feedback from existing users likely to be negative because not including accessibility from the start
- **Summary:** Explores the tension between user feedback and accessibility improvements in organizations that historically lacked inclusive design. Explains why existing users often resist accessible changes and how a homogenous user base can mask the needs of disabled people who were previously excluded.
- **Key points:** Users naturally resist interface changes regardless of benefit; Existing user bases lack disabled people due to historical exclusion; Unanimous negative feedback doesn't mean the change is worse; Roll changes out incrementally to minimize disruption
- **Page status:** ok

### 2. What's the Difference Between HTML's Dialog Element and Popovers?

- **URL:** https://blog.master.dev/whats-the-difference-between-htmls-dialog-element-and-popovers/
- **Originally saved as:** https://frontendmasters.com/blog/whats-the-difference-between-htmls-dialog-element-and-popovers/
- **Source:** Chris Coyier (Frontend Masters) · 2024-09-30 · article
- **Tags:** HTML & components, Focus & keyboard
- **Summary:** Compares the HTML <dialog> element with the popover attribute. Both are hidden by default and render in the top layer, but they differ in focus management, how they're controlled and when to use them: dialogs suit modal interactions with focus trapping, popovers offer HTML-only controls and light dismiss.
- **Key points:** Modal dialogs trap focus and add a backdrop; Popovers can be controlled with HTML only (popovertarget); Both close with Esc; Dialogs move focus inside; popovers leave it on the trigger; Popovers light-dismiss on outside click unless manual
- **Page status:** ok

### 3. Basic Myths about Disability I Can't Believe We Still Have to Debunk

- **URL:** https://www.huffpost.com/entry/basic-myths-about-the-dis_b_9560556
- **Source:** HuffPost Contributor · 2016 · article
- **Tags:** Lived experience & culture
- **My comments:** Myths about disability
- **Summary:** Debunks common misconceptions about disabled people: wheelchair users may be able to walk, accessible parking placards cover non-visible conditions, identity-first language is valid, and disabled people want respect rather than 'inspiration porn'.
- **Key points:** Invisible disabilities can require wheelchair use without paralysis; Parking placards cover many conditions beyond mobility; Identity-first language is a legitimate preference; 'Inspiration porn' objectifies disabled people
- **Page status:** ok

### 4. The Accessibility Operations Guidebook is out

- **URL:** https://devonpersing.netlify.app/posts/taog-is-out/
- **Source:** Devon Persing · 2024-10-17 · book announcement
- **Tags:** Programs & process, Learning resources
- **My comments:** Accessibility Operations Guidebook
- **Summary:** Announces the Accessibility Operations Guidebook ebook, which addresses burnout in accessibility work with organizational-psychology theory and practical strategies for building sustainable, data-driven accessibility programs that center disabled people.
- **Key points:** Combines social-science foundations with actionable program strategy; Addresses systemic burnout among accessibility professionals; Intersectional, community-centered approach; DRM-free ebook; also available via libraries (OverDrive)
- **Page status:** ok

### 5. Designing for accessibility: enhancing math learning for the blind using the NVDA screen reader

- **URL:** https://medium.com/design-bootcamp/designing-for-accessibility-enhancing-math-learning-for-the-blind-using-the-nvda-screen-reader-bc2a43145c97
- **Originally saved as:** https://scribe.rip/design-bootcamp/designing-for-accessibility-enhancing-math-learning-for-the-blind-using-the-nvda-screen-reader-bc2a43145c97
- **Source:** Jo Chang (Bootcamp, Medium) · 2024-10-11 · article
- **Tags:** Screen readers & braille, Lived experience & culture
- **My comments:** Math on NVDA
- **Summary:** Looks at Access8Math, a free NVDA add-on from the Taiwanese nonprofit Coseeing, which addresses barriers blind students face learning math digitally. Covers NVDA's weak MathML support, Access8Math's reading/interaction modes, and a web editor that lets teachers create accessible math without knowing Nemeth Braille.
- **Key points:** NVDA has limited MathML support; Access8Math adds math reading and navigation modes; Web editor for teachers, no Nemeth expertise needed; Free, volunteer-built add-on
- **Page status:** ok (Original scribe.rip mirror link is broken; use the Medium URL)

### 6. The Small Business Accessibility Playbook for WordPress

- **URL:** https://equalizedigital.com/the-small-business-accessibility-playbook-for-wordpress/?utm_source=a11yweekly&utm_medium=sponsored
- **Source:** Equalize Digital and WP Buffs · 2024-06-06 · guide / ebook
- **Tags:** Learning resources, Law & policy, Testing & auditing
- **My comments:** Small business playbook
- **Summary:** Free 44-page ebook helping small businesses understand and implement website accessibility on WordPress: laws and compliance, testing tools and methods, remediation, and recommended accessible themes and plugins.
- **Key points:** Written for non-developers; Covers accessibility laws and legal risk; Step-by-step WordPress testing instructions; When to fix in-house vs. hire help
- **Page status:** ok

### 7. Why GOV.UK's Exit this Page component doesn't use the Escape key

- **URL:** https://beeps.website/blog/2024-10-09-why-govuk-exit-this-page-doesnt-use-escape/
- **Source:** beeps (GOV.UK Design System team) · 2024-10-09 · article
- **Tags:** Focus & keyboard, HTML & components
- **My comments:** Use of escape key
- **Summary:** Explains why GOV.UK's Exit this Page safety component (for people at risk of domestic abuse) uses repeated Shift presses instead of Escape, covering browser behavior, transient-activation rules and assistive technology conflicts.
- **Key points:** Escape cancels page loading in browsers; Escape doesn't count as user activation, so it can't trigger the redirect; Escape is heavily used by OSes and assistive tech; Shift chosen as least problematic alternative
- **Page status:** ok

### 8. Old alt text advice

- **URL:** https://html5accessibility.com/stuff/2024/11/23/old-alt-text-advice/
- **Source:** Steve Faulkner · 2024-11-23 · guide
- **Tags:** Images & alt text, HTML & components
- **My comments:** Thorough alt text advice
- **Summary:** Comprehensive alt text guidance originally written for the HTML5 spec (2010-2014), covering about 19 image scenarios with examples and code: decorative images, icon buttons, charts, images of text, and long descriptions.
- **Key points:** Alt text depends on the image's purpose and context; Decorative images get empty alt; Icon buttons describe the function; Charts need data-based descriptions; use figure/figcaption or links for long ones
- **Page status:** ok

### 9. Patrick's European vacation: traveling internationally as a person with a disability (Part Three)

- **URL:** https://www.deque.com/blog/patricks-european-vacation-my-experience-traveling-internationally-as-a-person-with-a-disability-part-three-the-conclusion/
- **Source:** Patrick Sturdivant (Deque) · 2024-11-26 · article / personal story
- **Tags:** Lived experience & culture, Screen readers & braille
- **My comments:** Experience of blind person traveling (there’s also a part 1 and 2, which are also great)
- **Summary:** A blind traveler's account of his return flight from Germany to Texas, covering Frankfurt airport and business-class travel, and proposing improvements for airlines such as Braille cabin labeling, accessible in-flight entertainment and clearer seat-belt alerts.
- **Key points:** Seat controls lacked tactile indicators; EU rules may exempt aircraft entertainment systems; Braille labeling inconsistent across airlines; United Airlines leads on accessible IFE and Braille
- **Page status:** ok

### 10. Assume the Position: A Labeling Story

- **URL:** https://vispero.com/resources/assume-the-position-a-labelling-story/
- **Originally saved as:** https://www.tpgi.com/assume-the-position-a-labelling-story/
- **Source:** TPGi (now Vispero) · 2023-06 · article
- **Tags:** Forms, HTML & components
- **My comments:** In-depth article about label positioning with form control
- **Page status:** moved (TPGi blog moved to Vispero; the new page couldn't be read automatically)

### 11. The goal of accessibility isn't to find issues, it's to fix them

- **URL:** https://www.hassellinclusion.com/blog/accessibilitys-goal-is-to-fix-issues-not-just-find-them/
- **Source:** Jonathan Hassell (Hassell Inclusion) · 2021-02-10 · article
- **Tags:** Programs & process, Testing & auditing
- **My comments:** AIPM - matrix for determining who to prioritize AX fixes
- **Summary:** Argues accessibility testing is pointless without remediation, citing widespread failures after the UK 2020 public-sector accessibility deadline. Introduces the Accessibility Issue Prioritisation Matrix (AIPM) to prioritize fixes by audience affected, severity of impact and cost to fix.
- **Key points:** Testing finds problems; fixing needs organizational commitment; AIPM weighs affected audience, impact and cost; Enables realistic budgeting for fixes; Remediating organizations move toward prevention
- **Page status:** ok

### 12. What automated accessibility testing can and can't do

- **URL:** https://www.netz-barrierefrei.de/en/auto-testing.html?ref=accessible-mobile-apps-weekly.ghost.io
- **Source:** Domingos de Oliveira (netz-barrierefrei.de) · article
- **Tags:** Testing & auditing
- **My comments:** What AX testing can and can’t do
- **Page status:** unreadable (Site timed out when fetched)

### 13. What's new with TalkBack 15.0

- **URL:** https://support.google.com/accessibility/android/answer/14997212?hl=en
- **Source:** Google (Android Accessibility Help) · documentation
- **Tags:** Android, Screen readers & braille
- **My comments:** What’s new with Talkback
- **Summary:** Release notes for TalkBack 15.0, Android's screen reader: generative-AI image descriptions (server-side or on-device on Pixel 9), punctuation verbosity controls, 'Read from next' renamed 'Read from focused item', and new Braille selection gestures.
- **Key points:** Gen-AI image descriptions; Punctuation verbosity: Some / Most / All; 'Read from focused item' via triple-tap; New Braille text-selection gestures
- **Page status:** ok

### 14. Advent of iOS Accessibility

- **URL:** https://accessibilityupto11.com/post/2024-12-06-01/
- **Originally saved as:** https://dadederk.github.io/post/2024-12-06-01/
- **Source:** Dani Devesa Derksen-Staats (Accessibility up to 11) · 2024-12-06 · guide / series
- **Tags:** iOS, Learning resources
- **My comments:** A bunch of iOS AX tips with links to other resources
- **Summary:** A 24-day series on common iOS accessibility issues and fixes for UIKit and SwiftUI: unlabeled elements, header traits, images, buttons, grouping, toggles, modals, contrast, touch targets, Dynamic Type and Reduce Motion, with links to further resources.
- **Key points:** Unlabeled icon buttons are a frequent miss; Grouping elements cuts VoiceOver swipes; Custom components need explicit accessibility setup; Support the largest Dynamic Type sizes; Test manually with VoiceOver
- **Page status:** ok

### 15. Optimizing for VoiceOver and Voice Control

- **URL:** https://www.basbroek.nl/optimizing-assistive-technology
- **Source:** Bas Thomas (Bas Broek) · 2024-09-27 · article
- **Tags:** iOS, Screen readers & braille, Voice & switch control
- **My comments:** Bas’ Blog - a lot on iOS AX tips
- **Summary:** Documents building an iOS survey component and the conflicting requirements of VoiceOver and Voice Control: combining elements helps VoiceOver but can hide actions from Voice Control. Settles on a balanced compromise and calls for better Voice Control documentation.
- **Key points:** VoiceOver support is a foundation for Voice Control; Combining elements helps VoiceOver but can break Voice Control; Voice Control lacks affordances for secondary/'ghost' actions; Pragmatic compromise across assistive technologies
- **Page status:** ok

### 16. Putting AI to the (Accessibility) Test

- **URL:** https://vispero.com/resources/putting-ai-to-the-accessibility-test/
- **Originally saved as:** https://www.tpgi.com/putting-ai-to-the-accessibility-test/
- **Source:** Tj Squires (TPGi / Vispero) · 2024-12-19 · article
- **Tags:** AI, Testing & auditing, Screen readers & braille, Images & alt text
- **My comments:** How blind engineer is using AI to test accessibility of photos
- **Summary:** A blind accessibility engineer describes using generative AI (JAWS PictureSmart) in testing: analyzing screenshots, comparing visual vs. programmatic information, and checking alt text, while stressing client privacy and verifying AI output.
- **Key points:** Check client privacy before using AI; Less reliance on sighted colleagues; Compare AI descriptions with alt text; AI can hallucinate; can't judge contrast
- **Page status:** ok

### 17. The Complete Guide to ARIA Live Regions for Developers

- **URL:** https://www.a11y-collective.com/blog/aria-live/
- **Source:** Florian Schroiff (The A11Y Collective) · 2024-12-05 · guide
- **Tags:** ARIA, Screen readers & braille
- **My comments:** Aria-live
- **Summary:** Guide to using ARIA live regions to announce dynamic content to screen reader users: aria-live values off/polite/assertive, aria-atomic and aria-relevant, code examples, common mistakes and testing across screen readers.
- **Key points:** Live regions announce updates without moving focus; Choose polite vs assertive by urgency; aria-atomic and aria-relevant control scope; Test in NVDA, JAWS and VoiceOver
- **Page status:** ok

### 18. How to Dehumanize Accessibility with AI

- **URL:** https://ashleemboyer.com/blog/how-to-dehumanize-accessibility-with-ai
- **Source:** Ashlee M Boyer · 2024-12-14 · article / opinion
- **Tags:** AI, Testing & auditing, Lived experience & culture
- **My comments:** Mentions that testing at most can find 40% of issues
- **Summary:** Critiques an 'a11y-AI' tool that uses AI-generated disabled personas, arguing synthetic characters can't represent disabled people's experiences or replace human expertise, and that accessibility problems stem from ableism, not lack of awareness.
- **Key points:** AI personas can't authentically tell disabled people's stories; Root problem is systemic ableism; Automated tools catch only about 13-40% of issues; Hire disabled accessibility experts instead
- **Page status:** ok

### 19. Headaches with FCC Reporting on Captioning Problems Per CVAA

- **URL:** https://equalentry.com/captioning-problems-fcc-reporting/
- **Source:** Meryl Evans (Equal Entry) · 2024-12-05 · article
- **Tags:** Law & policy, Deaf & hard of hearing
- **My comments:** Equal Entry - I like their legal discussions in general
- **Summary:** Describes the burdensome FCC captioning complaint process under the CVAA, using the author's report about ION TV censoring profanity in captions but not audio. Argues the process demands too much from disabled consumers and lacks follow-up to confirm fixes.
- **Key points:** Captions sanitized while audio unchanged; FCC complaints require excessive detail; Little oversight of broadcaster fixes; Streaming platforms offer easier flagging
- **Page status:** ok

### 20. Why are we so rubbish at accessibility?

- **URL:** https://carmemias.com/why-are-we-so-rubbish-at-accessibility/
- **Source:** Carme Mias · 2024-12-23 · article
- **Tags:** Testing & auditing, Statistics
- **My comments:** Gives details about top AX issues
- **Summary:** Uses WebAIM Million data (95.9% of top homepages have detectable errors, about 56 per page) to argue that the most common failures (low contrast, missing alt text, unlabeled forms) are easy to fix, and that developers must take ownership.
- **Key points:** 95.9% of top 1M homepages have errors; Top failures: contrast, alt text, form labels, empty links/buttons; About 25% of the UK population reports a disability; Developers are the last link in the chain
- **Page status:** ok

### 21. Don't Hide Skip Links

- **URL:** https://ozewai.org/blog/technical-articles/dont-hide-skip-links/
- **Source:** Andrew Downie (OZeWAI) · 2024-12-22 · article
- **Tags:** Focus & keyboard, HTML & components
- **My comments:** In-depth discussion about skip links for keyboard-only users | Gets me thinking why regions aren’t expected to be focusable
- **Summary:** Argues skip links should be visible rather than hidden until focus, since keyboard-only users benefit most from them, while screen reader users have other navigation methods. Recommends multiple skip links on long pages.
- **Key points:** Skip links satisfy WCAG 2.4.1 Bypass Blocks; Keyboard-only users benefit most; Hidden skip links are a problem for sighted keyboard users; Consider several skip links on long pages
- **Page status:** ok

### 22. AI and Accessibility: Ethical Considerations and Solutions

- **URL:** https://www.a11y-collective.com/blog/artificial-intelligence-accessibility/
- **Source:** The A11Y Collective · 2024-12-09 · article
- **Tags:** AI
- **My comments:** Discusses considerations when using AI for accessibility
- **Summary:** Examines how AI can help accessibility (image description, speech recognition, adaptive interfaces) while addressing limitations: errors, accent and noise problems, automated 'fixes' that interfere with assistive tech, privacy and training-data bias. Stresses involving disabled people throughout development.
- **Key points:** Tools like Seeing AI and Lookout help but aren't infallible; Speech recognition struggles with accents and noise; Automated 'fixes' can break assistive tech; Training-data bias; Include disabled people throughout, not just at the end
- **Page status:** ok

### 23. FTC orders AI accessibility startup accessiBe to pay $1M for misleading advertising

- **URL:** https://techcrunch.com/2025/01/03/ftc-orders-ai-accessibility-startup-accessibe-to-pay-1m-for-misleading-advertising/
- **Source:** Kyle Wiggers (TechCrunch) · 2025-01-03 · news
- **Tags:** Overlays, Law & policy, AI
- **My comments:** Interesting that only 1 company was targeted
- **Summary:** The FTC fined overlay vendor accessiBe $1 million for falsely claiming its AI plug-in makes sites WCAG/ADA compliant and for presenting sponsored reviews as independent. The order bars overstating capabilities and requires endorsement disclosures.
- **Key points:** $1M penalty; Deceptive claims of compliance; Undisclosed paid reviews; NFB called its marketing disrespectful and misleading
- **Page status:** ok

### 24. super short note on links in iOS with VoiceOver

- **URL:** https://html5accessibility.com/stuff/2025/01/02/super-short-note-on-links-in-ios-with-voiceover/
- **Source:** Steve Faulkner · 2025-01-02 · article
- **Tags:** iOS, Screen readers & braille, HTML & components
- **My comments:** Issue with links on VO in iOS
- **Summary:** Documents an iOS VoiceOver/WebKit bug where links containing non-generic HTML elements are announced and counted as multiple links. Workaround: use generic elements (span) or role="none"; a WebKit bug was filed.
- **Key points:** Non-generic child elements fragment link announcements; Use span or role=none as a workaround; WebKit bug filed
- **Page status:** ok

### 25. Automated Accessibility Testing at Slack

- **URL:** https://slack.engineering/automated-accessibility-testing-at-slack/
- **Source:** Natalie Stormann (Slack Engineering) · 2025-01-07 · article / case study
- **Tags:** Testing & auditing
- **My comments:** Slack using AXE testing
- **Summary:** How Slack added Axe checks to its Playwright end-to-end tests to complement manual testing toward WCAG 2.1: why they moved off Jest/RTL, excluding known issues, filtering to critical violations, running checks after full render, and a Jira triage workflow.
- **Key points:** Axe + Playwright integration; Non-blocking suite with exclusion lists; Check only after full render to avoid false positives; Jira automation for triage; Automation doesn't replace human judgment
- **Page status:** ok

### 26. Automated and manual accessibility testing work best together

- **URL:** https://blog.pope.tech/2025/01/09/automated-and-manual-accessibility-testing-work-best-together/
- **Source:** Whitney Lewis (Pope Tech) · 2025-01-09 · article
- **Tags:** Testing & auditing
- **My comments:** Automated and manual testing working together
- **Summary:** Explains the strengths and limits of automated vs. manual accessibility testing and how combining them gives breadth and depth. Suggests a realistic strategy: monthly automated scans, annual manual testing of sample pages, and testing changes before release.
- **Key points:** Automated: fast, consistent, incomplete; Manual: slower but judges real impact and AT compatibility; Start with WAVE; Monthly scans + annual manual sample testing
- **Page status:** ok

### 27. How I learned to code with my voice

- **URL:** https://whitep4nth3r.com/blog/how-i-learned-to-code-with-my-voice/
- **Source:** Salma Alam-Naylor (whitep4nth3r) · 2025-02-04 · article / personal story
- **Tags:** Voice & switch control, Lived experience & culture
- **My comments:** Account of how a software engineer codes with voice
- **Summary:** A developer with severe hand pain describes learning to code by voice with Talon and Cursorless, what didn't work, and practical advice for others.
- **Key points:** Learn Talon's alphabet with deliberate practice; Rango for browser navigation; Start with small tasks; Expect a learning curve; combine tools
- **Page status:** ok

### 28. Overlay Fact Sheet

- **URL:** https://overlayfactsheet.com/en/
- **Source:** Karl Groves and 1,000+ signatories · resource / open letter
- **Tags:** Overlays, Law & policy
- **My comments:** Issues with overlays | Article describing lawsuits with overlays: https://www.lflegal.com/2025/02/userway-overlay-lawsuit/
- **Summary:** Open letter signed by 1,000+ accessibility professionals explaining why accessibility overlays can't make sites compliant, can worsen the experience for disabled users, raise privacy concerns and use deceptive marketing. Includes testimony from disabled users.
- **Key points:** Overlays can't deliver WCAG compliance; Automated repairs fail for images, forms, keyboard, dynamic content; Toolbars duplicate existing assistive tech; Privacy concerns from disability detection/tracking
- **Related link:** [Another Web Access Overlay Company Sued by a Small Business](https://www.lflegal.com/2025/02/userway-overlay-lawsuit/): A small online florist (BloomsyBox) filed a class action against overlay vendor UserWay after being sued by a blind user despite paying for the overlay; alleges false claims of lawsuit protection. Notes over 1,000 2024 ADA suits against sites using overlays.
- **Page status:** ok

### 29. Rethinking Find-in-Page Accessibility: Making Hidden Text Work for Everyone

- **URL:** https://schepp.dev/posts/rethinking-find-in-page-accessibility-making-hidden-text-work-for-everyone/
- **Source:** Christian 'Schepp' Schaefer · 2025-02-17 · article
- **Tags:** HTML & components, Screen readers & braille
- **My comments:** Find-in-page accessibility | Hidden=”until-found”
- **Summary:** Notes that some blind users navigate primarily with the browser's find-in-page, and proposes hidden="until-found" so visually hidden labels (e.g., on icon-only buttons) can still be found by search.
- **Key points:** Find-in-page is a real navigation strategy; hidden=until-found makes hidden text searchable; Chromium-only support at time of writing; aria-label as interim fallback
- **Page status:** ok

### 30. There's no such thing as 'menubar navigation'

- **URL:** https://www.tempertemper.net/blog/theres-no-such-thing-as-menubar-navigation
- **Source:** Martin Underhill (tempertemper) · 2025-02-28 · article
- **Tags:** ARIA, HTML & components, Focus & keyboard
- **My comments:** Questioning menubar W3C example
- **Summary:** Argues against using the ARIA menubar pattern for website navigation: menubars are for application actions, while site navigation should be simple lists of links. The menubar's arrow-key model confuses keyboard and screen reader users.
- **Key points:** Menubars = actions; navigation = links; W3C example needs 70+ lines of JS; Arrow-key behavior conflicts with Tab expectations; Most sites never need a menubar
- **Page status:** ok

### 31. A11y 101: 1.3.5 Identify Input Purpose

- **URL:** https://tarnoff.info/2025/03/03/a11y-101-1-3-5-identify-input-purpose/
- **Source:** Nat Tarnoff · 2025-03-03 · guide
- **Tags:** Forms, WCAG & standards
- **My comments:** Nice article about input
- **Summary:** Explains WCAG 1.3.5 Identify Input Purpose: native labels, correct input types and autocomplete attributes, and how autocomplete supports independence, password managers and security.
- **Key points:** Native label with for/id; Use specific input types; Use autocomplete tokens; Accessibility overlaps with security
- **Page status:** ok

### 32. Best Practices for Cognitive Accessibility in Web Design

- **URL:** https://www.a11y-collective.com/blog/cognitive-accessibility/
- **Source:** Caitlin de Rooij (The A11Y Collective) · 2025-02-24 · guide
- **Tags:** Cognitive, reading & mental health, Visual design & color
- **My comments:** Nice overview of how to make web/mobile products accessible for people with cognitive disabilities
- **Summary:** Guide to cognitive accessibility: how cognitive disabilities affect web use, relevant WCAG 2.2 criteria, design patterns (plain language, consistent navigation, forgiving forms, memory aids) and testing with real users.
- **Key points:** Many more people than the ~13% with cognitive disabilities benefit; Reduce overload, manage focus, allow time; Plain language, consistent navigation, clear errors; Test with people who have cognitive disabilities
- **Page status:** ok

### 33. WCAG Colour Contrast: What does the 4.5:1 ratio actually mean?

- **URL:** https://davedavies.dev/posts/wcag-colour-contrast-explained/
- **Source:** Dave Davies · 2025-01-31 · article
- **Tags:** Visual design & color, WCAG & standards
- **My comments:** Nice in-depth discussion in text color-contrast, esp motivation behind 4.5:1 rule
- **Summary:** Explains the science behind WCAG's 4.5:1 contrast ratio: relative luminance (brightness, not hue), how red/green/blue are weighted, colour vision deficiency, and how the standard evolved from a 3:1 baseline adjusted for reduced vision. Includes practical tools.
- **Key points:** Ratio measures luminance difference, not hue; Green ~72%, red ~21%, blue ~7% of luminance; ~1 in 12 men have colour vision deficiency; 4.5:1 = 3:1 baseline adjusted for vision loss
- **Page status:** ok

### 34. Android 16's Transition to Adaptive Apps: A Major Victory for Accessibility

- **URL:** https://www.accesstime.co/blog/android-16-upgrade
- **Source:** Michelle Neysa (AccessTime) · 2025-02-17 · article
- **Tags:** Android, Mobile apps
- **My comments:** Android 16 won’t allow locking in portrait and landscape mode
- **Summary:** Android 16 removes apps' ability to lock orientation and resizability on large screens, forcing adaptive layouts. That helps foldables and people who depend on landscape mode (e.g., mounted devices, motor or vision needs), aligning with WCAG 1.3.4 Orientation.
- **Key points:** No more portrait-only lockouts; Aligns with WCAG 2.1 Orientation; Test across orientations; use adaptive layouts; Benefits users with mounted devices and motor/visual needs
- **Page status:** ok

### 35. Implementing aria-describedby for Web Accessibility

- **URL:** https://www.a11y-collective.com/blog/aria-describedby/
- **Source:** The A11Y Collective · 2025-03-07 · guide
- **Tags:** ARIA
- **My comments:** Aria-describedby
- **Summary:** How to use aria-describedby to link elements to supplementary descriptive text for screen reader users, with examples for forms, buttons and dialogs, common mistakes, and testing advice.
- **Key points:** Links an element to descriptive text by ID; Pitfalls: overuse, broken IDs, repeating the label; Keep descriptions concise; Prefer native HTML; visible descriptions help everyone
- **Page status:** ok

### 36. Because we're not alone (reflections on CSUN)

- **URL:** https://www.joedolson.com/2025/03/because-were-not-alone/
- **Source:** Joe Dolson · 2025-03 · article / reflection
- **Tags:** Programs & process, Community & careers
- **My comments:** Like his statement that accessibility has to be done with intention
- **Summary:** Reflections after the CSUN Assistive Technology Conference on how shared struggles build community, WordPress 6.8's ~95 accessibility improvements, and why publicly critiquing site accessibility (on The Accessibility Show) is about showing the intentional work required.
- **Key points:** Every organization struggles with accessibility; WordPress 6.8 ships ~95 accessibility fixes; Critique exposes needed effort, not blame; Even accessibility-focused orgs face constraints
- **Page status:** ok

### 37. Abra Academy: learn how to make your apps accessible

- **URL:** https://academy.abra.ai/
- **Source:** Abra · course / e-learning
- **Tags:** Mobile apps, Learning resources
- **My comments:** Mobile ax courses
- **Summary:** E-learning platform for mobile app accessibility with a free 45-minute kickoff course and paid courses on testing, common issues and platform-specific iOS/Android training, with certificates. Instructors are involved in the W3C Mobile Accessibility Task Force.
- **Key points:** Free intro course; Paid courses ~€60-150; bundle ~€180; iOS and Android specific training; From the team behind Appt
- **Page status:** ok

### 38. Is React Accessible? That's the Wrong Question

- **URL:** https://www.accessarmada.com/blog/is-react-accessible-thats-the-wrong-question/
- **Source:** Access Armada · 2025-03-17 · article
- **Tags:** HTML & components
- **My comments:** Common ax issues when using React
- **Summary:** Argues the real question is whether React makes accessible apps easier or harder. Common React problems: div soup, weak semantics, ARIA misuse, SPA route-change focus management and client-side rendering performance.
- **Key points:** Use semantic HTML, not div soup; Use Fragments to avoid excess nesting; ARIA misuse harms users; Manage focus on route changes
- **Page status:** ok

### 39. Designers, your excuse is gone. Stunning, animated and accessible. Yes, you can!

- **URL:** https://annebovelett.eu/designers-your-excuse-is-gone-stunning-animated-and-accessible-yes-you-can/
- **Source:** Anne-Mieke Bovelett · 2025-03-14 · article
- **Tags:** Visual design & color
- **My comments:** Github experience
- **Summary:** Uses GitHub's redesigned, animated signup flow, which respects reduced-motion preferences, as proof that accessible design and visual beauty can coexist.
- **Key points:** Beauty and accessibility aren't in conflict; Honors prefers-reduced-motion; Persistent advocacy changes organizations
- **Page status:** ok

### 40. What disabled people have to give up in the name of accessibility (privacy rights of people with disabilities)

- **URL:** https://accessaces.com/what-disabled-people-have-to-give-up-in-the-name-of-accessibility/
- **Source:** Access Aces · article / opinion
- **Tags:** Lived experience & culture
- **My comments:** Privacy for disabled people on apps | Interesting argument for why shouldn’t track if someone is using a screen reader
- **Summary:** A blind author argues that detecting assistive technology violates privacy by forcing disability disclosure, and that separate 'accessible' versions, remote sighted-assistance apps, overlays and connected devices trade disabled people's data for access.
- **Key points:** AT detection discloses disability without consent; Separate accessible versions are inferior; Assistance apps collect sensitive data; Overlays can track users across sites
- **Page status:** ok

### 41. Does Gemini Generate Accessible Android Apps?

- **URL:** https://eevis.codes/blog/2025-03-31/does-gemini-create-accessible-android-apps/?ref=accessible-mobile-apps-weekly.ghost.io
- **Source:** Eevis Panula · 2025-03-31 · article
- **Tags:** AI, Android
- **My comments:** Nice demonstration explaining why certain innocuous AX code causes problems in Android
- **Summary:** Tests Google's Gemini generating a Jetpack Compose Android app in two iterations. The first had major issues (redundant contentDescriptions, missing scroll, extra focus stops); the second was better, for unclear reasons. Tested with TalkBack, Switch Access and more.
- **Key points:** AI repeats inaccessible patterns from training data; Redundant contentDescription hurts screen reader users; focusable() + clickable() creates duplicate tab stops; Test with multiple assistive technologies
- **Page status:** ok

### 42. How to meet SC 2.5.3 Label in Name

- **URL:** https://vispero.com/resources/how-to-meet-sc-2-5-3-label-in-name/
- **Originally saved as:** https://www.tpgi.com/how-to-meet-sc-2-5-3-label-in-name/
- **Source:** Akash Shukla (TPGi / Vispero) · 2025-04-21 · article
- **Tags:** Voice & switch control, WCAG & standards, Forms
- **My comments:** End of article keeps tips on what to do if visible and ax label can’t match
- **Summary:** Explains WCAG 2.5.3 Label in Name: a control's accessible name must contain its visible label so speech-input users can say what they see. Covers common failures (missing names, mismatched text, extra interspersed words, reordering) and best practice of identical or label-first names.
- **Key points:** Name should match or start with visible label; No interspersed words or reordering; iOS 18+ Voice Control accepts names that begin with the label
- **Page status:** ok

### 43. A Decade of Employment

- **URL:** https://blakewatson.com/journal/a-decade-of-employment/
- **Source:** Blake Watson · 2025-05-04 · personal essay
- **Tags:** Lived experience & culture
- **My comments:** Person with spinal muscular atrophy describes their path to employment
- **Summary:** A web developer with spinal muscular atrophy reflects on ten years of employment after six years unemployed, his path into web design, remote work, and how means-tested, state-by-state disability programs discourage employment.
- **Key points:** Persistent portfolio-building led to a job; Remote work since 2019; Means testing creates work disincentives; Advocates better disability support programs
- **Page status:** ok

### 44. Everything's More Complicated in Groups: Required Groups

- **URL:** https://vispero.com/resources/everythings-more-complicated-in-groups-required-groups/
- **Originally saved as:** https://www.tpgi.com/everythings-more-complicated-in-groups-required-groups/
- **Source:** Alicia Evans (TPGi / Vispero) · 2025-05-14 · article
- **Tags:** Forms, ARIA
- **My comments:** Discussion of required for groups | I like how in-depth this article is, author clearly has extensive AX experience
- **Summary:** How to communicate that a group of radio buttons or checkboxes is required: use fieldset/legend, note aria-required doesn't work on fieldset, put the asterisk on the group label, add 'required' text to the legend, and state rules like 'pick at least one' for checkboxes.
- **Key points:** fieldset + legend; aria-required not valid on fieldset; Required indicator on the legend; Consider a select instead
- **Page status:** ok

### 45. My Request to Google on Accessibility

- **URL:** https://adrianroselli.com/2025/05/my-request-to-google-on-accessibility.html
- **Source:** Adrian Roselli · 2025-05 · article / opinion
- **Tags:** Programs & process
- **My comments:** Request to Google for releases and accessibility
- **Summary:** Criticizes Google for repeatedly shipping web-platform features with accessibility barriers (e.g., toasts, CSS carousels) and sidelining accessibility experts and disabled users; asks that features meet WCAG AA before release.
- **Key points:** Pattern of inaccessible platform features; Experts excluded and dismissed; Require WCAG AA before shipping
- **Page status:** ok

### 46. Guidance on Applying WCAG 2.2 to Mobile Applications (WCAG2Mobile)

- **URL:** https://www.w3.org/TR/wcag2mobile-22/?ref=accessible-mobile-apps-weekly.ghost.io
- **Source:** W3C Mobile Accessibility Task Force · 2025-05-06 · standard / W3C note
- **Tags:** WCAG & standards, Mobile apps
- **My comments:** Draft of Mobile WCAG standards
- **Summary:** W3C draft note on applying WCAG 2.2 A and AA success criteria to native, mobile web and hybrid apps, replacing web terms (e.g., 'web page') with mobile concepts like screens and views. Informative, not normative.
- **Key points:** Covers all WCAG 2.2 A/AA criteria for mobile; Maps web terminology to screens/views; Informative guidance only; Excludes hardware, AAA and wearables
- **Page status:** ok

### 47. Apple unveils powerful accessibility features coming later this year

- **URL:** https://www.apple.com/newsroom/2025/05/apple-unveils-powerful-accessibility-features-coming-later-this-year/
- **Source:** Apple Newsroom · 2025-05-13 · press release
- **Tags:** iOS
- **My comments:** New Apple AX features
- **Summary:** Apple's 2025 accessibility announcements: App Store Accessibility Nutrition Labels, Magnifier for Mac, Braille Access, Accessibility Reader, Live Captions on Apple Watch, Vision Pro zoom and Live Recognition, and Switch Control for brain-computer interfaces.
- **Key points:** Accessibility Nutrition Labels in the App Store; Magnifier on Mac; Braille Access note-taker; Accessibility Reader; BCI support in Switch Control
- **Page status:** ok

### 48. AAA11Y: Accessible Website Gallery

- **URL:** https://www.aaa11y.com/en/search/?level=aa
- **Source:** Torque, Inc. · gallery / resource
- **Tags:** Visual design & color, Learning resources
- **My comments:** Website of accessible sites, can filter by WCAG level
- **Summary:** A curated gallery of well-designed websites selected for accessibility, filterable by WCAG level (A/AA/AAA), site type, industry and colour.
- **Key points:** Inspiration for accessible design; Filter by WCAG level; English/Japanese
- **Page status:** ok

### 49. Where to Put Focus When Opening a Modal Dialog

- **URL:** https://adrianroselli.com/2025/06/where-to-put-focus-when-opening-a-modal-dialog.html
- **Source:** Adrian Roselli · 2025-06-06 · article
- **Tags:** HTML & components, Focus & keyboard
- **My comments:** Focus in dialogs
- **Summary:** Rejects a single rule for initial focus in modal dialogs: it depends on content type (simple message, interactive, action-required, form), length, and the risk of accidental actions. Includes screen reader testing showing inconsistent dialog-role announcements.
- **Key points:** Short messages: focus close button can be fine; Long/complex content: focus the dialog or heading; Consider undoability of actions; Screen readers announce dialog role inconsistently
- **Page status:** ok

### 50. From Curiosity to Creation: The Story Behind Accessibility Nerd

- **URL:** https://equalentry.com/ai-accessibility/
- **Source:** Equal Entry · 2025-06-17 · interview
- **Tags:** AI, Images & alt text
- **My comments:** Accessibility Nerd
- **Summary:** Interview with Cameron Cundiff about his Accessibility Nerd projects: Image Describer (a Gemini-based Chrome extension for image descriptions with follow-up questions) and a11y-agent, a CLI that pairs linting with AI to help developers fix issues interactively.
- **Key points:** AI augments, not replaces, accessibility expertise; Combine linting with AI to limit hallucination; Targets mainstream engineers
- **Page status:** ok

### 51. Implement WCAG Rules in Your Infographics

- **URL:** https://www.a11y-collective.com/blog/accessible-infographics/
- **Source:** The A11Y Collective · 2025-06-26 · guide
- **Tags:** Visual design & color, Images & alt text, WCAG & standards
- **My comments:** Mentions course for IAAP
- **Summary:** How to make web infographics accessible: simple design, text transcripts and alt text, 4.5:1 contrast and not relying on colour, controllable animation, semantic HTML/SVG rather than flat images, and testing.
- **Key points:** Limit data points; Provide transcripts for complex graphics; Don't rely on colour alone; Prefer HTML/SVG over images
- **Page status:** ok

### 52. CPACC Quality Content Providers

- **URL:** https://www.accessibilityassociation.org/cpacc-quality-content-providers
- **Source:** International Association of Accessibility Professionals (IAAP) · resource list
- **Tags:** Community & careers, Learning resources
- **My comments:** CPACC CEAC opportunities
- **Page status:** unreadable (Page content couldn't be extracted (likely rendered by script))

### 53. Robust roles on Android

- **URL:** https://vispero.com/resources/robust-roles-on-android/
- **Originally saved as:** https://www.tpgi.com/robust-roles-on-android/
- **Source:** TPGi (now Vispero) · article
- **Tags:** Android
- **My comments:** Good explanation why roles need to be added to correct ax property
- **Page status:** moved (TPGi blog moved to Vispero; the new page couldn't be read automatically)

### 54. 2025 Midyear Accessibility Lawsuit Report: Key Legal Trends

- **URL:** https://blog.usablenet.com/2025-midyear-accessibility-lawsuit-report-key-legal-trends
- **Source:** Jason Taylor (UsableNet) · 2025-07-09 · report
- **Tags:** Law & policy, Statistics
- **My comments:** Mid-year Lawsuit report for 2025
- **Summary:** Over 2,000 digital accessibility lawsuits were filed in the first half of 2025, with a projected ~20% rise for the year. Filings are shifting to state courts (especially New York), e-commerce is the top target, and accessibility widgets still offer no legal protection.
- **Key points:** Projected ~4,975 suits in 2025; New York state courts dominate; E-commerce ~69% of suits, food service ~18%; New plaintiff firms entering; Widgets don't prevent lawsuits
- **Page status:** ok

### 55. Accessibility and the agentic web

- **URL:** https://tetralogical.com/blog/2025/08/08/accessibility-and-the-agentic-web/
- **Source:** Léonie Watson (TetraLogical) · 2025-08-08 · article
- **Tags:** AI
- **My comments:** Accessibility and agentic web
- **Summary:** Considers how agentic AI (e.g., conversational shopping agents) could help disabled people get things done without navigating websites, while raising concerns about inconsistent content, falling web traffic and unclear legal obligations.
- **Key points:** Technically accessible sites can still lack needed product info; Agents act for users via conversation; AI search reducing site traffic; Open questions on content consistency and legal duty
- **Page status:** ok

### 56. Can components conform to WCAG?

- **URL:** https://hidde.blog/component-conformance/
- **Source:** Hidde de Vries · 2025-08-13 · article
- **Tags:** WCAG & standards, HTML & components, Programs & process
- **My comments:** Components and accessibility
- **Summary:** WCAG conformance applies only to full pages, not components, because accessibility depends on customization, combination and context. Components should be built and documented for accessibility, but real conformance is assessed on the finished experience.
- **Key points:** Conformance = full pages only; Customization and composition change outcomes; Context breaks things (e.g., hidden focus indicators); Design systems should document what's been tested
- **Page status:** ok

### 57. "Best practice" is just your opinion

- **URL:** https://www.craigabbott.co.uk/blog/best-practice-is-just-your-opinion/
- **Source:** Craig Abbott · 2025-08-20 · article
- **Tags:** WCAG & standards, Programs & process
- **My comments:** Nice article about tension with WCAG compliance and being accessible
- **Summary:** Argues that labeling audit findings 'best practice' makes real barriers sound optional, is inconsistent between practitioners and can sound arrogant. Suggests 'standard of care' or just 'accessibility issues' instead.
- **Key points:** 'Best practice' implies optional; Practitioners disagree on it; It changes with technology; Alternatives: 'standard of care', 'accessibility issue'
- **Page status:** ok

### 58. Accessibility features reference (Chrome DevTools)

- **URL:** https://developer.chrome.com/docs/devtools/accessibility/reference
- **Source:** Google Chrome Developers · 2026-05-28 · documentation
- **Tags:** Testing & auditing, Learning resources
- **My comments:** Chrome AX reference
- **Summary:** Reference for Chrome DevTools accessibility features: Lighthouse audits, the Accessibility pane and accessibility tree, ARIA inspection, emulating vision deficiencies and media preferences, reflow testing and finding low-contrast text.
- **Key points:** Lighthouse audits; Accessibility tree inspection; Emulate vision deficiencies / reduced motion; Contrast issue detection
- **Page status:** ok

### 59. Open UI

- **URL:** https://open-ui.org/
- **Source:** Open UI Community Group (W3C) · organization / standards
- **Tags:** HTML & components, WCAG & standards
- **My comments:** Open UI Project | W3C community effort to improve UI components
- **Summary:** W3C community group working to let developers style and extend built-in UI controls (select, checkbox, date pickers) by specifying their parts, states, behaviors and accessibility requirements, with research on 30+ components.
- **Key points:** Specs for native UI components; Research across 30+ components; Proposals like customizable select; Open to contributors
- **Page status:** ok

### 60. Study finds neurodiverse workers more satisfied with AI assistants

- **URL:** https://arstechnica.com/information-technology/2025/09/study-finds-neurodiverse-workers-more-satisfied-with-ai-assistants/
- **Source:** Ars Technica · 2025-09 · news
- **Tags:** AI, Cognitive, reading & mental health
- **My comments:** Neurodivergent benefiting from AI
- **Page status:** blocked (Site blocks automated reading)

### 61. Screen readers do not need to be saved by AI

- **URL:** https://www.craigabbott.co.uk/blog/screen-readers-do-not-need-saved-by-ai/
- **Source:** Craig Abbott · 2025-09-14 · article / opinion
- **Tags:** AI, Screen readers & braille
- **My comments:** Argument not to use AI for screen reader users
- **Summary:** Argues against building LLMs into screen readers: output is inconsistent, it would be costly to build and test, too slow at 600-800 wpm listening speeds, energy-hungry, and would raise costs for disabled users. The real fix is better human-authored content.
- **Key points:** LLM output is inconsistent; Too slow for fast screen reader users; Hardware/energy/cost burden on disabled users; Teach inclusive authoring instead
- **Page status:** ok

### 62. Mobile Accessibility at W3C

- **URL:** https://www.w3.org/WAI/standards-guidelines/mobile/
- **Source:** Shawn Lawton Henry (W3C WAI) · 2025-05-06 · standards overview
- **Tags:** WCAG & standards, Mobile apps
- **My comments:** W3C Mobile AX standards
- **Summary:** Explains that W3C covers mobile accessibility through existing standards (WCAG, UAAG, ATAG, WAI-ARIA) rather than separate mobile guidelines, and points to WCAG2Mobile guidance and the Mobile Accessibility Task Force.
- **Key points:** No separate mobile guidelines; Covers phones, tablets, wearables, appliances; Links to WCAG2Mobile guidance
- **Page status:** ok

### 63. Appt Mobile Accessibility News, Issue #75

- **URL:** https://www.appt.news/appt-news-accessible-mobile-apps-issue-75/?ref=accessible-mobile-apps-weekly-newsletter
- **Source:** Appt (guest: Daniel Devesa Derksen-Staats) · 2025-11-01 · newsletter
- **Tags:** Mobile apps, Community & careers
- **My comments:** A lot of Mobile AX goodies in here
- **Summary:** Newsletter issue with iOS accessibility takeaways from SwiftLeeds (developers underestimate issues; native components help) plus recent iOS and Android resources on custom controls, keyboard access and focus management.
- **Key points:** Awareness is the main barrier; Native components reduce issues; Individual developers drive change; EAA adds momentum
- **Page status:** ok

### 64. Accessible iOS design: how Forza Football included blind users

- **URL:** https://axesslab.com/designing-accessible-football-lineups-for-blind-users-lessons-from-forza-football/
- **Source:** Diogo Melo (Axess Lab) · 2025-11-04 · case study
- **Tags:** iOS, Screen readers & braille
- **My comments:** Nice article about Forza football ax features on iOS
- **Summary:** How Forza Football made visual team lineups work with VoiceOver by using accessibilitySortPriority so players are read goalkeeper-to-forward, matching football conventions rather than default reading order.
- **Key points:** Default VoiceOver order didn't match the domain; accessibilitySortPriority changes order without changing layout; Applied to bench players too
- **Page status:** ok

### 65. Why Separate Guest and Logged In States Create Accessibility Barriers

- **URL:** https://buttondown.com/access-ability/archive/why-separate-guest-and-logged-in-states-create/
- **Source:** Access * Ability newsletter · 2025-11-05 · article
- **Tags:** HTML & components, Cognitive, reading & mental health
- **My comments:** Mentions that 70% of sites sued in 2025 were for e-commerce
- **Summary:** Losing a cart or form progress when a user logs in forces disabled users to redo effortful work. Login should be 'a continuation point, not a reset point'; preserve progress or warn users.
- **Key points:** Preserve carts/forms across login; Extra burden for AT users; Cart abandonment costs revenue; E-commerce is most-sued sector
- **Page status:** ok

### 66. Catching up on accessibility with AI chat

- **URL:** https://medium.com/design-ibm/catching-up-on-accessibility-with-ai-chat-1129be33c184
- **Source:** Mike Gower (IBM Design) · 2025-04-22 · article
- **Tags:** AI, HTML & components, Focus & keyboard
- **My comments:** AI and AX messaging
- **Summary:** Nine design considerations for accessible AI chat interfaces, from keyboard navigation of inverted chat logs to feedback-button clutter, voice input, input-area controls, floating launcher tab stops and docked panels, with good and bad examples.
- **Key points:** Inverted chat order hurts keyboard users; Too many feedback buttons add noise; Floating launchers create hard-to-reach tab stops; Docked panels avoid obscured focus; Region-level keyboard navigation
- **Page status:** ok

### 67. Link vs Button: Choosing the Right Element for the Right Job

- **URL:** https://vispero.com/resources/link-vs-button-choosing-the-right-element-for-the-right-job/
- **Originally saved as:** https://www.tpgi.com/link-vs-button-choosing-the-right-element-for-the-right-job/
- **Source:** Deeksha Yadav (TPGi / Vispero) · 2025-11-10 · article
- **Tags:** HTML & components
- **My comments:** Nice article about link vs button
- **Summary:** Links navigate to a location (need href and descriptive text); buttons perform actions on the page. Correct semantics matter because screen readers announce roles and users navigate by them, even though misuse isn't strictly a WCAG failure.
- **Key points:** Links go somewhere; buttons do something; Links need href; Screen readers announce roles differently; Not a strict WCAG failure but affects usability
- **Page status:** ok

### 68. Practical guide to mobile accessibility testing

- **URL:** https://abra.ai/blog/practical-guide-to-mobile-accessibility-testing
- **Source:** Abra · 2026-02-28 · guide
- **Tags:** Mobile apps, Testing & auditing
- **My comments:** Thorough article about how to test for accessibility
- **Summary:** A hands-on manual testing guide for mobile apps with an 11-category checklist (contrast, text, non-text content, media, controls, gestures, status messages, keyboard, screen readers, and more), advising testing screen by screen with one assistive technology at a time.
- **Key points:** Manual testing is essential; One AT at a time, screen by screen; 11 test categories; Document clearly for prioritization
- **Page status:** ok

### 69. How Button Traits can make a chaotic iOS app accessible

- **URL:** https://axesslab.com/how-button-traits-can-make-a-chaotic-ios-app-accessible/
- **Source:** Diogo Melo (Axess Lab) · 2025-12-05 · article
- **Tags:** iOS, Screen readers & braille, Voice & switch control
- **My comments:** Nice demonstration of how button traits drastically improve UI
- **Summary:** Starts from a deliberately inaccessible SwiftUI app and shows that two fixes, grouping elements and adding the .isButton trait, made it work with VoiceOver, Full Keyboard Access and Voice Control.
- **Key points:** Semantics fix multiple assistive technologies at once; Group and hide decorative elements; The .isButton trait is recognized by VO, FKA and Voice Control; Small code changes, big impact
- **Page status:** ok

### 70. Why Are 38 Percent of Stanford Students Saying They're Disabled?

- **URL:** https://reason.com/2025/12/04/why-are-38-percent-of-stanford-students-saying-theyre-disabled/
- **Source:** Emma Camp (Reason) · 2025-12-04 · opinion
- **Tags:** Lived experience & culture, Cognitive, reading & mental health
- **My comments:** Article questioning the rise in disability accommodations at elite colleges
- **Summary:** Opinion piece questioning very high disability-accommodation rates at elite universities (38% at Stanford), mostly for mental health and learning disabilities, attributing them to social media, looser diagnostic criteria and risk-averse affluent families. A contested viewpoint.
- **Key points:** Elite colleges report very high accommodation rates; Community colleges report ~3-4%; Author blames social media and DSM changes; Argues accommodations can be overused
- **Page status:** ok

### 71. The Next Revolution in Design: Emotional Accessibility

- **URL:** https://www.fastcompany.com/91451256/the-next-revolution-in-design-emotional-accessibility
- **Source:** Ben Wintner (Fast Company) · 2025-12-01 · opinion
- **Tags:** Visual design & color, Lived experience & culture
- **My comments:** Discusses limitation of universal design, not about delighting the user
- **Summary:** Argues accessible design should go beyond compliance to how products make people feel, citing Michael Graves Design products that meet ADA standards while conveying dignity and pride.
- **Key points:** Universal design often lacks emotional connection; Design for dignity and belonging; Emotional connection drives adoption
- **Page status:** ok

### 72. 2026 Predictions: The Next Big Shifts in Web Accessibility

- **URL:** https://webaim.org/blog/2026-predictions/
- **Source:** John Northup (WebAIM) · 2025-12-22 · article
- **Tags:** WCAG & standards, AI, Programs & process
- **My comments:** WebAIM 2026 predictions
- **Summary:** WebAIM's seven predictions for 2026: AI speeds workflows but can't replace expert judgment, WCAG 2.2 becomes the procurement norm, native HTML over custom widgets, accessibility debt treated as business risk, web and native practice converging, respecting user preferences, and WCAG 3 thinking influencing practice early.
- **Key points:** AI helps but humans judge quality; WCAG 2.2 becomes standard; Prefer native HTML; Accessibility debt = business risk; Respect system preferences
- **Page status:** ok

### 73. What really happens when a user clicks an accordion button?

- **URL:** https://www.maxdesign.com.au/articles/accordion-button.html
- **Source:** Russ Weakley (Max Design) · 2025-12-04 · article
- **Tags:** HTML & components, Screen readers & braille
- **My comments:** Nice explanation of how button works with JavaScript and browser
- **Summary:** Traces a click on an accordion button through hit-testing, JavaScript, DOM updates, accessibility-tree updates, OS accessibility APIs and the screen reader's speech queue, showing these happen concurrently rather than as a simple sequence.
- **Key points:** DOM changes update the accessibility tree; Events cross OS accessibility APIs; Screen readers queue utterances; Concurrent, not linear
- **Page status:** ok

### 74. Traveling with a Service Dog, Part 1

- **URL:** https://accessaces.com/traveling-with-a-service-dog-part-1/
- **Source:** Access Aces · article / personal story
- **Tags:** Lived experience & culture
- **My comments:** Nice narrative about having a service dog at airport
- **Page status:** unreadable (Site rate-limited automated reading)

### 75. Dark Mode: Essential not a Preference

- **URL:** https://seemeplease.com/blog/dark-mode
- **Source:** Katie McDermott (See Me Please) · 2025-03-04 · article
- **Tags:** Visual design & color
- **My comments:** Dark mode
- **Summary:** Argues dark mode is an accessibility need, not a cosmetic preference, based on user testing where it was the most requested feature among low-vision, blind and neurodivergent testers. WCAG doesn't require it, and overlays or colour inversion are poor substitutes for native dark mode.
- **Key points:** ~75% of low-vision testers strongly preferred dark mode; Reduces glare and headaches; WCAG conformance doesn't guarantee usability; Native dark mode beats inversion/overlays
- **Page status:** ok

### 76. Accessible faux-nested interactive controls

- **URL:** https://piccalil.li/blog/accessible-faux-nested-interactive-controls/
- **Source:** Eric Bailey (Piccalilli) · 2026-01-15 · article
- **Tags:** HTML & components
- **My comments:** How to make entire list cell clickable, but have clickable child elements
- **Summary:** Never nest interactive elements; instead use the 'semantic breakout' technique (a pseudo-element stretches the primary link over the card, with z-index keeping secondary actions clickable) to get the look of nested controls accessibly.
- **Key points:** Never nest interactive elements; Pseudo-element breakout for card links; Keep accessible names concise; Confirm destructive actions
- **Page status:** ok

### 77. Making an iOS E-Commerce Product List Accessible to VoiceOver and Beyond

- **URL:** https://axesslab.com/making-an-ios-e-commerce-product-list-accessible-to-voiceover-and-beyond/
- **Source:** Diogo Melo (Axess Lab) · 2026-01-08 · article
- **Tags:** iOS, Screen readers & braille, Voice & switch control
- **My comments:** Nice article about how to make an iOS app accessible to screen reader and keyboard users
- **Summary:** A blind iOS developer fixes a product list and wishlist for VoiceOver, Full Keyboard Access and Voice Control: star-rating labels, grouping product info, and accessibility actions for cart/wishlist, noting Voice Control needs directly exposed controls.
- **Key points:** Label star ratings; Group product info into one element; Accessibility actions behave differently per AT; Voice Control needs visible controls
- **Page status:** ok

### 78. Optimizing VoiceOver in an iOS E-Commerce App with Conditional Accessibility

- **URL:** https://axesslab.com/optimizing-voiceover-in-an-ios-e-commerce-app-with-conditional-accessibility/
- **Source:** Diogo Melo (Axess Lab) · 2026-01-08 · article
- **Tags:** iOS, Screen readers & braille
- **My comments:** Nice article on making iOS app accessible for VoiceOver without detrimentally affecting other assistive technologies
- **Summary:** Shows how to detect when VoiceOver is running (SwiftUI environment value or UIKit notifications) and switch to a combined, actions-based model for VoiceOver while leaving Full Keyboard Access and Voice Control with exposed controls.
- **Key points:** @Environment(\.accessibilityVoiceOverEnabled); Combine elements + custom actions for VO; Adjustable actions for efficiency; Each AT gets an optimized model
- **Page status:** ok

### 79. Here's how to instruct a LLM to reference the ARIA Authoring Practices Guide

- **URL:** https://ericwbailey.website/published/heres-how-to-instruct-a-llm-to-reference-the-aria-authoring-practices-guide/
- **Source:** Eric Bailey · 2026-02-16 · article
- **Tags:** AI, ARIA
- **My comments:** How to be careful using APG for LLM
- **Summary:** Warns against feeding the whole ARIA Authoring Practices Guide to LLMs because its examples over-favor ARIA and vary in AT support. Recommends pointing LLMs only at pattern descriptions and keyboard-interaction sections, and prioritizing semantic HTML and your own design-system docs.
- **Key points:** APG demonstrates ARIA; it isn't a pattern library; Examples have uneven AT support; Reference only 'About' and 'Keyboard Interaction' sections; Invest in your own semantic HTML docs
- **Page status:** ok

### 80. Between the Dots: What Designers Miss Without Braille Users

- **URL:** https://www.helenkeller.org/between-the-dots-what-designers-miss-without-braille-users/
- **Source:** Megan Dausch (Helen Keller National Center) · 2026-01-30 · article
- **Tags:** Screen readers & braille, Visual design & color
- **My comments:** Nice article about braille users
- **Summary:** Braille display users read through a window of 12-80 cells, so verbose labels, unpredictable focus changes and fleeting dynamic content hit them hard. Self-voicing and audio-only interfaces exclude braille and DeafBlind users; include braille users in testing.
- **Key points:** Concise labels matter on braille displays; Logical, predictable focus; Dynamic notifications can be missed; Provide transcripts; test with braille users
- **Page status:** ok

### 81. I used Claude Code and GSD to build the accessibility tool I've always wanted

- **URL:** https://blakewatson.com/journal/i-used-claude-code-and-gsd-to-build-the-accessibility-tool-ive-always-wanted/
- **Source:** Blake Watson · 2026 · article / personal story
- **Tags:** AI, Lived experience & culture
- **My comments:** Vibe coding an ax feature
- **Summary:** A developer with spinal muscular atrophy used Claude Code with the GSD workflow to build 'Scroll My Mac', a macOS app for click-and-drag scrolling, in about 8 hours and roughly $80 of usage, and reflects on AI's promise and concerns for disabled makers.
- **Key points:** Custom assistive tech built in ~8 hours; AI can democratize AT creation; Free on GitHub, signed and notarized; Concerns about AI and developers' futures
- **Page status:** ok

### 82. How aria-labelledby really works

- **URL:** https://www.maxdesign.com.au/articles/aria-labelledby.html
- **Source:** Russ Weakley (Max Design) · 2025-12-17 · article
- **Tags:** ARIA
- **My comments:** How aria-labelledby works under the hood
- **Summary:** Explains aria-labelledby: it names an element from existing on-page text by ID reference, outranks aria-label and native naming, can reference multiple IDs (including itself) and hidden content, fails silently on broken IDs, and can't cross shadow DOM.
- **Key points:** Highest precedence in name calculation; Multiple space-separated IDs; Can reference hidden content; Can't cross shadow DOM; fails silently
- **Page status:** ok

### 83. More about screen reader speech queues

- **URL:** https://www.maxdesign.com.au/articles/more-about-speech-queues.html
- **Source:** Russ Weakley (Max Design) · 2025-12-18 · article
- **Tags:** Screen readers & braille
- **My comments:** Nice explanation of how speech queues work for screen readers
- **Summary:** Uses a traffic-intersection analogy to explain why screen readers may or may not announce typed characters: typing echo is low priority and debounced, focus changes interrupt it, DOM batching merges changes, and some fields suppress echo.
- **Key points:** Typing echo is low priority and debounced; Focus changes can pre-empt announcements; Screen reader output is filtered, not a log
- **Page status:** ok

### 84. aria-haspopup might not do what you think it does

- **URL:** https://www.matuzo.at/blog/2026/aria-haspopup-menu
- **Source:** Manuel Matuzović · 2026-02-23 · article
- **Tags:** ARIA, HTML & components
- **My comments:** Nice article explaining menu vs navigation
- **Summary:** aria-haspopup is often misused on navigation disclosure buttons. It declares a popup of a specific role (menu, listbox, tree, grid, dialog), and screen readers like JAWS then expect menu keyboard behavior. For site navigation, use aria-expanded instead.
- **Key points:** Popup must have the matching role; Navigation (links) ≠ menu (actions); JAWS expects menu keyboard behavior; Use aria-expanded for nav disclosures
- **Page status:** ok

### 85. A11y 101: 2.5.1 Pointer Gestures

- **URL:** https://tarnoff.info/2026/02/23/a11y-101-2-5-1-pointer-gestures/
- **Source:** Nat Tarnoff · 2026-02-23 · guide
- **Tags:** WCAG & standards, Focus & keyboard
- **My comments:** Nice explanation of how to address WCAG 2.5.1 with various options
- **Summary:** Explains WCAG 2.5.1 Pointer Gestures: multipoint or path-based gestures need single-pointer alternatives, and keyboard support should cover all mouse/touch interactions, e.g., buttons or arrow keys for drag-and-drop with live-region announcements.
- **Key points:** Single-pointer alternative for multipoint/path gestures; Drag-and-drop needs button/arrow alternatives; Canvas tools need native controls; Keyboard parity for all interactions
- **Page status:** ok

### 86. If you thought the speed of writing code was your problem - you have bigger problems

- **URL:** https://andrewmurphy.io/blog/if-you-thought-the-speed-of-writing-code-was-your-problem-you-have-bigger-problems
- **Source:** Andrew Murphy · 2026-03-17 · article
- **Tags:** AI, Programs & process
- **My comments:** Great article about issue with AI coding
- **Summary:** Argues AI coding tools speed up a step that usually isn't the bottleneck; real delays come from unclear requirements, review queues, deployment fear and organizational friction, so teams should map value streams and measure cycle time.
- **Key points:** Optimize the actual bottleneck; Coding speed rarely is it; Measure cycle time, limit WIP; Faster output can make things worse
- **Page status:** ok

### 87. #365DaysIOSAccessibility

- **URL:** https://accessibilityupto11.com/365-days-ios-accessibility/
- **Source:** Dani Devesa Derksen-Staats (Accessibility up to 11) · resource collection
- **Tags:** iOS, Learning resources
- **My comments:** 365 tips for ios AX - like the format
- **Summary:** A year-long series of short daily iOS accessibility tips (230+ posts) on SwiftUI/UIKit accessibility modifiers, VoiceOver, Voice Control, Switch Control, Full Keyboard Access, Dynamic Type and testing.
- **Key points:** Bite-sized daily tips; SwiftUI and UIKit APIs; Covers many assistive technologies
- **Page status:** ok

### 88. AI Doesn't Fix Accessible Systems. It Depends on Them.

- **URL:** https://annaecook.com/writing/2026/ai-doesnt-fix-accessible-systems-it-depends-on-them
- **Source:** Anna E. Cook · 2026-05-04 · article
- **Tags:** AI, Programs & process
- **My comments:** AI perpetuating inaccessible products
- **Summary:** Argues AI can't fix accessibility; it relies on accessible, semantic, consistent systems to work at all. Cites WebAIM Million 2026 showing the first regression in six years, which she links to AI-assisted coding and budgets shifting from accessibility to AI.
- **Key points:** AI reproduces training-data problems; Accessible infrastructure enables AI; WebAIM Million 2026 shows regression; Budgets shifting away from accessibility
- **Page status:** ok

### 89. Learning to develop more accessible iOS games

- **URL:** https://accessibilityupto11.com/post/2026-02-22-01/
- **Source:** Dani Devesa Derksen-Staats (Accessibility up to 11) · 2026-02-22 · article
- **Tags:** iOS
- **My comments:** This author has experience with iOS AX
- **Summary:** How the author made RetroRapid!, an Apple Watch racing game, accessible: multiple inputs (Digital Crown, swipes, taps, keyboard), audio cues using musical notes, haptics, customizable settings, and non-stigmatizing difficulty names.
- **Key points:** Multiple input methods; Audio and haptic feedback; Customizable difficulty and presentation; 'Cruise/Fast/Rapid' instead of Easy/Hard
- **Page status:** ok

### 90. Building a general-purpose accessibility agent, and what we learned in the process

- **URL:** https://github.blog/ai-and-ml/github-copilot/building-a-general-purpose-accessibility-agent-and-what-we-learned-in-the-process/
- **Source:** Eric Bailey (GitHub Blog) · 2026-05-15 · article / case study
- **Tags:** AI, Testing & auditing
- **My comments:** AX agent developed by Github
- **Summary:** GitHub's pilot accessibility agent reviews pull requests and fixes simple issues; it has reviewed 3,535 PRs with a 68% resolution rate. Lessons: separate reviewer and implementer sub-agents, linear templated instructions, historical audit data, and escalation to humans.
- **Key points:** Reviewer + implementer sub-agents; Templates reduce hallucination; Past audit data improves results; ~36% of WCAG criteria need manual evaluation
- **Page status:** ok

### 91. A Practical Guide to Flutter Accessibility Part 2: Hiding Noise, Exposing Actions

- **URL:** https://www.thedroidsonroids.com/blog/flutter-accessibility-guide-part-2
- **Source:** Karol Wrótniak (Droids On Roids) · 2026-04-23 · guide
- **Tags:** Mobile apps
- **My comments:** Accessibility for cross-platform framework, Flutter
- **Summary:** Flutter accessibility techniques: ExcludeSemantics for decorative elements, BlockSemantics behind overlays, customSemanticsActions as gesture alternatives, and live regions for dynamic updates, compared with SwiftUI and Compose equivalents.
- **Key points:** ExcludeSemantics for noise; BlockSemantics for overlays; Custom actions replace gestures; Semantics(liveRegion: true)
- **Page status:** ok

### 92. Lovable's AI built a 100% accessible site – or did it?

- **URL:** https://axesslab.com/lovable/
- **Source:** Hampus Sethfors (Axess Lab) · 2026-05-13 · audit / case study
- **Tags:** AI, Testing & auditing, Screen readers & braille
- **My comments:** Nice analysis of accessibility issues with an iOS app
- **Summary:** Axess Lab tested a conference site built with Lovable, which claimed 100% accessibility. A screen reader user found SPA focus problems, hidden menu/modal content being read, missing aria-expanded, skipped headings, label mismatches for voice control and a poorly marked language switcher.
- **Key points:** Automated '100%' score was misleading; SPA focus landed mid-page; Hidden content still read; Skipped headings, missing aria-expanded
- **Page status:** ok

### 93. AppleVis

- **URL:** https://www.applevis.com/
- **Source:** AppleVis · community / resource hub
- **Tags:** iOS, Community & careers
- **My comments:** AppleVis
- **Summary:** Community website for blind and low-vision users of Apple products, with app accessibility reviews and directory, guides, podcasts, forums and news about VoiceOver and iOS/macOS accessibility.
- **Key points:** App accessibility directory and reviews; Guides and podcasts; Active blind user community
- **Page status:** ok (Summary written from the homepage structure)

### 94. 4 iOS display settings to check your app with

- **URL:** https://racheleditullio.com/blog/2026/05/4-ios-display-settings-to-check-your-app-with/
- **Source:** Rachele DiTullio · 2026-05 · article
- **Tags:** iOS, Testing & auditing
- **My comments:** Nice article on testing with different iOS settings, also has other related articles
- **Page status:** unreadable (Site rate-limited automated reading)

### 95. Why the accept attribute degrades file upload UX

- **URL:** https://adamsilver.io/blog/why-the-accept-attribute-degrades-file-upload-ux/
- **Source:** Adam Silver · 2026-05-31 · article
- **Tags:** Forms, WCAG & standards
- **My comments:** Article shows different interpretations of a WCAG criterion
- **Summary:** Argues against the accept attribute on file inputs: it greys out ineligible files without explanation, doesn't cover size limits or drag-and-drop, and hides errors rather than preventing them. Better to validate and show a clear error.
- **Key points:** Disabled files confuse users; Hint text often isn't read; Doesn't cover all validation; Error hiding ≠ error prevention
- **Page status:** ok

### 96. AIMAC: AI Model Accessibility Checker leaderboard

- **URL:** https://aimac.ai/
- **Source:** GAAD Foundation with ServiceNow · 2026-08-22 · benchmark
- **Tags:** AI, Testing & auditing
- **My comments:** AI model comparison for accessibility
- **Summary:** Benchmark that asks 60 AI models to generate web pages in 28 categories and measures WCAG 2.2 AA violations with axe-core ('accessibility debt'). Results vary widely by provider and version; price doesn't predict accessibility; colour contrast dominates failures.
- **Key points:** 60 models ranked; Contrast is ~90% of violations; Price doesn't predict results; Newer isn't always better
- **Page status:** ok

### 97. SEO is not accessibility, and we have the data to prove it

- **URL:** https://afixt.com/seo-is-not-accessibility-and-we-have-the-data-to-prove-it/
- **Source:** Karl Groves (AFixt) · 2026-06-11 · article / research
- **Tags:** Testing & auditing, Programs & process
- **My comments:** SEO vs accessibility
- **Summary:** Analysis of 20 audits and 100,000+ automated failures finds only a small fraction of accessibility checks relate to SEO. The most common failures (dynamic content, ARIA, contrast, keyboard) are invisible to search engines, and some SEO tactics conflict with accessibility.
- **Key points:** Only ~13-27% of checks are SEO-relevant; Search engines model one non-interactive user; Keyword-stuffed alt text hurts accessibility
- **Page status:** ok

### 98. Designing for people who are D/deaf

- **URL:** https://tetralogical.com/blog/2026/06/17/designing-for-deaf-people/
- **Source:** Ela Gorla (TetraLogical) · 2026-06-17 · article
- **Tags:** Deaf & hard of hearing
- **My comments:** Comprehensive article on how to design for deaf people
- **Summary:** Design considerations for D/deaf people beyond captions: accurate synced captions and transcripts, customizable captions, plain language, predefined form options, sign language for core content, and multiple contact methods instead of phone-only.
- **Key points:** Captions + transcripts; Plain language; Sign language for key content; Don't require phone contact
- **Page status:** ok

### 99. Handling Missing Data Without Breaking Accessibility

- **URL:** https://intopia.digital/articles/handling-missing-data-without-breaking-accessibility/
- **Source:** Nathan Ortiz (Intopia) · 2026-06-16 · article
- **Tags:** HTML & components, Screen readers & braille
- **My comments:** Nice article about how to handle when data is missing
- **Summary:** Five patterns for null or missing data in data-driven UIs so screen reader users don't meet empty elements and keyboard users don't land on dead controls: check data before rendering, don't style with empty elements, set defaults, use meaningful fallbacks, and put spacing on containers.
- **Key points:** Don't render empty DOM nodes; Don't use empty elements for layout; Set defaults; Fallback text only when useful
- **Page status:** ok

### 100. Designing with Mustard

- **URL:** https://annaecook.com/writing/2026/designing-with-mustard
- **Source:** Anna E. Cook · 2026-06-02 · essay
- **Tags:** AI, Visual design & color
- **My comments:** Insight about how discourse around AI is coercion, not invitation | Also mentions limitations of AI design prototyping for accessibility
- **Summary:** A satirical essay pushing back on 'adapt or perish' AI design-tool rhetoric: design needs thinking, collaboration and accountability; AI optimizes visual output while hiding structural and accessibility gaps.
- **Key points:** Prototypes answer specific questions; AI hides structural/accessibility flaws; Friction enables thinking; Humans stay accountable
- **Page status:** ok

### 101. Designing for people with reading disabilities

- **URL:** https://tetralogical.com/blog/2026/06/25/designing-for-reading-disabilities/
- **Source:** Grace Snow (TetraLogical) · 2026-06-25 · article
- **Tags:** Cognitive, reading & mental health, Visual design & color
- **My comments:** Nice article on how to design for reading disabilities
- **Summary:** Practical guidance for reducing reading effort: plain language and short sentences, left-aligned text at 70-80 characters, clear headings, legible fonts, a reading age around 9-11, expanded acronyms, and supporting visuals or audio.
- **Key points:** Plain language, reading age ~9-11; Left-aligned, 70-80 char lines; Distinct letterforms, tall x-height; Expand acronyms; add visuals/audio
- **Page status:** ok

### 102. 10 Tips for Building iOS Apps That Handle Dynamic Type Well

- **URL:** https://mobilea11y.com/blog/good-dynamic-type/
- **Source:** Mobile A11y · 2026-07-06 · guide
- **Tags:** iOS, Visual design & color
- **My comments:** iOS article about text - might be worth reading again
- **Summary:** Ten practical Dynamic Type tips: put text in scroll views, don't scale fixed bars, remove fixed heights, switch horizontal layouts to vertical at accessibility sizes, use line limits wisely, SF Symbols, @ScaledMetric, and test Bold Text and Display Zoom.
- **Key points:** Scroll views for text; No fixed heights; Stack vertically at large sizes; @ScaledMetric for custom elements
- **Page status:** ok

### 103. Here's a simple recipe for good image alt text

- **URL:** https://pedalpoint.com/2024/05/heres-a-simple-recipe-for-good-image-alt-text/?utm_source=convertkit&utm_medium=email&utm_campaign=How+to+write+great+image+alt+text+-+7172108
- **Source:** Pedal Point · 2024-05 · article
- **Tags:** Images & alt text
- **My comments:** Nice article on writing good alt text
- **Page status:** blocked (Page returned 401 (may require sign-in))

### 104. A11yjobs

- **URL:** https://www.a11yjobs.com/
- **Source:** A11yjobs · job board
- **Tags:** Community & careers
- **My comments:** Main job board for ax
- **Summary:** Job board for digital accessibility and assistive technology roles (consultants, engineers and more; remote, hybrid and on-site), plus newsletters, glossary, certifications and events.
- **Key points:** Accessibility-specific job listings; Remote and on-site roles; Career resources
- **Page status:** ok

### 105. The Problem with Blanks for People Who Are Blind or Low Vision

- **URL:** https://buttondown.com/access-ability/archive/the-problem-with-blanks-for-people-who-are-blind/
- **Source:** Access * Ability newsletter · 2026-07-01 · article
- **Tags:** Screen readers & braille, HTML & components
- **My comments:** Insightful article about blanks
- **Summary:** Blank space is ambiguous to screen reader users, who can't tell intentional emptiness from a loading failure. Use explicit text (e.g., 'None' in table cells), proper paragraph spacing instead of blank lines, and announced empty states.
- **Key points:** Fill empty table cells with 'N/A'/'None'; Use spacing tools, not blank lines; Announce empty states
- **Page status:** ok

### 106. Designing For Distressed Users: Why Mental Health Apps Shouldn't Follow Every UI Fashion

- **URL:** https://www.smashingmagazine.com/2026/07/designing-distressed-users-mental-health-apps-ui/
- **Source:** Kat Homan (Smashing Magazine) · 2026-07-09 · article
- **Tags:** Cognitive, reading & mental health, Visual design & color
- **My comments:** Nice article on mental health considerations
- **Summary:** With ~95% of mental health app users gone by day 30, argues trendy UI patterns add cognitive friction, emotional mismatch and inconsistency for distressed users; offers a five-point framework for judging trends.
- **Key points:** Novel UI adds cognitive load; Playful visuals can erode trust; Predictable navigation; Streaks/pushy notifications add pressure
- **Page status:** ok

### 107. The Perfect Cripple: A User Guide to Being Palatable

- **URL:** https://www.salient.org.nz/post/the-perfect-cripple-a-user-guide-to-being-palatable
- **Source:** Pluto Rennie (Salient) · 2026-05-10 · essay
- **Tags:** Lived experience & culture
- **My comments:** Interesting article about how you have to act a certain way when disabled
- **Summary:** Essay on the pressure for disabled people to present disability consistently and non-disruptively to be believed, while real bodies fluctuate; critiques care as a scarce, productivity-audited resource.
- **Key points:** Pressure to appear consistent and credible; Fluctuating disability is penalized; Need audited by productivity
- **Page status:** ok

### 108. Oh, it's happening to me

- **URL:** https://www.disabilitydebrief.org/debrief/oh-its-happening-to-me/
- **Source:** Peter Torres Fremlin (Disability Debrief) · 2026-07-08 · interview
- **Tags:** Lived experience & culture
- **My comments:** Overlap between ageism and disability, argues that we shouldn’t judge based on age
- **Summary:** Interview with anti-ageism activist Ashton Applewhite on how ageism and ableism intertwine, why older disabled people often resist disability identity, and adaptation and interdependence as shared human experiences.
- **Key points:** Ageism and ableism share roots; Internalized bias in both; Aging brings disability to most people
- **Page status:** ok

### 109. Can we make default tailwind a more accessible choice?

- **URL:** https://spatie.be/blog/can-we-make-default-tailwind-a-more-accessible-choice
- **Source:** Nick Bevers (Spatie) · 2026-08-07 · article
- **Tags:** Visual design & color, HTML & components
- **My comments:** Nice article that explains rem and how that works with page zoom
- **Summary:** Tailwind's rem-based breakpoints respond to users' browser font-size settings, which exceeds WCAG minimums, but can surprise developers who test at default size. Teams should choose deliberately between honoring font preferences and layout predictability.
- **Key points:** rem media queries follow the browser font setting; px breakpoints ignore it; A conscious design decision
- **Page status:** ok

### 110. Accessibility Legal Update July 2026

- **URL:** https://convergeaccessibility.com/2026/08/03/legal-update-july-2026/
- **Source:** Ken Nakata (Converge Accessibility) · 2026-08-03 · legal update
- **Tags:** Law & policy
- **My comments:** Judge ruled that need intent to return to a website in order to be a valid accessibility lawsuit - used to dismiss cases where the plaintiff shows no intent to return | In “Bill Tracker” also has list of bills and their status
- **Summary:** Monthly US legal roundup: a Seventh Circuit standing dismissal (plaintiffs must allege specific intent to return), conflicting experts in a California case, a class certification with individualized Unruh claims, and state anti-abusive-litigation laws (Georgia HB 1470, Utah SB 68) and California bills.
- **Key points:** Standing requires specific intent to return; Georgia and Utah anti-abuse statutes in effect; California AB 649 cure-and-report advancing
- **Page status:** ok

### 111. Should native app screen titles be headings?

- **URL:** https://tetralogical.com/blog/2026/07/22/should-the-screen-title-be-a-heading/
- **Source:** Graeme Coleman (TetraLogical) · 2026-07-22 · article
- **Tags:** Mobile apps, iOS, Android, Screen readers & braille
- **My comments:** Nice article on native accessibility | Claims iOS supports heading levels
- **Summary:** Argues native app screen titles should be exposed as headings (like an h1) under WCAG 1.3.1. Testing popular apps found iOS apps did this (SwiftUI's default) while most Android apps did not; Compose makes it easier than XML Views.
- **Key points:** Screen title ≈ h1; iOS gets it by default in SwiftUI; Most Android apps fail; Compose improves heading support
- **Page status:** ok

### 112. MagentaA11y

- **URL:** https://www.magentaa11y.com/
- **Source:** T-Mobile Accessibility Resource Center · tool
- **Tags:** Testing & auditing, Learning resources, Mobile apps
- **My comments:** Has native app accessibility criteria
- **Summary:** Open-source tool from T-Mobile that generates accessibility acceptance criteria and test instructions for web and native components, so product teams can build and verify accessible experiences.
- **Key points:** Generates acceptance criteria; Web and native components; Open source
- **Page status:** ok

### 113. Accessibility rant: reader mode

- **URL:** https://unattributed.cc/2026/07/16/accessibility-rant-reader-mode/
- **Source:** unattributed.cc · 2026-07-16 · article / opinion
- **Tags:** HTML & components, Cognitive, reading & mental health
- **My comments:** Reader mode in browsers - learned something new!
- **Page status:** blocked (Site disallows automated reading)

### 114. MagentaA11y: how to test images

- **URL:** https://www.magentaa11y.com/#/how-to-test-criteria/test-type/images
- **Source:** T-Mobile Accessibility Resource Center · tool / test criteria
- **Tags:** Testing & auditing, Images & alt text
- **My comments:** Has nice advice on how to handle alt text for charts
- **Summary:** MagentaA11y's testing criteria for images: acceptance criteria and step-by-step manual test instructions (keyboard, screen reader) for informative and decorative images.
- **Key points:** Acceptance criteria for images; Manual test steps; Part of MagentaA11y
- **Page status:** ok (Section of the MagentaA11y tool (entry 112); page needs JavaScript so summary is based on the tool's structure)

### 115. Web Content Accessibility Guidelines (WCAG) | Appt

- **URL:** https://appt.org/en/guidelines/wcag
- **Source:** Appt Foundation · 2024-04-11 · reference
- **Tags:** WCAG & standards, Mobile apps, Learning resources
- **My comments:** Each WCAG criteria has tips for how to implement on Android and iOS
- **Summary:** Appt's overview of WCAG 2.2 for apps: 4 principles, 13 guidelines, 87 success criteria across levels A/AA/AAA, how they apply to mobile apps, and links to EN 301 549 and Section 508.
- **Key points:** WCAG applies to apps as well as web; Aim for AA; Links to regional requirements; Free handbook and guides
- **Page status:** ok

### 116. HHS Accessibility Rule: Fast-Approaching Compliance Deadlines for Healthcare Providers

- **URL:** https://www.thedoctors.com/articles/hhs-accessibility-rule-fast-approaching-compliance-deadlines-for-hospitals-medical-and-dental-offices-and-healthcare-providers
- **Source:** Deborah de Quevedo (The Doctors Company) · 2024-05-09 · article / legal
- **Tags:** Law & policy
- **My comments:** AX medical regulation for disability - notice that some deadlines in 2027 and 2028
- **Summary:** Explains the May 2024 HHS Section 504 rule for healthcare providers receiving federal funds: accessible exam tables and scales, and WCAG 2.1 AA for websites, apps and kiosks, with deadlines in 2026-2028.
- **Key points:** Medical equipment deadline July 8, 2026; Web/app: May 11, 2027 (15+ employees); May 10, 2028 (fewer); WCAG 2.1 AA; Can't delegate responsibility to vendors
- **Page status:** ok

### 117. Accessibility Best Practices for Your Project

- **URL:** https://opensource.guide/accessibility-best-practices-for-your-project/
- **Source:** Open Source Guides (GitHub) · 2026-09-04 · guide
- **Tags:** Programs & process, Learning resources
- **My comments:** Open Source ax tips
- **Summary:** How to make open source projects accessible: partner with disabled people, publish an accessibility statement, accessible docs, keyboard-friendly native UI, automated plus manual testing, and accessibility in PR checklists and issue templates.
- **Key points:** Accessibility statement; Accessible documentation; Add to PR checklists and templates; Start with quick wins
- **Page status:** ok

### 118. WebAIM's WCAG 2 Checklist

- **URL:** https://webaim.org/standards/wcag/checklist
- **Source:** WebAIM · 2024-06-20 · checklist
- **Tags:** WCAG & standards, Testing & auditing, Learning resources
- **My comments:** Comprehensive checklist for WCAG criteria
- **Summary:** Simplified, practical checklist of WCAG 2.2 success criteria organized by principle, filterable by WCAG version and level, with links to W3C specs and WebAIM techniques.
- **Key points:** Plain-language criteria; Filter by 2.0/2.1/2.2 and A/AA/AAA; Links to techniques
- **Page status:** ok

### 119. ARIA anti-patterns and you

- **URL:** https://dbushell.com/2026/06/26/aria-anti-patterns-and-you/
- **Source:** David Bushell · 2026-06-26 · article
- **Tags:** ARIA
- **My comments:** Explains why should be careful when using APG, it purposely over-indexes on using ARIA
- **Page status:** blocked (Site disallows automated reading)

### 120. Disability dongle

- **URL:** https://sightlessscribbles.com/posts/disability-dongle/
- **Source:** Sightless Scribbles · article / opinion
- **Tags:** Lived experience & culture
- **My comments:** Shows how prototyping practices in Silicon Valley can lead to inaccessible products
- **Page status:** unreadable (Page redirects in a loop)

### 121. Guidance on Applying WCAG 2 to Non-Web ICT (WCAG2ICT)

- **URL:** https://www.w3.org/TR/wcag2ict-22/
- **Source:** W3C · 2025-12-11 · standard / W3C note
- **Tags:** WCAG & standards
- **My comments:** WCAG interpretation for non-web applications
- **Summary:** W3C note on applying WCAG 2.0/2.1/2.2 success criteria to non-web documents and software, replacing 'web page' with 'document' or 'software' and addressing closed-functionality systems.
- **Key points:** Most criteria apply to non-web ICT; Covers documents and software; Closed-functionality considerations
- **Page status:** ok

### 122. Smart Libraries: AI Use in South Korea

- **URL:** https://daisy.org/news-events/articles/smart-libraries-ai-use-in-south-korea/
- **Source:** Dave Gunn (DAISY Consortium) · 2026-08-20 · article
- **Tags:** AI, Screen readers & braille
- **My comments:** DAISY format | How making e-books accessible
- **Summary:** South Korea's National Library for the Disabled uses AI: an online EPUB verification system with a chatbot to help publishers produce born-accessible books, and generative AI trials to speed accessible-format production, with human oversight.
- **Key points:** Chatbot-guided accessibility verification; Gen AI for accessible formats; Human oversight essential
- **Page status:** ok

### 123. Should a Dialog Close When Clicked Outside?

- **URL:** https://adrianroselli.com/2026/08/should-a-dialog-close-when-clicked-outside.html
- **Source:** Adrian Roselli · 2026-08 · article
- **Tags:** HTML & components, Focus & keyboard
- **My comments:** Considerations for dialogs
- **Summary:** Depends on context: action-required dialogs (legal, warnings, logins) shouldn't close on outside click; informational ones can; sheets and drawers need judgment about data loss, visibility of the page underneath and recovery.
- **Key points:** Action-required: don't light-dismiss; Informational: light-dismiss OK; Consider data loss and recovery
- **Page status:** ok

### 124. Accessibility getting dropped in the process

- **URL:** https://buttondown.com/nic-steenhout/archive/accessibility-getting-dropped-in-the-process/
- **Source:** Nic Steenhout · 2026-08-05 · newsletter article
- **Tags:** Programs & process
- **My comments:** Describes case of AX considered in design but then wasn’t implemented with AX
- **Summary:** Why accessible designs become inaccessible products: workflow gaps rather than individual failures. Handoffs lack ownership, design reviews don't document implementation, and end-of-project audits come too late. Add checkpoints throughout.
- **Key points:** Accessibility lacks an owner at handoffs; Developers need feedback loops; Late audits are expensive; Checkpoints throughout development
- **Page status:** ok

### 125. Checklist - The A11Y Project

- **URL:** https://www.a11yproject.com/checklist/
- **Source:** The A11Y Project · checklist
- **Tags:** WCAG & standards, Testing & auditing, Learning resources
- **My comments:** WCAG checklist
- **Summary:** Beginner-friendly WCAG-based checklist in 18 categories (content, global code, keyboard, images, headings, forms, media and more), each item linked to its success criterion.
- **Key points:** Beginner friendly; Linked to WCAG criteria; Aim for AA
- **Page status:** ok

### 126. WCAG in Plain English

- **URL:** https://aaardvarkaccessibility.com/wcag-plain-english/
- **Source:** AAArdvark · reference
- **Tags:** WCAG & standards, Learning resources
- **My comments:** Goes into WCAG in detail
- **Summary:** Plain-language explanation of WCAG criteria, browsable by principle, guideline, theme, level, disability type and responsibility (code, content, design). Not a replacement for official WCAG.
- **Key points:** Plain-language criteria; Filter by disability and role; CC BY-SA
- **Page status:** ok

### 127. AI and Accessibility for Ecommerce: What the Tools Really Do and What they Don't

- **URL:** https://blog.usablenet.com/ai-and-accessibility-for-ecommerce-what-the-tools-really-do-and-what-they-dont
- **Source:** Jeff Adams (UsableNet) · 2026-08-05 · article
- **Tags:** AI, Testing & auditing
- **My comments:** Article on limitations of AI to build accessible sites
- **Summary:** AI can generate storefronts quickly but reproduces inaccessible patterns from its training data. Automated scans cover only about 25-30% of requirements, iterative AI changes can quietly regress accessibility, and expert oversight plus AT user testing remain essential.
- **Key points:** AI copies inaccessible patterns; Scans cover ~25-30%; Iterations can regress; Test with AT users
- **Page status:** ok

### 128. android-view-accessibility-techniques

- **URL:** https://github.com/cvs-health/android-view-accessibility-techniques
- **Source:** CVS Health · code samples (GitHub)
- **Tags:** Android, Learning resources
- **Summary:** Open-source Android sample app with 29 accessibility techniques for View-based UIs (basics, grouping and ordering, dynamic behavior, specific components), each documented, plus Espresso accessibility testing examples.
- **Key points:** 29 techniques with working code; Documentation per technique; Espresso test examples
- **Page status:** ok

### 129. android-compose-accessibility-techniques

- **URL:** https://github.com/cvs-health/android-compose-accessibility-techniques
- **Source:** CVS Health · code samples (GitHub)
- **Tags:** Android, Learning resources
- **Summary:** Open-source sample app with 30+ documented accessibility techniques for Jetpack Compose (informative content, interactive behaviors, specific components) in Kotlin.
- **Key points:** 30+ Compose techniques; Working code and docs; Apache 2.0
- **Page status:** ok

### 130. W3C WCAG GitHub Discussions

- **URL:** https://github.com/w3c/wcag/discussions
- **Source:** W3C · community forum
- **Tags:** WCAG & standards, Community & careers
- **My comments:** Good resource if unsure whether is a WCAG failure | Issues tab is also good for this
- **Summary:** The W3C WCAG repository's GitHub Discussions forum, where practitioners ask clarification questions about WCAG 2.2 and WCAG 3 success criteria (focus visibility, contrast, reflow, labels, pointer gestures) and get answers from the community and working group members.
- **Key points:** Q&A on interpreting success criteria; Covers WCAG 2.2 and 3; Many questions answered by WG members
- **Page status:** ok

### 131. TetraLogical

- **URL:** https://tetralogical.com/
- **Source:** TetraLogical · organization
- **Tags:** Community & careers
- **My comments:** Another major AX company
- **Summary:** UK accessibility consultancy offering audits, consultancy, training and strategy, with a team of screen reader and ARIA specialists, and a widely read blog and free newsletter series.
- **Key points:** Audits, training, strategy; Respected blog; Free foundations newsletter
- **Page status:** ok

### 132. How to Learn WCAG

- **URL:** https://www.camcoulter.com/presentations/how-to-learn-wcag/
- **Source:** Cam Coulter · 2026-09-03 · presentation notes
- **Tags:** WCAG & standards, Learning resources
- **My comments:** Cam Coulter’s presentation about WCAG, has a bunch of great resources in it
- **Summary:** Presentation notes on a structured way to learn WCAG: understand its structure (principles, guidelines, success criteria), learn HTML/CSS/JS and ARIA, practice testing with tools and screen readers, and join the community.
- **Key points:** Learn the structure first; Web fundamentals help; Practice testing; Join communities and conferences
- **Page status:** ok

### 134. Accessible Color Choices Are About So Much More Than Just Contrast

- **URL:** https://www.sheribyrnehaber.com/accessible-color-choices-are-about-so-much-more-than-just-contrast/
- **Source:** Sheri Byrne-Haber · 2026-09-02 · article
- **Tags:** Visual design & color, WCAG & standards
- **My comments:** In-depth article about limitations of WCAG criteria for color
- **Summary:** WCAG's colour criteria cover only a fraction of colour accessibility. Discusses colour vision deficiency, sensory sensitivity to saturated colours, migraine/photophobia triggers, seizure risk from static striped patterns, and the need for both light and dark themes.
- **Key points:** Contrast is only part of the story; Saturated colours can cause pain; Striped patterns can trigger seizures; Offer both light and dark modes
- **Page status:** ok

### 135. Understanding aria-details

- **URL:** https://www.maxdesign.com.au/articles/aria-details-explained.html
- **Source:** Russ Weakley (Max Design) · 2026-08-13 · article
- **Tags:** ARIA
- **My comments:** Aria-details property and how differs from aria-describedby
- **Summary:** aria-details points to extended, structured information without having screen readers read it all automatically, letting users choose to explore it. Contrasts it with aria-describedby, which is read as part of the element's description and suits short text.
- **Key points:** Signals extra info exists; For long or structured content; aria-describedby for short essentials; Multiple IDs allowed in ARIA 1.3
- **Page status:** ok

### 136. Patrick Lauke: how to interpret WCAG (presentation)

- **URL:** https://www.youtube.com/watch?v=ADIgU53Y2Rg
- **Source:** Patrick H. Lauke (YouTube) · video
- **Tags:** WCAG & standards
- **My comments:** Patrick Lauke’s presentation on how to interpret WCAG
- **Page status:** blocked (YouTube rate-limited automated reading)

### 165. Using AI as Your Accessibility Testing Partner

- **URL:** https://onsman.com/using-ai-as-your-accessibility-testing-partner/
- **Source:** Ricky Onsman · 2026-09-13 · article
- **Tags:** AI, Testing & auditing
- **My comments:** I really like this sentence "The highest value lies in helping expert auditors think more broadly, cover more disability perspectives, explore edge cases, improve consistency, and reduce the administrative burden of auditing."
- **Summary:** How accessibility auditors can use AI as a supporting 'junior partner' while keeping testing evidence-based. AI can review large amounts of content quickly, but its output needs expert review, auditors stay accountable for conclusions, and usability testing with disabled people can't be reliably simulated.
- **Key points:** AI complements, not replaces, professional judgment; Audits carry an evidentiary burden, so findings must be evidence-based; Biggest value: broader thinking, more disability perspectives, edge cases, consistency, less admin; Testing with disabled people remains essential
- **Page status:** ok

### 166. Evaluating a Success Criterion

- **URL:** https://adrianroselli.com/2026/09/evaluating-a-success-criterion.html
- **Source:** Adrian Roselli · 2026-09 · article
- **Tags:** WCAG & standards, Testing & auditing
- **My comments:** It gives really good tips on how to evaluate a WCAG criterion.
- **Page status:** unreadable (Site rate-limited automated reading on 2026-09-24; summary to be added later)

### 167. Exclusion by Design - Michele A. Williams

- **URL:** https://www.youtube.com/watch?v=rTlzxDLkg8I
- **Source:** Michele A. Williams (Accessibility Talks) · video / talk
- **Tags:** Lived experience & culture
- **My comments:** "If exclusion is the norm, access will always feel exceptional"
- **Page status:** blocked (YouTube blocked automated reading; summary to be added later)

## Mobile accessibility course links

### 137. Assistive technologies for using apps

- **URL:** https://appt.org/en/articles/assistive-technologies
- **Source:** Appt Foundation · 2023-11-01 · guide
- **Tags:** Mobile apps, Screen readers & braille, Voice & switch control
- **My comments:** Appt.org assistive technologies
- **Summary:** Overview of the main assistive technologies used with apps (screen readers, voice control, switch control, keyboard access) with links to Android and iOS documentation for each.
- **Key points:** Four main AT categories; TalkBack and VoiceOver; Platform-specific links
- **Page status:** ok

### 138. Accessibility Stats

- **URL:** https://appt.org/en/stats
- **Source:** Appt Foundation (research by Q42) · 2025-12-04 · statistics
- **Tags:** Statistics, Mobile apps
- **My comments:** Appt.org assistive stats
- **Summary:** Anonymous data from millions of Dutch iOS and Android users: over half have at least one accessibility setting on (about 50% of iOS users, nearly 75% of Android). Visual settings like dark mode and font size are most common.
- **Key points:** 50%+ of users use accessibility settings; Font size and dark mode most common; Captions used widely
- **Page status:** ok

### 139. Disability and health (fact sheet)

- **URL:** https://www.who.int/news-room/fact-sheets/detail/disability-and-health
- **Source:** World Health Organization · 2023-03-07 · statistics / fact sheet
- **Tags:** Statistics
- **My comments:** WHO ax stats
- **Summary:** An estimated 1.3 billion people (about 16%, 1 in 6) have significant disability. They face health inequities, earlier death and higher risk of chronic conditions due to stigma, poverty and inaccessible health systems.
- **Key points:** 1.3 billion people, ~1 in 6; Twice the risk of depression, diabetes and more; Health inequities from systemic barriers
- **Page status:** ok

### 140. Appt.org: A guide for making apps accessible

- **URL:** https://appt.org/en
- **Source:** Appt Foundation · resource hub
- **Tags:** Mobile apps, Learning resources
- **My comments:** Appt.org guide for making ax apps
- **Summary:** Nonprofit knowledge base for accessible mobile apps: usage statistics, code documentation for iOS, Android, React Native, Flutter and Xamarin, WCAG guidance for apps, articles and a free handbook.
- **Key points:** Code docs across 5 frameworks; Usage statistics; Free handbook
- **Page status:** ok

### 141. Android Developers

- **URL:** https://developer.android.com/
- **Source:** Google · documentation hub
- **Tags:** Android, Learning resources
- **My comments:** Android developer docs
- **Summary:** Google's official Android developer site, including the accessibility guides for making apps work with TalkBack, Switch Access, Voice Access and large text in both Views and Jetpack Compose.
- **Key points:** Official Android docs; Accessibility section for Views and Compose
- **Page status:** ok (Summary written from general knowledge of the site)

### 142. Apple Developer

- **URL:** https://developer.apple.com/
- **Source:** Apple · documentation hub
- **Tags:** iOS, Learning resources
- **My comments:** Apple developer docs
- **Summary:** Apple's official developer site, including Human Interface Guidelines and accessibility documentation for VoiceOver, Dynamic Type, Voice Control and Switch Control in SwiftUI and UIKit.
- **Key points:** Official Apple docs; HIG accessibility guidance
- **Page status:** ok (Summary written from general knowledge of the site)

### 143. Native versus cross-platform frameworks to develop accessible apps

- **URL:** https://appt.org/en/articles/native-versus-cross-frameworks-accessible-apps
- **Source:** Appt Foundation · 2025-01-30 · article
- **Tags:** Mobile apps
- **My comments:** Appt.org native vs cross platform frameworks
- **Summary:** Compares accessibility API support in native Android/iOS vs Flutter, React Native and Xamarin: native and Flutter have full support, React Native about 90% (e.g., no focus order control), Xamarin 50-80%.
- **Key points:** Native: full support; Flutter: full; React Native: ~90%; Xamarin: 50-80%
- **Page status:** ok

### 144. Key Differences Between Native, Web, and Hybrid Apps

- **URL:** https://abra.ai/blog/wat-are-the-differences-between-apps
- **Source:** Abra · 2024-09-08 · article
- **Tags:** Mobile apps
- **My comments:** Abra differences between native, web, and hybrid apps
- **Summary:** Explains native, cross-platform and hybrid (webview) apps and how framework choice affects accessibility capability and compliance; recommends testing accessibility early.
- **Key points:** Native: full device access; Cross-platform: possible accessibility gaps; Hybrid: webviews + native; Framework choice affects accessibility
- **Page status:** ok

### 145. Disability in the EU: facts and figures

- **URL:** https://www.consilium.europa.eu/en/infographics/disability-eu-facts-figures/
- **Source:** Council of the European Union · 2024-10-14 · statistics / infographic
- **Tags:** Statistics
- **My comments:** EU disability figures
- **Summary:** About 90 million Europeans (24% of adults) have a disability, rising steeply with age (47% over 65). Disabled people face higher discrimination, unemployment and poverty risk.
- **Key points:** 1 in 4 EU adults; 47% of those 65+; 29% at risk of poverty/social exclusion
- **Page status:** ok

### 146. Appt Accessibility Handbook

- **URL:** https://appt.org/en/handbook
- **Source:** Jan Jaap de Groot and Paul van Workum (Appt) · 2024-05-16 · book / handbook
- **Tags:** Mobile apps, Learning resources
- **My comments:** Appt handbook
- **Summary:** Free app accessibility handbook (2nd edition, English and Dutch) covering the basics in plain language and updated for WCAG 2.2; PDF download or printed copy.
- **Key points:** Free PDF; Updated for WCAG 2.2; Plain language
- **Page status:** ok

### 147. Disabilities when using apps

- **URL:** https://appt.org/en/articles/disabilities/
- **Source:** Appt Foundation · 2024-04-11 · article / statistics
- **Tags:** Statistics, Mobile apps
- **My comments:** Appt disabilities by cohort
- **Summary:** Overview of six groups of disabilities that affect app use (cognitive, hearing, mobility, speech, visual, and age-related), with Dutch prevalence figures, and a reminder that disabilities can be permanent, temporary or situational.
- **Key points:** Six disability groups; ~19.5% of Dutch people have age-related impairments; ~14.7% low literacy; Permanent, temporary, situational
- **Page status:** ok

### 148. VoiceOver: screen reader for iOS

- **URL:** https://appt.org/en/docs/ios/features/voiceover
- **Source:** Appt Foundation · 2024-04-11 · documentation
- **Tags:** iOS, Screen readers & braille
- **My comments:** Appt VoiceOver guidance
- **Summary:** How to turn on and use VoiceOver on iOS: activation options, core gestures (swipe to move, double-tap to activate), multi-finger gestures, the rotor, and settings like speech rate.
- **Key points:** Enable via Settings, Siri or shortcut; Swipe left/right, double-tap; Rotor via two-finger rotate
- **Page status:** ok

### 149. TalkBack: screen reader for Android

- **URL:** https://appt.org/en/docs/android/features/talkback
- **Source:** Appt Foundation · 2024-04-11 · documentation
- **Tags:** Android, Screen readers & braille
- **My comments:** Appt Talkback guidance
- **Summary:** How to enable and use TalkBack on Android: single-finger swipes to move, two-finger scroll, multi-finger gestures for menus and editing (since 9.1), and settings for speech rate, pitch and verbosity.
- **Key points:** Volume-key shortcut; Multi-finger gestures since 9.1; Practice app available
- **Page status:** ok

### 150. Voice control

- **URL:** https://appt.org/en/stats/voice-control
- **Source:** Appt Foundation · 2022-12-12 · documentation / statistics
- **Tags:** Voice & switch control, Mobile apps
- **My comments:** Appt Voice Control guidance (Android and iOS)
- **Summary:** Explains voice control on mobile (Voice Access on Android, Voice Control on iOS), where users speak labels or numbers shown on screen to act, and links to platform guides. iOS usage data isn't available.
- **Key points:** Speak labels, numbers or grid positions; Voice Access (Android), Voice Control (iOS); Visible labels must match accessible names
- **Page status:** ok

### 151. Voice Access for Android

- **URL:** https://appt.org/en/docs/android/features/voice-access
- **Source:** Appt Foundation · 2024-04-18 · documentation
- **Tags:** Android, Voice & switch control
- **My comments:** Appt Voice Access guidance
- **Summary:** Setup and command reference for Android Voice Access: enabling it, numbered labels and grid overlays, and voice commands for navigation, gestures, text editing and settings.
- **Key points:** Android 5.0+; Numbers and grid overlay; Extensive text-editing commands
- **Page status:** ok

### 152. Switch control

- **URL:** https://appt.org/en/stats/switch-control
- **Source:** Appt Foundation · 2022-12-12 · documentation / statistics
- **Tags:** Voice & switch control, Mobile apps
- **My comments:** Appt Switch Control guidance
- **Summary:** Explains switch control for people with motor disabilities: internal switches (screen, camera) and external switches (physical buttons), with links to iOS Switch Control and Android Switch Access guides.
- **Key points:** Internal vs external switches; iOS Switch Control / Android Switch Access
- **Page status:** ok

### 153. Switch Access for Android

- **URL:** https://appt.org/en/docs/android/features/switch-access
- **Source:** Appt Foundation · 2024-04-11 · documentation
- **Tags:** Android, Voice & switch control
- **My comments:** Appt Switch Access guidance
- **Summary:** How to set up Android Switch Access: connecting switches, keyboards or device buttons, choosing a scanning method (auto, step, group), and using its menus.
- **Key points:** Three switch types; Auto, step and group scanning; Actions menu for multi-action items
- **Page status:** ok

### 154. Font size

- **URL:** https://appt.org/en/stats/font-size
- **Source:** Appt Foundation · 2023-01-27 · statistics
- **Tags:** Visual design & color, Mobile apps, Statistics
- **My comments:** Appt font size
- **Summary:** Over one fifth of Dutch iOS and Android users enlarge text (3+ million people); Android default font sizes vary by manufacturer. Links to code samples for supporting scalable text.
- **Key points:** 20%+ of users enlarge text; Android defaults vary by device; Code samples for scalable fonts
- **Page status:** ok

### 155. Keyboard Access for iOS

- **URL:** https://appt.org/en/docs/ios/features/keyboard-access
- **Source:** Appt Foundation · 2024-02-20 · documentation
- **Tags:** iOS, Focus & keyboard
- **My comments:** App for iOS external keyboard
- **Summary:** How to connect an external keyboard to iOS and use Full Keyboard Access: Tab, arrow keys, Space to activate, and customizable commands, with shortcut tables.
- **Key points:** Bluetooth or wired; Tab / arrows / Space; Customizable commands in Settings
- **Page status:** ok

### 156. Keyboard access

- **URL:** https://appt.org/en/stats/keyboard-access
- **Source:** Appt Foundation · 2022-09-16 · documentation / statistics
- **Tags:** Focus & keyboard, Mobile apps
- **My comments:** Appt external keyboard guidance
- **Summary:** Explains why keyboard access matters on mobile (motor disabilities, blind users, tablet keyboard users) and links to Android and iOS guides.
- **Key points:** Easier than touch for some motor disabilities; Blind users type faster; Common with tablets
- **Page status:** ok

### 157. Mobile App Accessibility under EN 301 549 v4.1.0

- **URL:** https://abra.ai/blog/mobile-app-accessibility-en-301-549-v4-1-0
- **Source:** Abra · 2026-01-21 · article / standards
- **Tags:** WCAG & standards, Law & policy, Mobile apps
- **My comments:** Mobile accessibility for EN 301 549
- **Summary:** EN 301 549 v4.1.0 aligns the EU standard with WCAG 2.2: web views in apps are treated as non-web software (Clause 11), four new criteria (focus, dragging, target size, authentication) are added, and some previously void criteria now apply to apps.
- **Key points:** Web views = non-web software; New WCAG 2.2 criteria; Clearer layer responsibility model; Testing approaches will need updates
- **Page status:** ok

### 158. All ACT Rules

- **URL:** https://www.w3.org/WAI/standards-guidelines/act/rules/
- **Source:** W3C WAI · standards reference
- **Tags:** WCAG & standards, Testing & auditing
- **My comments:** ACT rules
- **Summary:** Catalog of Accessibility Conformance Testing (ACT) rules for WCAG 2.2 and ARIA, which standardize how to test specific requirements; filterable by requirement, status and implementation (manual, automated, linters).
- **Key points:** Informative test rules; Proposed/approved status; Implementation reports for tools
- **Page status:** ok

### 159. Guidance on Applying WCAG 2.2 to Mobile Applications (WCAG2Mobile)

- **URL:** https://www.w3.org/TR/wcag2mobile-22/
- **Source:** W3C Mobile Accessibility Task Force · 2025-05-06 · standard / W3C note
- **Tags:** WCAG & standards, Mobile apps
- **My comments:** WCAG mobile ax task force
- **Summary:** W3C draft note on applying WCAG 2.2 A and AA success criteria to native, mobile web and hybrid apps, replacing web terms (e.g., 'web page') with mobile concepts like screens and views. Informative, not normative.
- **Key points:** Covers all WCAG 2.2 A/AA criteria for mobile; Maps web terminology to screens/views; Informative guidance only; Excludes hardware, AAA and wearables
- **Page status:** ok (Same page as entry 46)

### 160. Accessibility documentation | Appt

- **URL:** https://appt.org/en/docs
- **Source:** Appt Foundation · 2026-01-29 · documentation hub
- **Tags:** Mobile apps, Learning resources
- **My comments:** Appt ax documentation
- **Summary:** Appt's code documentation for eight platforms (Android Views, Jetpack Compose, iOS UIKit, SwiftUI, Flutter, React Native, .NET MAUI, Xamarin), starting with an Accessible App Starter Guide.
- **Key points:** 8 platforms; Code samples; Starter guide for beginners
- **Page status:** ok

### 161. Accessibility Annotation Kit for iOS (Figma)

- **URL:** https://www.figma.com/es-la/comunidad/file/1331647574396908226/accessibility-annotation-kit-for-ios
- **Source:** CVS Health · design tool (Figma file)
- **Tags:** iOS, Visual design & color
- **My comments:** CVS iOS annotations
- **Page status:** blocked (Figma disallows automated reading)

### 162. Include Accessibility Annotations (Figma plugin)

- **URL:** https://www.figma.com/es-la/comunidad/plugin/1208180794570801545/include-accessibility-annotations
- **Source:** eBay (Include) · design tool (Figma plugin)
- **Tags:** Mobile apps, Visual design & color
- **My comments:** Include annotations (iOS and Android)
- **Page status:** blocked (Figma disallows automated reading)

### 163. Automated accessibility testing of Android and iOS apps

- **URL:** https://appt.org/en/articles/automated-accessibility-testing-android-ios-apps
- **Source:** Appt Foundation · 2025-04-07 · article
- **Tags:** Mobile apps, Testing & auditing
- **My comments:** Appt automated testing on iOS and Android
- **Summary:** Overview of automated accessibility testing tools for mobile: platform tools (Espresso/UI Automator, XCTest), cross-platform (Appium), free libraries (Accessibility Test Framework for Android, GTXiLib) and paid tools (Abra, axe DevTools Mobile).
- **Key points:** Detects contrast, labels, semantics; Free and paid options; Automation doesn't catch everything
- **Page status:** ok

### 164. Appt.org: A guide for making apps accessible

- **URL:** https://appt.org/en
- **Source:** Appt Foundation · resource hub
- **Tags:** Mobile apps, Learning resources
- **My comments:** Appt knowledge base
- **Summary:** Nonprofit knowledge base for accessible mobile apps: usage statistics, code documentation for iOS, Android, React Native, Flutter and Xamarin, WCAG guidance for apps, articles and a free handbook.
- **Key points:** Code docs across 5 frameworks; Usage statistics; Free handbook
- **Page status:** ok (Same page as entry 140)
