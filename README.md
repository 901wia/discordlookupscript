# Discord Lookup UserScript

> **Important Notice**: This project is intended for educational and experimental purposes. Please read the disclaimer carefully before use.

---

## Overview

This UserScript adds a lightweight lookup panel to Discord Web that allows you to fetch **publicly available user or guild metadata** (such as avatars, banners, and basic flags) by ID. It is designed as a **technical experiment** focusing on UI/UX, asset handling, and request management within a userscript environment.

The project is **not affiliated with Discord** and does **not use any officially documented or supported Discord APIs**.

---

## Features

* Minimal floating lookup panel
* User ID and Guild ID lookup
* Avatar and banner preview
* One-click asset download (max resolution)
* Abortable requests to avoid request flooding
* Clean, isolated UI with no Discord UI modification

---

## Requirements

* A modern desktop browser (Chrome / Firefox)
* A userscript manager:

  * Tampermonkey (recommended)
  * Violentmonkey

---

## Installation

1. Install a userscript manager for your browser.
2. Download or copy the contents of `901DcTool.user.js`.
3. Create a new userscript in your userscript manager and paste the code.
4. Save and enable the script.
5. Open **[https://discord.com/app](https://discord.com/app)** or **[https://discord.com/channels/](https://discord.com/channels/)**.

Once loaded, a small toggle button will appear in the bottom-left corner of the screen.

---

## Usage

1. Click the toggle button to open the lookup panel.
2. Enter a **User ID** or **Guild ID** into the input field.
3. The script will automatically attempt to resolve the ID.
4. If a match is found:

   * User: avatar, banner, and basic flags are displayed
   * Guild: icon, banner, and approximate statistics are displayed
5. Click on an avatar or banner to download the asset at maximum available resolution.

> Tip: IDs must be at least 17 characters long to be processed.

---

## Account Safety Recommendations

* **Do not use this script on your main Discord account.**
* If you choose to test or experiment, use **alternative, test, or disposable accounts only**.
* Avoid excessive or automated lookups.
* Understand that any use of this script is done **at your own risk**.

---

## ⚠️ Legal & Usage Disclaimer

This project is provided **for educational and experimental purposes only**.

It interacts with Discord’s infrastructure using **user authentication tokens** and performs direct API requests that are **not part of Discord’s officially documented or supported workflows**. As such, usage of this project **may violate Discord’s Terms of Service** and **may result in account limitations or termination**, at Discord’s sole discretion.

Enforcement and detection mechanisms are **opaque and subject to change at any time**. The absence of immediate consequences **does not imply safety or approval**.

**This project must not be used on primary or personal accounts.** If used at all, it should be limited strictly to **secondary, test, or disposable accounts**, with full awareness of the associated risks.

The author assumes **no responsibility or liability** for any form of account action, data loss, or other consequences arising from the use, misuse, or modification of this project. By accessing or using this repository, you acknowledge and accept **full responsibility** for your actions.
