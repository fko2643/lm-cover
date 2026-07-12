# LM Cover

An unofficial theme customizer for [LoreMate.ai](https://loremate.ai). Change the look and feel of your chat experience — pick from six presets, tweak every color yourself, and share themes with others.

> **Unofficial fan project.** Not affiliated with or endorsed by the LoreMate development team.

---

## Features

- **6 Preset Themes** — Sunset Amber, Sepia Dream, Forest Night, Rose Quartz, Ocean Deep, Noir
- **Full Customizer** — 13 color fields grouped by Website, AI Bubble, and User Bubble
- **Speech / Action Aware** — respects LoreMate's speech/action highlighting. In None mode, everything gets your theme color; in Speech or Action mode, the highlighted text type gets your theme color while the dimmed type stays native
- **Live Preview** — changes apply instantly as you pick colors
- **Streaming Support** — message bubbles are styled correctly even mid-generation
- **My Themes** — save, edit, update, and delete your own custom color themes. Manage as many as you like.
- **Export / Import** — share themes as JSON files with the community
- **Persistent Storage** — your theme survives tab refreshes and browser restarts

---

## Installation

Since LM Cover is not on the Chrome Web Store, you'll need to load it manually. It takes less than a minute.

### Step 1: Download

[Download the latest release (.zip)](https://github.com/fko2643/lm-cover/releases) and unzip it somewhere on your computer.

### Step 2: Open Chrome Extensions

Open Chrome and go to:

```
chrome://extensions
```

### Step 3: Enable Developer Mode

Toggle the **Developer mode** switch in the top-right corner.

### Step 4: Load the Extension

Click **Load unpacked**, then select the `LM Cover` folder you just unzipped.

### Step 5: You're Done

Open [loremate.ai](https://loremate.ai), click the extension icon in your toolbar (pin it if you like), and pick a theme.

---

## How to Use

1. Click the LM Cover icon in your Chrome toolbar while on loremate.ai
2. Pick a preset from the dropdown, or select one of your saved custom themes
3. Expand **Customize Colors** to tweak individual elements
4. Click **Save as Custom** to create a new theme, or **Edit** an existing one from **My Themes**
5. While editing, click the **Update** button next to your theme to save changes
6. **Export** to share your theme, **Import** to load someone else's

### Speech / Action Behavior

LM Cover works alongside LoreMate's built-in speech/action text formatting:

| LoreMate Mode | What happens |
|---|---|
| **None** | All text gets your chosen Bubble Text color |
| **Speech** | `"quoted"` text gets your theme color, `*action*` and `action` text  stays native |
| **Action** | `*action*` and `action` text gets your theme color, `"quoted"` text stays native |

You don't need to do anything special, the extension detects your LoreMate setting automatically.

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Extension icon not showing | Pin it: click the puzzle icon in the toolbar, then the pin next to LM Cover |
| Colors don't change | Make sure you're on `https://loremate.ai` (the extension only runs there) |
| Popup looks broken | Try reloading the extension on `chrome://extensions` |
| Chrome warns about developer mode | This is normal for manually loaded extensions. The warning appears on every Chrome restart — it can only be removed by publishing to the Chrome Web Store. |
| Speech/Action colors look wrong | Switch to None and back — this forces a full refresh. If the issue persists, reload the page. |

---

## Credits

Made by Claude & Fuko. Icon based on the LoreMate brand logo.

---

*LM Cover is a community project. If LoreMate's website structure changes, certain colors may stop applying. Feel free to report issues to me on Discord or submit fixes.*
