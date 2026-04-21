# Case Study — Radio-Canada × experimenting.ai

Standalone preview page for the Radio-Canada AI adoption case study, deployable on Vercel as a static site.

**Purpose:** Allow Radio-Canada to review and approve the case study page via a shareable URL before it gets integrated into the main [experimenting.ai](https://experimenting.ai) website.

## Deploy

Push to GitHub, then import the repo into [Vercel](https://vercel.com) as a static site — no build step required.

## Structure

```
index.html      ← The case study page (self-contained HTML/CSS/JS)
images/         ← Photo assets (to be added)
vercel.json     ← Static deployment config, caching & security headers
```

## Notes

- The page is set to `noindex, nofollow` — it won't appear in search engines.
- OG image points to `images/og-cover.jpg` — replace the placeholder once the image is ready.
- Fonts (Inter, JetBrains Mono) are loaded via Google Fonts CDN.
- No build tools, no dependencies, no framework — just static HTML.
