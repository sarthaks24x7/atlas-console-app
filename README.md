# Atlas Console

**A free, local Windows app for running ad-hoc SQL against an Oracle Fusion pod through BI Publisher.**

🌐 **Landing page:** https://sarthaks24x7.github.io/atlas-console-app/
⬇️ **Download:** [Releases](https://github.com/sarthaks24x7/atlas-console-app/releases/latest)

> ℹ️ This repository hosts the **public download page and releases** for Atlas Console.
> The application source is maintained privately.

---

## What is it?

Atlas Console lets you run ad-hoc SQL against an Oracle Fusion pod and read the results in a
fast table — without building a report. It runs entirely on your own PC, like Jupyter Notebook:
a small local server plus your web browser. There is no database engine; queries flow through
Oracle's BI Publisher SOAP API.

## How to use

1. Download `AtlasConsole-win-x64.zip` from the [Releases page](https://github.com/sarthaks24x7/atlas-console-app/releases/latest).
2. Extract the folder anywhere (keep all files together).
3. Double-click **`AtlasConsole.exe`**.
4. Your browser opens to `http://127.0.0.1:4717`.
5. Add a connection (your Fusion pod URL, username, password) and start running SQL.

To quit, close the console window. To uninstall, run `Uninstall.cmd` and delete the folder.

## Requirements

- **Windows 64-bit** — that's it. Node.js is bundled; you install nothing.
- No admin rights, no registry changes, no services.

## Privacy & safety

- Runs 100% locally. Your SQL and credentials only ever talk to **your own** Fusion pod.
- Connection passwords are encrypted at rest in `%APPDATA%\AtlasConsole`.
- The app is not yet code-signed, so Windows SmartScreen may warn — choose **More info → Run anyway**.

---

*Not affiliated with Oracle Corporation. Oracle and Fusion are trademarks of their respective owners.*
