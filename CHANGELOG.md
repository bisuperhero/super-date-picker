# Changelog

## [0.9.0] - 2026-04-10


### Features

- Add CalendarGrid and CalendarHeader settings with customizable styles
- Add JSON schema and debugging configuration for SuperDatePicker
- Enhance package.json scripts for cleaning temporary files; improve calendar settings color application logic; refine CSS for more compact calendar cell sizing
- Increment version to 0.8.1.51; fix icon color application in SuperDatePicker
- Implement Default Selection and Custom Presets features in SuperDatePicker; add shared utilities and update capabilities
- Enhance calendar settings with new weekday customization options; remove obsolete plan document
- Implement version bumping tool and display version on landing page; update ESLint config and package scripts
- Add year navigation button size and border radius settings; update styles and tests
- Update calendar configuration and styles across multiple JSON files
- Add default background and text color options for preset ranges
- Update calendar settings and styles for improved layout and responsiveness
- Migrate config schema to new location and update TODO list
- Add month and month-range calendar types with month picker dialogs
- Update calendar settings, improve visual behavior, and enhance localization
- Enhance MiniCalendar with month presets

### Refactor

- Refactor code structure for improved readability and maintainability
- Refactor CSS variable names and update tests for calendar styling

### Chores

- (chore): Linting
- Update version and improve visual behavior

### Other

- Add manual testing guide for SuperDatePicker visual (v0.8.1.56)
- Add commit preprocessors to filter TODO messages from release notes
## [0.8.1] - 2026-04-06

Dialog height increased by 10px to better reflect the default design.
All notable changes to SuperDatePicker are documented here.
Each release is also available as a [GitHub Release](../../releases) with the `.pbiviz` file attached.

## [0.8.0] - 2026-04-05

First public beta release.

### Features

- **Three calendar modes:** Single Date Picker, Date Range Picker, and inline Mini Calendar
- **Date range presets:** Today, Yesterday, This/Previous week, This/Previous month, This/Previous year, custom "Days up to today" and "Days starting today" with configurable day count
- **Full theming:** customize colors and fonts for header, calendar body, weekday/weekend rows, selection, hover states, navigation arrows, dialog, buttons, and input box
- **Input box styling:** configurable font, colors, border width/radius, and calendar icon (show/hide, color, size, multiple icon versions)
- **Cell layout control:** adjustable cell width, height, and row gap
- **Navigation:** month/year arrows with hover states, "Today" quick-navigation button with customizable appearance
- **Dialog customization:** adjustable width and height, close icon, background and divider colors
- **Border controls:** color and width for calendar and input box
- **Preset range panel:** configurable position (top/bottom), alignment (left/center/right), gap, selected style colors, and show/hide clear button
- **Configuration transfer:** export and import all visual settings as JSON
- **Localization:** English and Czech; respects Power BI locale for date formatting and weekday names
- **First day of the week:** configurable
- **High-contrast mode** support
- **Refresh info panel:** optional text explaining how to re-enable the dialog if blocked
- **Landing page:** instruction screen when no data is assigned, with documentation and help links

### Known issues

- This is a beta release — please [report any issues](../../issues) you encounter

## [0.7.5] - 2026-04-05

Internal pre-release for initial testing.
