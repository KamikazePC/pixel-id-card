# Pixel ID Card

A digital ID card with a pixelated portrait that cycles through animated effects (ASCII, blocks, dither, halftone, signal, rain). It's one HTML file with no build step.

## Features

- **Portrait effects.** Upload a photo, then let the effects cycle or lock one.
- **Layouts.** The original card plus a set of pixel-stack layouts, each with its own info arrangement.
- **Photo outlines.** Normal, stepped wave, stepped corners or full bleed.
- **Lanyards.** Flat, printed, pixel, cord, ball chain or none. Strap colours and hardware finish are editable.
- **3D view.** A three.js card on a physics-driven lanyard. Drag it to swing, double-click to flip, click to change the effect.
- **Exports.** PNG, video (MP4 or WebM), and Apple Wallet and Google Wallet starter templates.

## Run it

Open `index.html` in a browser. Some features need it served over HTTP, for example:

```bash
npx serve .
```

Fonts and libraries (Geist, qrcode-generator 1.4.4, three.js 0.160.0) load from CDNs.

## License

MIT
