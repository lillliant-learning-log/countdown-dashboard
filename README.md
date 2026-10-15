# milestones.io — Live Countdown Dashboard

A modern, glassmorphic countdown dashboard built with vanilla web technologies. Track milestones, events, and personal goals in real time with ambient themes, flexible sorting, and responsive grid layouts.

---

## ✨ Features

- **⏱️ Live Countdown Timers**
  - High-precision live timers ticking every second with `Days : Hours : Mins : Secs`.
  - Tabular-numeric formatting prevents digit shifting and jitter.
  - Automatically transitions to a sleek **Completed** badge once a countdown expires.

- **🎨 Ambient Glassmorphism & Dual Themes**
  - Built-in theme switcher with smooth animated transitions:
    - **Warm Nature**: Golden sunbeam gradients, lush forest aesthetics, and warm earth-toned badges.
    - **Twilight City**: Moody purple-indigo evening hues, neon pink accents, and twilight city skyline backdrop.
  - Frosted glass cards featuring dynamic backdrop blurs, glow borders, and soft elevation shadows.

- **⭐ Flexible Featured Pinning**
  - Pin any milestone with the star button to promote it to a prominent 2×2 **Featured Hero Card** with enlarged countdown numerals.
  - Unpin anytime to seamlessly revert to a balanced, uniform grid layout (`repeat(auto-fit, minmax(280px, 1fr))`).
  - Completely voluntary — never forces an unpinned card into featured status.

- **🔍 Smart Filtering & Sorting**
  - **Category Filters**: Filter by `all`, `work`, `personal`, or `travel` with color-coded badges.
  - **Dynamic Sorting**: Instant sorting by `closest` (soonest first), `furthest`, or alphabetical `A-Z`.
  - **Manual Re-order Mode**: Enable the **Manual Re-order** toggle to display dedicated move up/down controls on each card.

- **➕ Milestone Management & Local Storage**
  - Add new events via a modal dialog with custom title, date/time picker, category, and optional notes/subtitles.
  - Delete unwanted milestones with one click.
  - **Persistent State**: Milestones, themes, categories, and sorting preferences automatically persist across sessions via `localStorage`.

- **🚀 Zero Build Step & Ultra Lightweight**
  - Self-contained single-file application (`index.html`).
  - No build pipeline, npm dependencies, or frameworks required.

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript**: Modern ES6+ architecture (event delegation, state management, `localStorage` persistence).
- **CSS3 Modern Layout**: CSS Grid (`auto-fit`, named spans), Flexbox, CSS Variables, and Glassmorphism (`backdrop-filter`).
- **Typography**: [Nunito](https://fonts.google.com/specimen/Nunito) via Google Fonts for friendly, rounded typography and tabular numerals.
- **Vector Graphics**: Inline SVGs for lightweight vector artwork and crisp ambient backgrounds.

---

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/christinewong/Count-Down-Website.git
   ```

2. **Open the application:**
   - Simply double-click `index.html` or open it in any modern browser (Chrome, Safari, Firefox, Edge).
   - Alternatively, serve it locally with any static server:
     ```bash
     npx serve .
     # or
     python3 -m http.server 8000
     ```

---

## 💡 How It Works

### Card Pinning & Featured Slot
- Click the **Star icon** in the top-right corner of any card to toggle it as the **Featured Milestone**.
- When featured, the card expands across 2 columns and 2 rows with prominent typography.
- Clicking the star icon again unpins the card, returning all cards to an equal grid.

### Manual Re-ordering
1. Check the **Manual Re-order** pill in the top navigation bar.
2. Up and down arrow buttons will appear on each card's action menu.
3. Use the arrows to arrange your milestones in custom priority order.

---

## 📂 Project Structure

```
├── index.html     # Complete standalone application (markup, styling, and logic)
└── README.md      # Project documentation
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).