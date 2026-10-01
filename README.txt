Movy Wrapper PWA

Purpose:
Reserves the iPhone safe-area above an embedded Movy page.

Important:
A PWA must be served from HTTPS (or localhost) to install properly.
Opening index.html directly from Files is not enough.

If Movy sends X-Frame-Options or CSP frame-ancestors restrictions,
the iframe will be blocked and this approach cannot work.

Files:
- index.html
- manifest.webmanifest
- sw.js
