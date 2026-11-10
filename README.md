pose-data-harvester

A small browser-based prototype that locates downloadable CSV/JSON files referenced from an HTML document and extracts candidate pose/joint data from text and image captions into JSON/CSV. Paste an article's HTML into the interface or open a same-origin URL in the browser and paste the fetched HTML. This repository contains only client-side code and heuristics for identification and reporting; implement a backend crawler separately when ready.

Usage:
- Open index.html in a browser.
- Paste the target page HTML or a minimal fetched response.
- Click 'Analyze'.

Limitations: No network crawling (safe, offline), heuristics only, limited image text extraction (uses captions/alt only).