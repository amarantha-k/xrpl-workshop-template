# XRP Ledger Workshop Template

This repository is configured as a GitHub Codespaces Template to provide you with a zero-setup development environment pre-loaded with the necessary tools for working with the XRP Ledger.

No need to install Node.js, the XRPL libraries, or the CLI locally—everything works instantly in your browser!

---

## Tech Stack & Tools Included

| Technology | Purpose | Version Included |
| :--- | :--- | :--- |
| **Node.js / npm** | The core runtime for using the `xrpl.js` client library. | LTS |
| **TypeScript** | For type-safe development of XRPL applications. | Latest |
| **xrp-cli** | A global command-line tool for basic XRPL interactions. | Latest |
| **VS Code Extensions** | Pre-installed extensions for JavaScript/TypeScript development. | N/A |

---

## Getting Started (The 2-Click Setup)

Follow these two simple steps to launch your pre-configured environment in the cloud:

### 1. Open in Codespace

Click the green **"Code"** button and select **"Create codespace on main"** from the dropdown menu.

Alternatively, click this badge:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/YOUR-GITHUB-ORG/xrpl-workshop-template)

> **Note:** GitHub will create a fresh copy of this repository in a powerful cloud machine, which might take 1–2 minutes for the initial setup and dependency installation.

### 2. Verify Your Environment

Once the VS Code editor opens in your browser, the terminal should be visible at the bottom.

Run these commands to confirm all tools are correctly installed:

```bash
# Verify the core Node.js environment is ready
node --version

# Verify the global XRPL CLI is ready
xrp-cli --help
```

## Clean Up: Deleting Your Codespace

Your Codespace is a cloud-hosted environment. While generous usage is free for all new accounts, we recommend deleting your Codespace once you are fully finished to avoid incurring unexpected charges.

Please follow this step to stop your cloud environment.

1.  Go to your codespaces list by navigating to: [https://github.com/codespaces](https://github.com/codespaces)

2.  Locate and delete the codespace:
    * Find the Codespace named for your workshop (e.g., `xrpl-workshop-template...`).
    * Click the **three dots ($\dots$)** on the right side.
    * Select **Delete**.