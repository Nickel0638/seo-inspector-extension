# SEO Inspector Extension

## Installation
1. Get an API key at [Google Cloud Console](https://console.cloud.google.com)
2. Enable the PageSpeed Insights API
3. In `popup.js`, replace `YOUR_API_KEY_HERE` with your actual key
4. Load the extension in Chrome via `chrome://extensions/` → Load unpacked

## Features
- Meta tags analysis (Title, Description, Canonical, Robots)
- H1-H6 headings list with visual highlighting on the page
- Open Graph & Twitter Card tags
- Images audit (total count & missing alt attributes)
- Core Web Vitals via PageSpeed Insights API (LCP, TBT, CLS, FCP, Speed Index, TTI)
- Overall SEO Score (0-100)
- Mobile / Desktop switching for Vitals analysis
