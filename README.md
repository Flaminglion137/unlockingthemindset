Circuit Breaker

A page you open instead of the feed. No backend, no tracking — everything runs in the browser and your streak is stored locally on your device.

Live: https://flaminglion137.github.io/unlockingthemindset/

How it works


Pause — a 5-second breathing countdown before anything else loads.
Check-in — pick the feeling that's actually driving the urge (bored, anxious, avoiding something, lonely, tired, autopilot), or use "Name your own goal and blocker" to type exactly what you're avoiding and what's stopping you.
Reframe — a line written for that specific feeling (or your own words), plus a "play it forward" prompt.
Redirect — one tiny, concrete action to do instead of scrolling.
Win — updates your streak, total breaks, and estimated time reclaimed.


Files


index.html — the live site.
goal-breaker.html — identical copy, kept as a separate file so it can be uploaded/tested without overwriting index.html.


Deploy on GitHub Pages


Push the file(s) to this repo's default branch.
In Settings → Pages, set the source to the branch/root (or /docs if you move it there).
Your live URL appears at the top of that Pages settings screen.


Customize


Moods & quotes: edit the moods object near the top of the <script> block in index.html.
Colors: CSS variables at the top of <style> (--accent, --accent2, --accent3, --bg).
Countdown length: let n = 5; in the script.
Time-reclaimed estimate: MIN_PER_BREAK in the script (minutes credited per completed break).
Reset your streak: click "reset my data" in the footer of the live page — clears local storage only, nothing server-side.
