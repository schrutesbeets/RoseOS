# RoseOS Setup Guide

Welcome to **RoseOS**. This web-based operating system is designed to provide a simplified, high-contrast interface for essential communication and tasks.

## 📱 Device Requirements

To get the full experience, this application is designed to run on **iOS (iPhone)**.
For the best experience, add this website to your Home Screen:
1. Open the site in **Safari**.
2. Tap the **Share** button (box with an arrow).
3. Scroll down and tap **"Add to Home Screen"**.

## ⚡️ Required Shortcuts

RoseOS relies on iOS **Shortcuts** to bridge the gap between the web interface and native device apps (like your Contacts and Photos).

You **MUST** create the following two shortcuts in the "Shortcuts" app on your iPhone for the buttons to work. The names must match exactly.

### 1. Create "Open Contacts"
This shortcut is used by the **SEND TEXT** and **SELECT CONTACT** buttons.

1. Open the **Shortcuts** app on your iPhone.
2. Tap the **+** (plus) icon to create a new shortcut.
3. Tap **Add Action**.
4. Search for **"Open App"** and select it.
5. Tap on the blue "App" word and select **Contacts**.
6. Tap the arrow next to the shortcut name at the top (or "New Shortcut") and select **Rename**.
7. Name it exactly: `Open Contacts`
8. Tap **Done**.

### 2. Create "Recent Photos"
This shortcut is used by the **MY PHOTOS** button.

1. Open the **Shortcuts** app.
2. Tap the **+** (plus) icon.
3. Tap **Add Action**.
4. Search for **"Open App"** and select it.
5. Tap the blue "App" word and select **Photos**.
6. (Optional) If you want it to jump straight to Recents, you can search for "Show Album" or similar, but simply opening the Photos app is sufficient.
7. Tap the arrow next to the shortcut name and select **Rename**.
8. Name it exactly: `Recent Photos`
9. Tap **Done**.

## 🌐 Other Features

- **Google Search**: The app attempts to open searches in **Google Chrome** (`googlechromes://`) if installed. If not, it will fall back to your default browser.
- **AOL Mail**: effectively links to the AOL Mail web interface.
