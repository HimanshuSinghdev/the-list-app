# The List — Shopping Tracker

[![Open App](https://img.shields.io/badge/🚀_Open_App-Click_Here-2A2A28?style=for-the-badge)](https://himanshusinghdev.github.io/the-list-app/)

👉 **Live App Link:** [https://himanshusinghdev.github.io/the-list-app/](https://himanshusinghdev.github.io/the-list-app/)

Track what you need to buy and check items off as you purchase them. "The List" is a beautifully designed, receipt-themed Progressive Web App (PWA) crafted with care by Himanshu.

## ✨ Features

* **Installable PWA:** Fully installable as a native-feeling app on desktop and mobile devices.
* **Smart Auto-Categorization:** Automatically sorts your items into logical categories (Produce, Dairy, Pantry, etc.) using a fast, built-in offline dictionary.
* **AI Fallback (Gemini):** Optional integration with the Gemini API to intelligently categorize any unrecognized items.
* **Price Tracking & Estimates:** Add prices to items to see a running estimated total before you hit the checkout counter.
* **Recurring Items:** Set custom reminders (e.g., 7, 14, or 30 days) for items you buy frequently, and they will automatically return to your "To Buy" list.
* **Multiple Lists:** Create and manage separate lists for different needs (e.g., Groceries, Hardware, Pharmacy).
* **Custom Currency:** Easily update the currency symbol (₹, $, €, £) from the settings menu.
* **Shareable:** Share your neatly formatted shopping list using your device's native share menu or copy it to your clipboard.

## 🚀 Tech Stack

* **Frontend:** Pure HTML, CSS (featuring CSS variables, custom gradients, and flexbox), and Vanilla JavaScript (No frameworks).
* **Caching & Updates:** Powered by a Service Worker (`sw.js`) using a network-first strategy, ensuring users always get the latest version without needing to manually reinstall.
* **Typography:** Features specialized fonts like `Space Mono`, `Space Grotesk`, and `Caveat` to achieve a tactile, printed-receipt aesthetic.
* **Data Storage:** Uses `LocalStorage` to keep all user data completely private and stored directly on the device.

## 📂 File Structure

* `index.html`: The core application UI, styling, and JavaScript logic.
* `sw.js`: The Service Worker handling asset caching (`app-cache-v17`) and offline capabilities.
* `manifest.json`: The web app manifest defining the app's standalone display, theme colors (`#2A2A28`), and start URL.
* `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`: The required app icons for home screen installation and masking.

## ⚙️ How to Add Your Gemini API Key

For the AI categorization fallback to work:
1. Tap the Settings (gear) icon in the top right of the app.
2. Paste a free Gemini API key (from Google AI Studio) into the input field.
3. The key is saved safely in your browser's local storage and is only used when the built-in offline dictionary cannot find a match.

## ☕ Support the Developer

If you find this app helpful, you can support Himanshu directly through the built-in support modal, which generates a QR code for zero-fee UPI donations.
