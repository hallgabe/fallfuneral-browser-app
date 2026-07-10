# Fallfuneral v1.0.0 - legal workflow tool 2026

> **Fallfuneral is a browser-based legal workflow tool for attorneys that keeps research, arrangements, conflict checks, and document generation in one offline-ready single-file app.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hallgabe/fallfuneral-browser-app?style=flat-square)](https://github.com/hallgabe/fallfuneral-browser-app)

---

<p align="center">
  <a href="https://hallgabe.github.io/fallfuneral-browser-app/">
    <img src="https://img.shields.io/badge/Download-Fallfuneral%20Latest-brightgreen?style=for-the-badge" alt="Download Fallfuneral">
  </a>
</p>

> **[Direct Download - Fallfuneral v1.0.0](https://hallgabe.github.io/fallfuneral-browser-app/)**

---

[Download Latest Build](https://hallgabe.github.io/fallfuneral-browser-app/)

---

## What Fallfuneral Does

Fallfuneral is built for legal work that benefits from staying close to the desktop browser instead of a remote service. It helps attorneys organize matters, review conflicts, manage deadlines, and generate documents without relying on a hosted backend. Since it ships as a single HTML file, deployment stays simple and self-contained.

The app is aimed at lawyers and legal teams that want a compact, offline-friendly workspace for research and organization. It keeps data in the browser through IndexedDB, with localStorage as a backup path, and it includes audit history plus provenance fields so changes and exports remain traceable.

---

## Core Capabilities

- Works fully in the browser with no server, login, or account creation
- Delivered as one HTML file for easy deployment
- Organizes arrangements, clients, advisers, and firms
- Provides conflict checking for legal workflow review
- Bundles US law corpus material with practice-area guidance
- Records critical dates, time entries, fees, and retained advice
- Keeps data locally in IndexedDB, with localStorage as fallback
- Produces hashed audit history exports with provenance details
- Can be hosted directly on GitHub Pages

---

## Setup

1. Download or clone the repository to your machine:
   `git clone https://github.com/hallgabe/fallfuneral-browser-app.git
2. Open the single HTML file in a modern browser, or publish it to a static host such as GitHub Pages.
3. No server, database, or account setup is required for basic use.

If you are using the hosted build, open the latest download link and start working directly in the browser.

---

## How to Use It

Typical workflow:

1. Open Fallfuneral in your browser.
2. Create or load a matter, arrangement, client, adviser, or firm record.
3. Run conflict checks before moving forward with work.
4. Add notes, dates, time entries, fees, and retained advice as needed.
5. Use the document generation features to produce the output you need.
6. Export audit history when you need a hashed record with provenance fields.

Because the app is browser-based, your workflow stays local to the device unless you intentionally move the data elsewhere.

---

## Configuration

Fallfuneral stores working information in browser storage rather than in a separate configuration system.

- Primary storage: IndexedDB
- Fallback storage: localStorage
- Deployment: single static HTML file

If you clear browser storage, the local dataset and settings associated with the app may be removed as well. For multi-device coordination, use the broadcast sync behavior supported by sibling tools where applicable.

---

## Requirements

- A modern browser with IndexedDB support
- JavaScript enabled
- Enough local storage for matters, records, and audit history
- Optional static hosting if you want to publish the file on GitHub Pages

No separate runtime, package manager, or backend service is required.

---

## FAQ

**Do I need an account or server to use it?**  
No. It is designed to run locally in the browser without signup or a server component.

**Where does Fallfuneral keep its data?**  
Data is stored in the browser using IndexedDB, with localStorage used as a fallback.

**Is updating the app difficult?**  
No. Since it is a single-file app, updates are simple to swap in or redeploy.

**What should I check if storage is not working?**  
Verify browser support, confirm that JavaScript is enabled, and make sure local storage is available and not being cleared between sessions.

**Does it include an audit trail?**  
Yes. The project includes hashed audit history exports with provenance fields.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
