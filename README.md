# Bootstrap 5 Snippets for Zed

A comprehensive collection of Bootstrap 5 utility classes and component snippets for the Zed editor.

## Features

- **300+ Bootstrap 5 snippets** for rapid development
- Autocomplete support for all Bootstrap 5 utility classes
- Component snippets (alerts, badges, buttons, cards, modals, etc.)
- Responsive utility classes
- Spacing utilities (margin, padding, gap)
- Flexbox utilities
- Display utilities
- Position utilities
- And much more!

## Installation

### Via Zed Extensions

1. Open Zed editor
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows) to open the command palette
3. Type "extensions" and select **Zed: Extensions**
4. Search for "Bootstrap 5 Snippets"
5. Click **Install**

### Manual Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/ahmetcadirci25/bootstrap-5-zed-snippets.git
   ```

2. In Zed, open the command palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
3. Select **Extensions: Install Dev Extension**
4. Navigate to the cloned directory and select it

## Usage

Simply start typing any Bootstrap 5 class name in your HTML files and the autocomplete suggestions will appear.

### Examples

Type `btn-` to see all button variants:
- `btn-primary` → `btn btn-primary`
- `btn-outline-danger` → `btn btn-outline-danger`
- `btn-lg` → `btn btn-lg`

Type `text-` to see all text utilities:
- `text-center` → `text-center`
- `text-danger` → `text-danger`
- `text-uppercase` → `text-uppercase`

Type `mb-` to see margin bottom utilities:
- `mb-0` → `mb-0`
- `mb-3` → `mb-3`
- `mb-auto` → `mb-auto`

## Snippet Categories

### Components
- Alerts
- Badges
- Breadcrumbs
- Buttons
- Cards
- Carousel
- Dropdowns
- Forms
- Input Groups
- List Groups
- Modals
- Navbar
- Navs
- Pagination
- Progress
- Spinners
- Tables
- Toasts

### Utilities
- Background colors
- Borders
- Display
- Flexbox
- Float
- Interactions
- Overflow
- Position
- Shadows
- Sizing
- Spacing (margin, padding, gap)
- Text
- Vertical align
- Visibility

## Bootstrap 5 Changes from Bootstrap 4

This extension is based on the Bootstrap 4 Sublime autocomplete plugin but updated for Bootstrap 5:

- **RTL Support**: Logical properties (`ms-*`, `me-*`, `ps-*`, `pe-*`, `start-*`, `end-*`)
- **New Utilities**: Shadows, opacity, object fit, ratio, ring
- **Removed**: Bootstrap 4 specific classes replaced with Bootstrap 5 equivalents
- **Updated Components**: Cards, forms, buttons updated to Bootstrap 5 syntax

## License

MIT License - See [LICENSE](LICENSE) file for details

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.