# ForceNX

**A premium website capture and offline reconstruction tool for Windows.**

ForceNX is a desktop application designed to discover website routes, capture accessible frontend resources, and export organized website projects for local inspection and reconstruction.

## ✨ Features

- **Multi-Page Discovery** — Discover accessible pages and routes beyond the landing page.
- **Browser Automation** — Inspect rendered websites using a browser automation engine.
- **Asset Collection** — Collect accessible images, fonts, stylesheets, and other frontend resources.
- **Animation Inspection** — Preserve original styles and scripts where possible and identify unsupported interactions.
- **Route Explorer** — View discovered pages and their capture status.
- **Offline Export** — Export captured files and supported local website reconstructions.
- **Visual Validation** — Compare screenshots and report missing resources.
- **Modern Desktop UI** — A premium dark glassmorphism interface with subtle purple accents.
- **Windows Support** — Designed for Windows desktop deployment.

## 🛠️ Technology Stack

- C++20
- Qt 6
- CMake
- Node.js
- Playwright
- SQLite

## 📦 Download

Download the latest Windows release from the repository's **Releases** section.

Choose the packaged Windows distribution and follow the included installation instructions.

## 🚀 Getting Started

1. Download the latest available Windows release.
2. Extract the portable package or run the installer, depending on the release format.
3. Launch `ForceNX.exe`.
4. Enter a website URL you are authorized to inspect.
5. Configure capture options and start scanning.
6. Review discovered routes, assets, and errors.
7. Export the captured project.

## ⚠️ Important Limitations

ForceNX captures accessible frontend resources; it does not automatically download a website's private server code or database.

Authentication-protected pages require authorized access. APIs, payment processing, server-side functionality, and live user data may not work offline.

Capture completeness depends on the website architecture, browser behavior, access permissions, and available resources.

## 🔒 Responsible Use

Use ForceNX only on websites you own or are authorized to inspect. Respect copyright, licenses, privacy, website terms, and applicable access restrictions.

Do not use the application to bypass authentication or other access controls.

## 📋 Project Status

ForceNX is under development. Features, compatibility, and packaging may change between releases.

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for the full license text.
