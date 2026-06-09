# CrawlScope — GEO & AI Crawler Audit Dashboard

**CrawlScope** is a high-fidelity Generative Engine Optimization (GEO) and technical SEO auditing dashboard. It helps developers and SEO specialists analyze how search engine bots and AI web crawlers (such as Googlebot, GPTBot, ClaudeBot, and Perplexity) read, understand, and cite websites in generative search engines.

Created by **Abu Sufyan** — Next.js & Technical SEO Developer.

---

## Key Features

- **GEO Score & Health Analytics**: Evaluates web performance across key categories including GEO citations, crawl coverage, index discovery velocity, and JSON-LD schema markup gaps.
- **Interactive Crawl Signal Map**: A real-time visual grid listing crawled URLs. Includes path-based searching and filter buttons to isolate URLs by their health class (`OK`, `Warn`, `Fail`).
- **URL & Structural Vector Diagnostics**: Click on any URL or system vector to open a detailed inspection drawer. The drawer offers recommendations and actionable, ready-to-copy code configurations.
- **Built-in Configuration Generators**: Contains copyable code templates for:
  - AI crawler-friendly `robots.txt` configurations.
  - LLM context documentation (`llms.txt`).
  - Next.js 15 App Router dynamic sitemaps (`sitemap.ts`) and canonical tag management.
  - Next.js static generation optimization templates.
- **Interactive Scan Simulator**: Type any domain to trigger a simulated edge crawl. The dashboard features an animated CLI-style terminal log that demonstrates dns resolution, robots.txt parsing, and crawling routines.
- **Export & Reporting**:
  - **Export JSON**: Downloads the full audit report as a structured JSON payload.
  - **Print Report**: Optimized print CSS styles that transform the interactive UI into a clean, professional PDF audit report.

---

## Technology Stack

- **Structure & Layout**: Semantic HTML5, CSS Flexbox & CSS Grid.
- **Styling**: Modern dark-mode palette utilizing CSS variables, rich animations, glassmorphic filters, and typography powered by Google Fonts (Syne and IBM Plex Mono).
- **Interactivity**: Pure, lightweight Vanilla JavaScript for data generation, state management, search filters, drawer controls, and file-download generation. No heavy dependencies or third-party libraries required.

---

## 💻 Getting Started

Since CrawlScope is built entirely on client-side vanilla web technologies, launching it is simple:

1. **Locate the file**: Open the directory where `index.html` is stored.
2. **Open in Browser**: Double-click `index.html` or drag it into any modern web browser (Chrome, Firefox, Safari, Edge).
3. **Usage**:
   - Enter a domain (e.g., `wtkpro.site` or `severancecalculator.xyz`) in the input box and click **Scan Site**.
   - Click on individual URLs in the **Crawl signal map** to inspect HTTP status, health scores, and recommended actions.
   - Click on items in the **Structural vectors** list to fetch ready-to-use configuration patterns.
   - Try changing CLI parameters in the terminal (like clicking on `--depth` or `--geo-signals`) and click **Re-run Audit** to see live crawling simulations.
   - Click **Export JSON** to save the crawled state locally, or click **Print Report** to generate a PDF.

---

## 👤 Developer Profile

**Abu Sufyan** — *Next.js Developer · Technical SEO · Developer Tooling*
- 🌐 Portfolio: [abusufyan.xyz](https://abusufyan.xyz)
- 🛠️ Platform: [WebToolkit Pro](https://wtkpro.site)
- 💼 Professional: [Hire on Upwork](https://www.upwork.com)
