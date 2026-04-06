<p align="center">
  <img src="superdatepicker.svg" alt="SuperDatePicker" width="80" />
</p>

<h1 align="center">SuperDatePicker for Power BI</h1>

<p align="center">
  A free, fully customizable date picker custom visual for Power BI.<br />
  Single date, date range, and inline mini calendar modes.
</p>

<p align="center">
  <a href="../../releases/latest"><img alt="Version" src="https://img.shields.io/github/v/release/bisuperhero/super-date-picker?label=version&color=blue" /></a>
  <img alt="Power BI API" src="https://img.shields.io/badge/Power%20BI%20API-5.11-orange" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT%20with%20Commons%20Clause-green" />
</p>

<p align="center">
  <a href="https://www.superdatepicker.com"><strong>Documentation</strong></a> &middot;
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

## ⚙️ Configuration Options

All settings are available in the **Format pane** in Power BI.

### Calendar modes

| Mode | Description |
|------|-------------|
| **Single Date Picker** | Click to open a calendar dialog, select one date |
| **Date Range Picker** | Dialog with start/end date selection and preset ranges |
| **Mini Calendar** | Inline calendar rendered directly on the canvas — no dialog |

### Date range presets

Available presets for the Date Range Picker (each can be shown or hidden individually):

Today, Yesterday, This week, Previous week, This month, Previous month, This year, Previous year, Days up to today (custom count), Days starting today (custom count)

Preset panel position (top/bottom), alignment (left/center/right), and selected-state colors are configurable.

### Theming

Every visual element is customizable:

- **Header** — background color, font color, font size
- **Calendar body** — background, font, weekday and weekend row colors
- **Navigation arrows** — arrow type, colors, hover colors (month and year separately)
- **Today button** — color, font size, uppercase, spacing
- **Selection** — selected day colors, range fill color, today accent, disabled day color
- **Hover** — background and text color
- **Dialog** — background, divider, input field colors, custom width and height
- **Buttons** — OK and Cancel with separate background and font colors
- **Input box** — font, colors, border width/radius, calendar icon (show/hide, color, size, multiple icon variants)
- **Cell layout** — cell width, height, row gap
- **Border** — color and width
- **Font** — family and size

### Other settings

- **First day of the week** — configurable (Monday, Sunday, etc.)
- **Configuration transfer** — export all settings as JSON, import into another visual
- **High-contrast mode** — automatic support
- **Localization** — respects Power BI locale for date formatting and weekday names

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

## ⚠️ Known Limitations

This is a **beta release** — the visual is functional but still being refined.

- Some advanced theming options may have edge cases or require fine-tuning
- Missing translations beyond English and Czech (help translating is welcome!)
- Not yet certified by Microsoft (certification is planned — the visual already follows certification requirements and makes no external network calls)

Found a bug? [Open an issue](../../issues/new?template=bug_report.yml) — feedback during beta is especially valuable.

## 🗺️ Roadmap

- [ ] Finalize features and theming options based on beta feedback
- [ ] Microsoft AppSource certification
- [ ] More built-in translations (see [Help Translate](#-help-translate-superdatepicker) below)


Have an idea? [Request a feature](../../issues/new?template=feature_request.yml).

## 🌍 Help Translate SuperDatePicker

SuperDatePicker currently supports **English** and **Czech**. Power BI supports 44 languages — help us cover more!

### How to contribute a translation

1. **Download** the [translation template](translations/translation-template.csv) (CSV — opens in Excel, Google Sheets, or any text editor)
2. **Fill in** the `your_translation` column with your language
3. **Submit** your translation by [opening an issue](../../issues/new?template=translation.yml) and attaching the file

No coding or GitHub experience needed — just fill in the spreadsheet and upload it.

### Translation progress (2/43 completed)

| Language | Status |
|----------|--------|
| English | ✅ Done |
| Czech (čeština) | ✅ Done |
| German (Deutsch) | Needed |
| Spanish (español) | Needed |
| French (français) | Needed |
| Italian (italiano) | Needed |
| Japanese (日本語) | Needed |
| Korean (한국어) | Needed |
| Polish (Polski) | Needed |
| Portuguese - Brazil (Português) | Needed |
| Chinese - Simplified (中文简体) | Needed |
| Chinese - Traditional (中文繁體) | Needed |
| Dutch (Nederlands) | Needed |
| Turkish (Türkçe) | Needed |
| Swedish (svenska) | Needed |
| Danish (dansk) | Needed |
| Norwegian (norsk) | Needed |
| Finnish (suomi) | Needed |
| Hungarian (magyar) | Needed |
| Romanian (română) | Needed |
| Slovak (slovenčina) | Needed |
| Croatian (hrvatski) | Needed |
| Bulgarian (Български) | Needed |
| Ukrainian (українська) | Needed |
| Greek (Ελληνικά) | Needed |
| Thai (ไทย) | Needed |
| Vietnamese (Tiếng Việt) | Needed |
| Indonesian (Bahasa Indonesia) | Needed |
| Malay (Bahasa Melayu) | Needed |
| Hindi (हिंदी) | Needed |
| Arabic | Needed |
| Hebrew (עברית) | Needed |
| Catalan (català) | Needed |
| Basque | Needed |
| Galician (galego) | Needed |
| Estonian (eesti) | Needed |
| Latvian (latviešu) | Needed |
| Lithuanian (lietuvių) | Needed |
| Kazakh (Қазақ) | Needed |
| Serbian - Cyrillic (српски) | Needed |
| Serbian - Latin (srpski) | Needed |
| Slovenian (slovenski) | Needed |
| Portuguese - Portugal (português) | Needed |

> Full list of [Power BI supported languages](https://learn.microsoft.com/en-us/power-bi/fundamentals/supported-languages-countries-regions)

## 💬 Support & Contributing

- **Bug reports & feature requests:** [Open an issue](../../issues)
- **Website & documentation:** [superdatepicker.com](https://www.superdatepicker.com)

This is a distribution-only repository — it contains the packaged `.pbiviz` file and release history. Source code is not included.

## 📄 License

MIT License with [Commons Clause](LICENSE) — free to use, but not to sell as a standalone product.

Copyright (c) 2025 Robert Junek | [BISuperhero.cz](https://www.bisuperhero.cz)
