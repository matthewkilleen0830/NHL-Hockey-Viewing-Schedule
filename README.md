# NHL Hockey Broadcast Dashboard

An interactive, single-page web dashboard designed to simplify your NHL hockey viewing experience each week. Built with **HTML5, CSS3, JavaScript (ES6+), Bootstrap 5**, and **Plotly.js**, this dashboard provides a sleek, dark-mode visual grid of all broadcast and streaming game schedules with real-time dynamic filtering.

![NHL Hockey Broadcast Matrix Dashboard Banner](images/headerBanner.png)

---

## Live Demo

Check out the live interactive application hosted on GitHub Pages:
👉 **[https://matthewkilleen0830.github.io/NHL-Hockey-Viewing-Schedule/](https://matthewkilleen0830.github.io/NHL-Hockey-Viewing-Schedule/)**

---

## ✨ Features & Functionality

* **Dual Schedule Visualizations**:
  * **National Broadcast Networks**: Visual timeline tracking major linear networks (e.g., ABC, ESPN, NHL Network).
  * **Streaming Providers**: Dedicated schedule tracking for digital-only streams (e.g., ESPN+, Peacock, Prime Video).
* **Interactive Slicers & Adaptive Filters**:
  * **Day / Date Selection**: Instant focus on specific game days.
  * **Puck Drop Time Slicer**: Dynamic multi-select filter adapting to available face-off slots for selected days.
  * **Conference Slicer**: Multi-select conference filter that dynamically updates based on active date and time constraints.
* **Art Deco Dark Theme**:
  * Clean, polished, custom CSS UI tailored for dark mode.
  * Custom team color branding and high-contrast timeline bars for seamless visual scanning.
* **Full Analytics Integration**:
  * Integrated **Google Analytics 4 (GA4)** for tracking real-time user activity, slicer interactions, and device metrics.
  * Configured with dual IPv4 & IPv6 internal traffic exclusion rules to keep development metrics clean.
* **SEO & Social Share Ready**:
  * Fully equipped with **Open Graph** and **Twitter Card** metadata for rich media link previews across iMessage, X, LinkedIn, and Discord.
  * Embedded **Schema.org (JSON-LD)** structured data for enhanced search engine indexing.

---

## 🛠️ Tech Stack & Libraries

| Category | Technology / Library |
| :--- | :--- |
| **Frontend Framework** | HTML5, Modern CSS3, JavaScript (Vanilla ES6+) |
| **UI Layout** | Bootstrap 5.3 |
| **Data Visualization** | Plotly.js |
| **Hosting & Deployment**| GitHub Pages |
| **Analytics** | Google Analytics 4 (gtag.js) |
| **Typography & Assets**| Google Fonts, Custom SVG Icons |

---

## 📁 Repository Structure

```text
├── index.html            # Main HTML entry point with layout & SEO metadata
├── styles.css            # Custom Art Deco dark-theme styling & responsive rules
├── script.js             # Dynamic data fetching, filter logic, and Plotly chart rendering
├── currentWeek/          # Active schedule data directory
│   └── weekFull.csv      # Weekly matchup dataset
├── images/               # Visual asset directory
│   ├── favicon.png       # Browser favicon icon
│   ├── headerBanner.png  # Dashboard header banner & Open Graph preview image
│   └── icon.png          # Web app icon
└── README.md             # Project documentation
