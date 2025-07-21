# 🌙 userChrome.css – Custom Firefox UI Theme

### 🎨 Theme Features

This `userChrome.css` provides a **custom dark/red UI experience** with strong visual consistency and modern usability.
<img width="1567" height="369" alt="image" src="https://github.com/user-attachments/assets/f0ea2c00-d56d-40a1-8545-1da18e69d01c" />

#### 🧱 Layout & Structure
- Tabs below the navigation bar (classic placement reminiscent of older Firefox/Australis)
- Australis-style curved tabs with a modern touch
- Compact tab bar with increased height and spacing
- Removal of titlebar elements and default spacers

#### 🎨 Color & Styling
- Custom red/dark color palette:
  - Dark shades for background and inactive elements
  - Deep red for highlights, active states, and hovers
- Rounded tabs on top only for a sleek look
- Red-accented active tab with border highlight
- Hover effect on inactive tabs with red border and lighter background
- Clear contrast between active and inactive tabs

#### ➕ Tab Enhancements
- New tab ("+") button styled to match theme
- Pinned tabs supported and styled
- Tab text styling for better readability and no cutoff for descenders

#### 📑 Bookmarks & Library Panel
- Flat, red hover and selection backgrounds
- Dark background for bookmarks menus
- Square corners (no rounded menus for a sharper UI feel)

#### 🖱️ Context Menus (Right-Click Menus)
- Dark background with red hover/selection
- Flat, square-cornered design
- Full context menu styling for consistent UI


## 🔧 Installation Guide

> ⚠️ **Note:** `userChrome.css` is an advanced customization and requires manual setup. Firefox does not support it natively by default anymore, so follow the steps carefully.

### 1. Enable `userChrome.css` Support in Firefox

1. Open Firefox and go to `about:config`
2. Search for:  
toolkit.legacyUserProfileCustomizations.stylesheets
3. Set it to `true`.

### 2. Locate Your Firefox Profile Folder

1. Go to `about:support`
2. Under **"Profile Folder"**, click **"Open Folder"** (or **"Show in Finder"** on macOS)

### 3. Set Up the Chrome Folder

1. Inside your profile folder, create a new folder named `chrome` (if it doesn't already exist)
2. Place the `userChrome.css` file into this `chrome` folder

Your Firefox Profile/
└── chrome/
└── userChrome.css


### 4. Restart Firefox

Close and reopen Firefox to apply your new custom theme.


### 5. Apply the Recommended Firefox Theme (Optional but Recommended)

To make the UI **look awesome**, install this matching theme from Firefox Add-ons:

🎨 **[Black Red Mood](https://addons.mozilla.org/en-US/firefox/addon/black-red-mood/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)**


### 6. Additional Tweaks (Optional)

To improve usability, apply the following changes in `about:config`:

- **Double-click tab to close**:  
Set `browser.tabs.closeTabByDblclick` to `true`

- **Keep last tab open (don’t close window)**:  
Set `browser.tabs.closeWindowWithLastTab` to `false`

---

## ❤️ Support & Donations

If you like this theme and want to support its development, you can donate via PayPal:

**🔗 [Donate to kyrisk@gmail.com](https://www.paypal.com/donate/?business=kyrisk@gmail.com)**

Thank you for supporting open customization! 🙌

---

## 📝 License

This project is open source under the [MIT License](LICENSE).
