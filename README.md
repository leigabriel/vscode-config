# VS Code Config

This repository contains a set of Visual Studio Code settings and a custom CSS file to enhance your editor experience.

## Installation

1. **Copy or Link the `settings.json`**
   - Open VS Code.
   - Go to `File` > `Preferences` > `Settings` (or press `Ctrl+,`).
   - Click the `{}` icon in the top right to open `settings.json`.
   - Replace your settings with the contents of this repo's `settings.json`, or merge as needed.

2. **Install Fonts (Optional)**
   - This config uses `JetBrainsMono Nerd Font`. Download and install it from [Nerd Fonts](https://www.nerdfonts.com/font-downloads).

3. **Install Recommended Extensions**
   - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
   - [Palenight Italic Theme](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme)
   - [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

4. **Enable Custom CSS**
   - Install the [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) extension.
   - Update the `vscode_custom_css.imports` path in `settings.json` to point to the absolute path of your `style.css` file from this repo.
   - Run the `Enable Custom CSS and JS` command from the Command Palette (`Ctrl+Shift+P`).
   - Restart VS Code.

---
Feel free to fork and modify for your own setup!