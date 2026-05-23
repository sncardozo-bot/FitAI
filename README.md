
# FitAI - Free iPhone App Setup

## Files
- index.html
- manifest.json
- sw.js
- cloudflare-worker.js

## Free Hosting
Use GitHub Pages.

## iPhone Installation
1. Upload files to GitHub Pages
2. Open in Safari
3. Share → Add to Home Screen

## AI Setup (Free Backend)
1. Create free Cloudflare Workers account
2. Paste cloudflare-worker.js
3. Add secret:
   ANTHROPIC_API_KEY

4. Deploy Worker
5. Replace:
   https://YOUR-CLOUDFLARE-WORKER.workers.dev/chat

inside index.html with your Worker URL.

## Result
- Fullscreen Home Screen app
- Offline support
- Claude AI support
- Persistent tracking
- Native-like experience on iPhone
