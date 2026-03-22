# My VS Code Themes

This repository contains my custom Visual Studio Code color themes in the `themes/` directory. Each theme is packaged as a small folder with a color theme JSON you can preview, package, or install locally.

Included themes

- `emo-hacker-stranger` — a dark theme with Dracula and neon accents.
- `spiderman-style` — a themed style inspired by Spider-Man.

Try a theme locally

1. Open this repository or the specific theme folder in VS Code (`File -> Open Folder...`).
2. Press `F5` to run an Extension Development Host and load the theme temporarily.
3. In the host window, open `Preferences: Color Theme` and choose the theme.

Package & install (optional)

```bash
npm install -g vsce
cd themes/<theme-folder>
vsce package
code --install-extension <theme-name>-0.0.1.vsix
```

Manual local install

Copy the theme folder to your extensions directory (example):

```bash
cp -r themes/<theme-folder> ~/.vscode/extensions/<theme-name>-0.0.1/
```

Replace `<theme-folder>` and `<theme-name>` with the folder/name you want to install.

Want help packaging or publishing any theme to the Marketplace? Ask and I can package one for you.
