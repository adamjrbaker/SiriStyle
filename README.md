# SiriStyle

A theme designed to feel like native to IOS with support for lovelace-mushroom cards, bubble-cards and more.

## Installation

To install the theme, follow these steps:

1. **Download the Theme**: Clone this repository or download the ZIP file and extract it.
2. **Add the Theme to Home Assistant**:
   - Place the `SiriStyle` folder in the themes directory of your Home Assistant configuration.
3. **Configure Home Assistant**:
   - Open your `configuration.yaml` file and add the following line:
     ```yaml
     frontend:
       themes: !include_dir_merge_named themes
     ```
4. **Restart Home Assistant**: After making changes, restart Home Assistant to apply the new theme.

## Usage

Once the theme is installed, you can select it from the Home Assistant user interface:

1. Go to your Home Assistant profile.
2. Under the "Themes" section, select your new theme from the dropdown menu.

## Contributing

If you would like to contribute to this theme, feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.