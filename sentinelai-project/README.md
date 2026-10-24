# SentinelAI – Smart Home Digital Twin

A self-contained 3D smart-home security simulator built with three.js
(loaded from cdnjs at runtime — an internet connection is required the
first time you open it).

## Run it

Just open `index.html` in a modern browser (Chrome, Edge, Firefox).

In VS Code, the easiest way is the **Live Server** extension:
1. Install the "Live Server" extension (ritwickdey.liveserver).
2. Right-click `index.html` → "Open with Live Server".

Double-clicking the file directly also works in most browsers.

## Structure

Everything — HTML, CSS and JavaScript — lives in `index.html`. There
are no build steps and no dependencies to install; three.js r128 is
pulled from `cdnjs.cloudflare.com` at load time.
