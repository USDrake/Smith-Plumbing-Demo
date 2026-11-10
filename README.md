# Smith Plumbing — Complete Website

Complete seven-page static demo website with local images, fonts, styles, scripts, and embedded assets. Old ChatGPT Sites home links have been made portable in this export.

## Upload to GitHub
1. Extract this ZIP.
2. Upload all extracted files and folders to the repository root. Upload the contents, not the ZIP itself.
3. Keep index.html at the root, alongside assets/, fonts/, and the other HTML, CSS, and JavaScript files.
4. Commit the files.

## Cloudflare Pages
Connect the repository to Cloudflare Pages. Select no framework, leave the build command blank, and use the repository root as the output directory (enter . if required). No npm install or build step is needed.

## Included pages
- Home: index.html
- About: about.html
- Contact: contact.html
- Services: services.html
- Plumbing repairs: plumbing-repairs.html
- Drain cleaning: drain-cleaning.html
- Water heaters: water-heaters.html

These are the pages present in the current Smith Plumbing Sites project. No separate septic page, emergency page, or chatbot is included in this source.

## Demo behavior
This is a fictional-business demo. Existing sample contact details and disclaimers are preserved. Forms are not connected to a message-delivery backend; the Services request form opens a text-message draft. Configure a real delivery service and contact details before adapting the demo for a real business.

## Hosting and preview
Root-relative links require hosting at a domain root, such as Cloudflare Pages, a custom domain, or root-level GitHub Pages. A GitHub Pages project URL under /repository-name/ requires adapting those paths first.

For local preview, run a static server in this folder, for example python3 -m http.server 8000, then visit http://localhost:8000. Opening individual HTML files directly may not resolve root-relative links.

No ChatGPT login or hosting service is required. Some images are embedded directly in the HTML and are already included.

## Cloudflare Pages domain and SEO

Primary site: https://smith-plumbing-demo.pages.dev/

All 7 HTML pages include canonical and Open Graph URL tags for the Cloudflare domain. The root-level `sitemap.xml` lists every HTML page, and `robots.txt` points crawlers to that sitemap. Upload all files at the root of the GitHub repository/Cloudflare Pages static output, preserving folders.
