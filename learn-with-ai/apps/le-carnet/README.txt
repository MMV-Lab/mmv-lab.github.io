Le Carnet - French trainer (Band 2, Unite 1)
============================================

What is in this folder
  index.html   the whole app (page, styles, script and all content in one file)
  fonts/       the two typefaces the page uses, with their licence texts

How to host it
  1. Upload the folder "le-carnet" as it is to your web space
     (FTP, your host's file manager, GitHub Pages, Netlify - anything
     that serves static files).
  2. Open  https://your-domain/le-carnet/  in a browser.
  Keep index.html and the fonts folder together. You may rename the folder
  or rename index.html; nothing else needs configuring.
  It also runs straight from disk: double-click index.html.

What it needs and what it does not
  - No server-side code, no database, no build step.
  - It loads nothing from other websites: no trackers, no CDN, no web-font
    service. The page makes no network requests besides its own files.
  - Progress (stamps, error box, name, drafts) is stored only in the visitor's
    browser (localStorage, key "carnet-fr-b2-v1"). Nothing is sent anywhere.
    A different device or a cleared browser starts fresh.
  - Read-aloud uses the French voice installed on the visitor's device
    (browser speech synthesis). Devices without a French voice stay silent;
    everything else works.

Deep links
  .../le-carnet/#station-rentree   (also: beau, de, vp, emo, look, qui, rel,
                                    lire, ton, son)
  .../le-carnet/#test              Test-Arena
  .../le-carnet/#regeln            Spickzettel (all rule cards)

Updating
  When a new version is made, replace index.html. Visitors keep their
  progress because it is tied to your site's address, not to the file.

Fonts
  Bricolage Grotesque and Playwrite FR Moderne, both under the SIL Open Font
  License 1.1 (texts in fonts/). The licence allows hosting them with the page.

Content
  All French sentences, stories and exercises were written for this app and
  follow the language points of the unit; no textbook text is reproduced.
