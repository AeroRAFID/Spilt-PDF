PDF Splitter PWA

HOW TO INSTALL
1. Upload the contents of this folder to an HTTPS static host (for example GitHub Pages, Netlify, or Cloudflare Pages).
2. Open the hosted URL in Chrome on Android or desktop.
3. Choose Install app / Add to Home screen from the browser menu.

IMPORTANT
- A PWA must be served from HTTPS (or localhost) to be installable. Opening index.html directly from a file manager is not enough.
- Connect to the internet on the first visit so the PDF library can be cached. After that, the app shell and library are available offline.
- Very large PDFs may need several GB of RAM. Splitting is balanced by page count, not exact byte size.
- Files are processed locally in the browser; they are not uploaded by this app.
