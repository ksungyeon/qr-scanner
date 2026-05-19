# QR Scanner — Chrome Extension

Scan QR codes directly from your screen without picking up your phone. Draw a region around any QR code on a webpage, or paste a screenshot, review the decoded URL, and open it — all without leaving your browser.

---

## Features

- **Draw to scan** — press your shortcut, drag a box around any QR code on screen, and the URL is decoded instantly
- **Paste to scan** — take a screenshot with Win+Shift+S, open the popup, and paste it with Ctrl+V
- **Review before you open** — every decoded URL is shown to you first; nothing opens automatically
- **Safe by design** — only `http://` and `https://` URLs are allowed; dangerous protocols are blocked
- **Fully local** — all decoding happens on your device; no data is sent anywhere
- **No account needed** — install and use, nothing else required
- **Customisable shortcut** — set any keyboard shortcut you like via Chrome's shortcut settings

---

## Installation

### From the Chrome Web Store
Search for **QR Scanner** or install directly from the listing *(link coming soon)*.

---

## How to use

**On-screen scan**
1. Press `Alt+Q` (or your custom shortcut) on any page
2. Draw a box around the QR code
3. Review the URL in the confirmation prompt
4. Click **Open link** to navigate

**Paste a screenshot**
1. Take a screenshot with `Win+Shift+S` and copy it to the clipboard
2. Click the extension icon to open the popup
3. Press `Ctrl+V` or click the paste zone
4. Review and open as usual

---

## Permissions

| Permission | Why it's needed |
|---|---|
| `activeTab` | To capture a screenshot of the current tab when you initiate a scan |
| `tabs` | To open the confirmed URL in a new tab |
| `scripting` | To show the selection overlay and confirmation prompt on the page |
| `clipboardRead` | To read an image you paste into the popup |

---

## Privacy

- No data is collected, stored, or transmitted. Everything runs locally in your browser. See the full [Privacy Policy](https://ksungyeon.github.io/qr-scanner/privacy-policy.html).

---

## Built with

- [jsQR](https://github.com/cozmo/jsQR) — QR code decoding library
- Chrome Extensions Manifest V3
