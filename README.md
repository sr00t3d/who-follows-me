# Who Follows Me?

Leia-me: [BR](README-ptbr.md)

![License](https://img.shields.io/github/license/sr00t3d/who-follows-me) ![Javascript](https://img.shields.io/badge/language-javascript-green.svg)

<img width="700" src="who-follows-me-cover.webp" />

**Who Follows Me?** is a browser extension (Manifest V3) designed to help you manage your Instagram connections in a smart, visual, and above all, secure way.

Unlike other apps that may compromise your account, this tool runs locally in your browser, respecting the platform’s limits and keeping your data private.

## Key Features

- **Automatic Scan:** Identifies who doesn’t follow you back, who your mutual followers are, verified accounts, and private profiles.
- **Advanced Filters:** Organize your list with just one click to focus on who really matters.
- **Safe Unfollow:** *Safe-Mode* system with adaptive pacing, automatic cooldown, and simulation to avoid Instagram blocks.
- **Data Export:** Save your reports in CSV or JSON formats for external analysis.
- **Modern Interface:** Compact layout, support for microinteractions, informative tooltips, and visual risk feedback.
- **Multi-language:** Native support for Portuguese (PT) and English (EN) based on your browser settings.

## Security First

Instagram has strict policies against aggressive automation. **Who Follows Me?** was built with protective layers:
- **Simulation Mode:** Test actions before executing them for real.
- **Notes Protection:** Profiles you marked with notes or considered important are protected against accidental unfollow.
- **Failure Queue:** If something goes wrong, the extension automatically manages retries without triggering annoying native alerts.

## How to install (User)

Go to: https://chromewebstore.google.com/detail/ecfokafaabljgocaeheiejiffmdhbgll

## How to install (Developer)

Since this version is under development, you can install it manually:

1. Download or clone this repository.
2. Open your browser (Chrome, Edge, Brave, or Opera).
3. Go to the Extensions page (`chrome://extensions/`).
4. Enable **"Developer mode"** in the top right corner.
5. Click **"Load unpacked"** and select the folder where the project files are located.


## How to use

1. Go to [Instagram](https://www.instagram.com) and log into your account.
2. Click the extension icon in your toolbar.
3. The extension will open an integrated interface (modal) directly on the page.
4. Wait for the list to load and use the filters to analyze your followers.

## Technologies Used

- **JavaScript (ES6+)**
- **Chrome Extension API (Manifest V3)**
- **CSS3** (Dynamic layouts and backdrop blur)
- **SweetAlert2** (For elegant visual feedback)

## License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for more details.

---
*Disclaimer: This project is not affiliated with, associated with, authorized, endorsed by, or in any way officially connected to Instagram, Facebook, or Meta Platforms, Inc.*