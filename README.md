# MMM-Themes
Pre-built themes for MagicMirror2, designed to be interchangeable with a variety of modules.

## Modules that support these themes:
- [MMM-Todoist2 (ZachR19)](https://github.com/ZachR19/MMM-Todoist2)

## Installation

1. Clone this repository into your MagicMirror CSS folder:
   ```bash
   git clone https://github.com/ZachR19/MMM-Themes.git ~/MagicMirror/css
   ```

2. Update your `~/MagicMirror/config/custom.css` file to import the theme and configure your custom styles. Adjust the theme imports and CSS variables to match your preferred styling:

```css
@import url("../css/MMM-Themes/themes/mm-<YOUR-DESIRED-THEME>.css");
@import url("../css/MMM-Themes/themes/mm-components.css");

:root {
  --color-text: var(--mm-text);
  --color-text-dimmed: var(--mm-text-dimmed);
  --color-text-bright: var(--mm-text-bright);
  --color-background: var(--mm-bg);

  --font-primary: var(--mm-font-primary);
  --font-secondary: var(--mm-font-secondary);

  --font-size: var(--mm-font-size);
  --font-size-small: var(--mm-font-size-sm);

  --gap-body-top: var(--mm-gap-body);
  --gap-body-right: var(--mm-gap-body);
  --gap-body-bottom: var(--mm-gap-body);
  --gap-body-left: var(--mm-gap-body);

  --gap-modules: var(--mm-gap-modules);
}
```

These variables inherit from the theme CSS files. Modify the CSS variables or add additional custom styles as needed for your MagicMirror setup.
