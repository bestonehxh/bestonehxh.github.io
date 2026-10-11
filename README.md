# bestonehxh.github.io

Static download site for the Sheep and Lab apps: a home page plus one landing page per app (`/sheepterm/`, `/sheeptext/`, ...). `assets/site.js` looks up each app's latest GitHub Release in the browser, links the right zip for macOS or Windows (falling back to the Releases page if the API is rate-limited), and highlights the visitor's OS. No build step at runtime, no tracking, no cookies. Pages are generated from one script kept outside this repo; the HTML is plain and can be edited directly.
