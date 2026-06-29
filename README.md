# Troll&Toad Export

> A Chrome extension for [TrollAndToad](https://www.trollandtoad.com/) buyers —
> turn your cart into a clean spreadsheet and move card lists in and out through
> the clipboard.

![Chrome Extension](https://img.shields.io/badge/Chrome_Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-34A853?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Features

- Build a clean table from your TrollAndToad cart
- **Export to Excel** (`.xlsx`) using SheetJS
- **Copy** the list to the clipboard, or **import** a list from the clipboard
- Navigation helpers to open cards quickly

## Installation (load unpacked)

1. Clone this repository.
2. Open `chrome://extensions` and enable **Developer mode**.
3. Click **Load unpacked** and select the project folder.
4. Open a TrollAndToad page and click the extension icon.

## Tech stack

- **Manifest V3** Chrome extension
- Vanilla **JavaScript** — background service worker + content script
- **[SheetJS](https://sheetjs.com/)** (`xlsx`) for spreadsheet export

## License

[MIT](./LICENSE) © Juan Elfers
