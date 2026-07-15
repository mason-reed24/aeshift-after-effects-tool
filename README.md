# AESHIFT v - browser-based file converter 2026

> **AESHIFT is a client-side Adobe After Effects file converter for downgrading supported project and preset files directly in the browser, with no uploads needed.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mason-reed24/aeshift-after-effects-tool?style=flat-square)](https://github.com/mason-reed24/aeshift-after-effects-tool)

---

<p align="center">
  <a href="https://mason-reed24.github.io/aeshift-after-effects-tool/">
    <img src="https://img.shields.io/badge/Download-AESHIFT%20Latest-brightgreen?style=for-the-badge" alt="Download AESHIFT">
  </a>
</p>

> **[Direct Download - AESHIFT v](https://mason-reed24.github.io/aeshift-after-effects-tool/)**

---

[Download Latest Build](https://mason-reed24.github.io/aeshift-after-effects-tool/)

---

## What AESHIFT Does

AESHIFT is a browser-first tool for handling Adobe After Effects project and preset files when compatibility with older versions matters. It is built around downgrade workflows, so supported files can be adapted for earlier After Effects releases without installing a desktop app or sending files to a server.

Since everything executes on the client, the conversion never leaves the browser. That makes it a convenient option for working with .aep, .aepx, and .ffx files while keeping the process local and centered on version compatibility.

---

## Key Capabilities

- Converts After Effects files between supported versions
- Handles .aep, .aepx, and .ffx file types
- Operates entirely in the browser with no file uploads
- Parses and patches binary RIFX .aep files
- Updates XML version tags in project and preset files
- Strips unsupported features for older After Effects releases
- Functions as a client-side version converter
- Keeps file handling local throughout the workflow

---

## Getting Started

AESHIFT is delivered as a web app, so there is no conventional desktop installation.

To use it locally:

1. Clone or download the repository.
2. Open the web app in a browser, or serve the folder through a local static server.
3. Load the file you want to convert and begin the downgrade process.

Example local serving option:

npm install -g serve
serve .

Then open the provided local address in your browser.

---

## How to Use It

1. Launch AESHIFT in a supported browser.
2. Pick an Adobe After Effects project or preset file.
3. Select the destination version or downgrade route, if the interface provides it.
4. Start the conversion.
5. Download the converted output after processing finishes.

Typical workflow:

- Use .aep for binary project files
- Use .aepx for XML project files
- Use .ffx for preset files
- Keep conversions local in the browser session

---

## Configuration Notes

AESHIFT is mainly controlled through its browser UI. When running it locally, configuration usually comes down to how the static files are hosted and any version-dependent controls available in the interface.

If you want to change deployment behavior, keep those settings with the web app files used by your local host or static server. For most setups, no extra configuration is needed beyond opening the app and loading a supported file.

---

## Requirements

- A modern web browser
- Access to the AESHIFT web app or a local static copy
- Supported Adobe After Effects file formats: .aep, .aepx, .ffx
- Sufficient local browser memory and storage for the files being processed
- A local server only if you prefer not to open the files directly from the filesystem

---

## FAQ

**Is AESHIFT web-based or desktop-based?**  
AESHIFT runs in the browser on the client side.

**Does it upload files to a server?**  
No. The conversion flow is designed to stay in the browser without uploads.

**What file types can it handle?**  
It supports .aep, .aepx, and .ffx files.

**Why would I use it?**  
It is useful when you need to adapt After Effects project or preset files for older versions.

**What if a file does not convert correctly?**  
Confirm that the file format is supported and that the target version fits the content inside the project.

**How do I update it?**  
Replace your local copy with the latest repository version or open the latest published build.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
