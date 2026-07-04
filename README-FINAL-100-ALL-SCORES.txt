FINAL 100 ALL SCORES STABLE UPLOAD

This package keeps the final Cheyenne Cleveland website setup and makes two stability fixes:

1. robots.txt has been simplified to the most universally accepted format:
   User-agent: *
   Disallow:
   Sitemap: https://cheyenneclevelandbooks.github.io/sitemap.xml

2. The optional content-visibility CSS rule has been removed so Lighthouse/DevTools filmstrip capture is less likely to show delayed or blank screenshots.

Upload the extracted files to the root of the cheyenneclevelandbooks.github.io repository. Do not upload the ZIP itself.

Commit message:
Final 100 all scores stability update
