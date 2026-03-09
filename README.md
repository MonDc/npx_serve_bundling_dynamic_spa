Dynamic Bundled SPA – Orbiting Color Boxes
Overview

This project is a dynamic single-page application (SPA) that displays four color boxes (yellow, green, gold, orange) orbiting around a central point.

It is designed as a mini-project / prototype / sandbox to demonstrate JavaScript animations, bundling, and static deployment.

The SPA is fully bundled into a single HTML file, so it can be deployed or served easily without any Node.js project setup.

Features

Four color boxes that orbit smoothly around a central point

Bundled single HTML file (bundled.html) for easy deployment

Modular development possible with index.html + app.js before bundling

Can be served locally with npx serve without npm init

Designed for learning, testing, and prototyping animation techniques

Folder Structure
dynamic-spa/
 ├─ bundled.html       # Fully bundled SPA (HTML + CSS + JS)

Before bundling, you may have index.html + app.js for modular development.

Installation & Local Hosting

Make sure Node.js is installed:

node -v
npm -v

Serve the bundled SPA locally:

npx serve path/to/dynamic-spa

The SPA runs immediately in the browser at http://localhost:5000 (default).

No npm init or build tools required — the bundled file is self-contained.

Usage

Open the SPA in any modern browser.

Observe the four color boxes orbiting continuously.

Serves as a prototype for animation experiments or small interactive demos.

Notes

Bundling combines all JS and CSS into a single HTML file, simplifying deployment.

This project demonstrates minimal tooling deployment using only npx serve.

Ideal for quick demos, learning, or prototyping animation ideas.