IRUBAS PHARMA — MULTI-PAGE CLOUDFLARE PAGES PACKAGE

DEPLOYMENT
1. Extract this ZIP.
2. Upload the CONTENTS of this folder to Cloudflare Pages (Direct Upload).
3. Keep index.html at the root of the uploaded folder.
4. Do not upload the ZIP itself as the website root.

PAGES
- index.html: Home
- learn-gmp.html: Learn GMP and guide pages
- lead-quality.html: Lead Quality
- regulatory-bodies.html: Regulatory Bodies directory
- regulators/*.html: Individual regulator reference pages
- resources.html: Resources and events
- blog.html: Blog

NOTES
- Navigation uses separate HTML pages and relative links.
- Shared visual styles and scripts are embedded in each page for a simple static deployment.
- Regulatory reference pages use expandable dropdown groups and link to official sources.
- The regulator directory is a structured starter implementation. It is not a verified exact copy of every dropdown and link from https://sp-pharma.github.io/pharma-website/ because that site's source package was not supplied in this conversation.
- Sign-in and event-interest forms retain the current prototype behavior; backend storage/authentication is not included.
