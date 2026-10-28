
# Portfolio assets

The portfolio's `index.html` references images, videos, and the resume PDF in
`media/`. These files were extracted from embedded base64 URLs without changing
their contents. Filenames are SHA-256 content hashes with media extensions.

Keep referenced media files alongside the page when deploying to GitHub Pages.
Use normal asset URLs for new media rather than embedding large base64 strings in
HTML. HTML and deployment assets are stored as ordinary Git files, not Git LFS
pointers.
