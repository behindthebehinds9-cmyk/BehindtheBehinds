BTB — SPORT UP CLOSE WEBSITE

PUBLISH
Drag this whole folder into https://app.netlify.com/drop
(To update later: drag the folder in again, or go to your site > Deploys > drag & drop.)

VIDEOS (auto-updating)
"The latest" section embeds your YouTube uploads playlist (UUtJlvBEQt9r9Zor0xef83lQ).
Every video you post to @Behindthebehinds appears there automatically. Nothing to edit.

HERO "LATEST VIDEO" CARD
This one is set by hand. In index.html search for 2jfcS0CovdU (appears twice: the link and the thumbnail)
and swap in the new video's ID. Change the small label text ("2026 Grand Final") too.

PHOTO STRIP
In index.html near the bottom, find: const tiles = ['photo1.jpg', ...]
Add your image files to this folder and add their names to the list. 9:16 (portrait) crops look best.

BOUNCING HEAD
The file is photo-bounce.png (transparent PNG). Replace it with another cutout to change it.
Speed: in index.html find "bvx = 1.2, bvy = 0.9" — bigger numbers = faster.

LEADERBOARD (read-only for visitors)
Edit rankings.json, e.g.
[{"player":"Josh Giddey","sport":"AFL","fit":7,"creativity":6}]
Sorted by total, then Sport Fit, then earliest entry (order in the file).

CONTACT FORM
Still opens the visitor's email app addressed to behindthebehinds9@gmail.com (nothing sent to a server).

COLOURS
Navy #0f1419 · Cream #e8f0f8 · Red #c74536 · Sky #5ba3c7
Fonts: Anton (headlines), Barlow (body) — bundled in /fonts, no Google dependency.
