Komma-Labor Mathe 6 (chapter II, decimals)
===========================================

What is in this folder
  index.html          the whole app (HTML, CSS and JavaScript in one file)
  fonts/              six font files and their licence text
  README.txt          this file

Putting it on your website
  1. Upload the folder "komma-labor" as it is (index.html and fonts/ must stay together).
  2. Open https://your-domain/komma-labor/ in a browser.
  You can rename the folder. Nothing needs a database, a build step or server-side code;
  any static web space works.

Good to know
  - The page loads nothing from other servers: no Google Fonts, no analytics, no cookies.
  - Progress, records and the checklist lights are kept in the browser's localStorage,
    so they stay on the device they were made on and are separate for each device.
    The copy on your website starts with empty progress; it does not share progress
    with the claude.ai version.
  - If you would rather keep the page out of search engines, add this line inside <head>
    of index.html:  <meta name="robots" content="noindex">
  - Without the fonts folder the app still works and falls back to system fonts.
  - Direct links work, for example .../komma-labor/#test or .../komma-labor/#arena-rallye
