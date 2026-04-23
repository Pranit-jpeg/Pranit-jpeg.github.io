# Publishing notes

## TODO: design the og:image

The Open Graph / Twitter Card meta tags on every page reference:

    https://pranit-jpeg.github.io/assets/og-image.png

That file does not exist yet. Until it does, link unfurls on
LinkedIn, Twitter/X, Slack, iMessage, etc. will fall back to a
card with no image — which is fine, not broken.

When you're ready:

1. Design a **1200 x 630 px** PNG. Keep important content inside
   a 1200 x 600 safe zone (LinkedIn crops ~15 px off the top/bottom).
2. Save as `assets/og-image.png`.
3. Commit and push. No HTML changes needed — the meta tags
   already point at that path.

Design suggestion: something that matches the site's
Fraunces + IBM Plex + cream/ink palette. Name, one-line framing,
restrained — the card is a first impression, not a billboard.

Preview the unfurl with:

- LinkedIn: https://www.linkedin.com/post-inspector/
- Twitter/X: https://cards-dev.twitter.com/validator (or just tweet a draft)
- Generic: https://www.opengraph.xyz/
