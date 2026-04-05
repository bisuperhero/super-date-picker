<p align="center">
  <img src="superdatepicker.svg" alt="SuperDatePicker" width="80" />
</p>

<h1 align="center">SuperDatePicker for Power BI</h1>

<p align="center">
  A free, fully customizable date picker custom visual for Power BI.<br />
  Single date, date range, and inline mini calendar modes.
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.0-blue" />
  <img alt="Power BI API" src="https://img.shields.io/badge/Power%20BI%20API-5.11-orange" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT%20with%20Commons%20Clause-green" />
</p>

<p align="center">
  <a href="https://www.superdatepicker.com"><strong>Website</strong></a> &middot;
  <a href="../../releases/latest"><strong>Download</strong></a> &middot;
  <a href="../../issues"><strong>Report a Bug</strong></a>
</p>

---

## ✨ Features

- 📅 **Single Date Picker** — select a single date with a clean calendar dialog
- 📆 **Date Range Picker** — select start and end dates, with configurable preset ranges (Last 7 days, This month, YTD, ...)
- 🗓️ **Mini Calendar** — inline calendar embedded directly on the canvas, no dialog needed
- 🎨 **Full Theming** — automatic light, dark, and high-contrast mode support; every color and font is customizable via the Format pane
- 🌍 **Localization** — respects Power BI locale for date formatting and weekday names
- ⚙️ **Configuration Transfer** — export and import visual settings as JSON to reuse across reports

## 🚀 Quick Start

### 1. Download

Download the latest `.pbiviz` file from the [Releases page](../../releases/latest).

### 2. Import into Power BI

1. Open your report in Power BI Desktop
2. In the **Visualizations** pane, click `...` → **Import a visual from a file**
3. Select the downloaded `.pbiviz` file

### 3. Add to your report

1. Click the SuperDatePicker icon in the Visualizations pane to add it to the canvas
2. Drag a **Date** column into the visual's data field
3. Open the **Format** pane to choose the calendar type and customize the appearance

## 📸 Screenshots

<!-- 
  Add screenshots to a /screenshots folder and uncomment below:
  
  | Single Date | Date Range | Mini Calendar |
  |:-----------:|:----------:|:-------------:|
  | ![Single Date](screenshots/single-date.png) | ![Date Range](screenshots/date-range.png) | ![Mini Calendar](screenshots/mini-calendar.png) |
-->

*Coming soon.*

## 📋 Requirements

- Power BI Desktop (November 2023 or later) or Power BI Service
- A date column in your dataset

## ❓ FAQ

<details>
<summary><strong>How do I filter other visuals by the selected date?</strong></summary>

SuperDatePicker uses the Power BI Advanced Filter API. Once you assign a date column, any date selection automatically cross-filters all other visuals on the page that share the same data source.

</details>

<details>
<summary><strong>Can I use this in Power BI Service (cloud)?</strong></summary>

Yes. Import the `.pbiviz` file into your report in Power BI Desktop, then publish to the Service as usual. The visual travels with the report.

</details>

<details>
<summary><strong>Is this visual certified by Microsoft?</strong></summary>

Not yet. Certification is on the roadmap. The visual follows Microsoft's certification requirements and does not make any external network calls.

</details>

## 💬 Support & Contributing

- **Bug reports & feature requests:** [Open an issue](../../issues)
- **Website & documentation:** [superdatepicker.com](https://www.superdatepicker.com)

This is a distribution-only repository — it contains the packaged `.pbiviz` file and release history. Source code is not included.

## 📄 License

MIT License with [Commons Clause](LICENSE) — free to use, but not to sell as a standalone product.

Copyright (c) 2025 Robert Junek | [BISuperhero.cz](https://www.bisuperhero.cz)
