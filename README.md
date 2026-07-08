# embed

Put nostr on **any website** — a blog, a docs page, a shop. No iframe, no SDK,
no build step: two copy-paste tags.

**Generator:** https://nostr-client.github.io/embed/

```html
<script type="module" src="https://nostr-client.github.io/note/note.js"></script>
<nostr-note event-id="<hex>"></nostr-note>
```

Works for a single note, a profile card, one author's feed, a hashtag feed, or
the global firehose — the generator page builds the snippet and previews it
live. Because these are plain web components on your own page (not iframes),
they inherit your fonts and can be themed with
[`--nc-*` tokens](https://github.com/nostr-client/theme).

Part of [nostr-client](https://github.com/nostr-client). AGPL-3.0-or-later.
