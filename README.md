# BAPS KDC Mahant Ministry Letter

Minimal static site for the BAPS KDC event. The current deployment smoke test displays **Hello World**.

## Architecture

QR code → Vercel website → this public GitHub repository

Vercel should be connected to this repository main branch. Each push to main can trigger an automatic deployment. The GitHub and Vercel accounts may be different; the repository is public, so Vercel can import it from its URL.

## Local preview

Open index.html in a browser, or serve the repository with any static web server.

## Static QR code

After deployment, generate a static QR code for the confirmed Vercel URL. A static QR code encodes the URL directly and remains usable as long as that URL remains available; changing the page content does not require changing the QR code.
