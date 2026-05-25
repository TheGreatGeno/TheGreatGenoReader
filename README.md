# TheGreatGenoReader

Things to do:
1. Proxy/Feed Issues — Identify and remove dead feeds (Politico, AP News, etc. blocked by Cloudflare/CORS). Clean up console spam.
2. Local Backend Server — Replace proxies with a Node.js/Python server running on localhost to bypass CORS entirely. Eliminates feed failures but requires terminal process running.
3. Favicon/Logo Design — Current book icon in header is too small to read clearly. Redesign or enlarge.
4. Left Sidebar with Source Filtering — Add collapsible sidebar listing all visible feeds. Click a feed name to filter the main view to just that source. Click again to unfold. Includes hamburger menu toggle for mobile (auto-closed on screens under 768px, auto-open on desktop).
   NOTE:  This has been replaced by filtering withing the 'Manage Feeds' button.
5. GitHub Hosting with Backend — Host the reader on Vercel or Netlify with serverless functions to fetch feeds server-side instead of proxies.
