# Website Performance Optimization TODO

## Steps from Approved Plan

- [x] Step 1: Minify css/style.css (remove comments, whitespace, unused rules) and create css/style.min.css. Update all HTML files to link to style.min.css instead of style.css.
- [ ] Step 2: Optimize HTML <head> across all pages (add preconnect for external domains, update Google Fonts with &display=swap, preload critical CSS like bootstrap.css and style.min.css, move non-critical JS to <body> end with defer/async).
- [ ] Step 3: Minify unminified JS files (e.g., js/main.js, js/jquery.easing.1.3.js) and create minified versions (main.min.js, etc.). Update HTML to use minified/deferred JS.
- [ ] Step 4: Optimize images – Convert key images (e.g., logo.png, co_working_space_*.jpg) to WebP format, add loading="lazy" to non-critical <img>, add width/height attributes, use <picture> for WebP fallback. Update all HTML img tags accordingly.
- [ ] Step 5: Remove unused code (e.g., commented sections, unused modals/carousels in specific pages like locations.html).
- [ ] Step 6: Testing – Run local server, use browser_action to verify no errors, check PageSpeed Insights improvements.
- [ ] Step 7: Final verification and cleanup (e.g., remove old files if approved).

Progress: Starting with Step 1.
