# TheGreatGenoReader

App updates:
5/25/26 - Added ability to filter in the 'Feed' section.  Filter is persistent and is displayed in status bar.  A Clear All Filter button is present in Feed when filtering is in place.  Updated "Done" button to "Read" button and added in the Bookmarks section.

To-Do for Later:

1. Proxy/Feed Issues — Identify and remove dead feeds (Politico, AP News, etc. blocked by Cloudflare/CORS). Clean up console spam.
2. Local Backend Server — Replace proxies with a Node.js/Python server running on localhost to bypass CORS entirely. Eliminates feed failures but requires terminal process running.
3. Favicon/Logo Design — Current book icon in header is too small to read clearly. Redesign or enlarge.
4. GitHub Hosting with Backend — Host the reader on Vercel or Netlify with serverless functions to fetch feeds server-side instead of proxies.
5. Feed Filtering in Modal — ✓ DONE. Filter by multiple sources directly in Feeds modal instead of side panel.
6. User Settings Menu — Add settings modal for preferences like articles per feed, auto-mark as history on click, articles per page, default collapse state on load.
7. Refactor Button Labels — Centralize button text (Done, Bookmark, Remove, etc.) as constants at the top of the file instead of hardcoded strings throughout.
8. Refactor View State Logic — Change isBmark true/false pattern to explicit viewType string ('feed', 'bookmarks', 'history') for cleaner, more maintainable code.
