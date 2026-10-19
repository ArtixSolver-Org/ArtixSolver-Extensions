<p align="center">
  <img src="https://artixsolver.online/assets/artix-logo.png" alt="Artix Solver logo" width="128">
</p>

# Artix Solver Browser Extension

A browser extension that automatically solves hCaptcha challenges using the [Artix Solver](https://artixsolver.online) API.

> **Disclaimer:** This project is for **educational purposes only**, to study how browser extensions interact with captcha services. Do not use it on websites or services where you do not have permission. You are responsible for how you use this software and for complying with the terms of any site you visit.
> **Warning:** Automated captcha solving may violate website terms of service and can lead to account suspension. The software is provided "as is", without warranty of any kind. Use at your own risk.

---
## Source availability

To protect against abuse and to preserve our edge, the extension's source code is not published in this repository. Download the packaged, ready-to-load build from the latest release instead. The packaged build is everything you need to run it.

---
## Features

- Automatically detects and solves hCaptcha checkboxes, image grids, drag challenges, and more
- Works on Chromium browsers (Manifest V3) and Firefox (Manifest V2)
- Sends data only to `https://artixsolver.online`

## Credits

- **Free:** 100 credits per day
- **With your own API key:** 250 credits per day. Sign up at [artixsolver.online](https://artixsolver.online) and use your key.

---

## Installation

Download the extension from [artixsolver.online/extensions](https://artixsolver.online/extensions).

### Chrome, Brave, Edge, Opera

1. Download the extension, or clone this repository.
2. Open `chrome://extensions` (or `edge://extensions`).
3. Enable **Developer mode**.
4. Click **Load unpacked** and select the `chromium/` folder.

### Firefox

1. Open `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on...**.
3. Select `firefox/manifest.json`.

---

## Setup

1. Log in at [artixsolver.online](https://artixsolver.online) and copy your API key.
2. Click the Artix Solver icon in your browser toolbar.
3. Paste the API key and click **Save**.

---

## License

MIT License. See [LICENSE](LICENSE) for details.
