# One Pack Master

<div align="center">

![One Pack Master Logo](scrlogo.png)

**A curated collection of essential VS Code extensions for modern web development**

[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code-Marketplace-blue?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=devLocifer.one-pack-master)
[![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=devLocifer.one-pack-master)
[![Downloads](https://img.shields.io/badge/downloads-0-orange?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=devLocifer.one-pack-master)

</div>

## Overview

One Pack Master is a carefully curated VS Code extension pack designed to supercharge your development workflow. This collection includes the most essential extensions that every developer needs, from code formatting and linting to productivity tools and themes.

Perfect for:

- **Frontend Developers** working with JavaScript, TypeScript, and modern frameworks
- **Full-Stack Developers** who need comprehensive tooling
- **Teams** looking to standardize their development environment
- **Beginners** who want a ready-to-use setup

## What's Included

This extension pack automatically installs the following essential extensions:

### **Styling & Frameworks**

- **[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)** - Intelligent autocomplete, syntax highlighting, and linting for Tailwind CSS

### **Code Quality & Formatting**

- **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** - Find and fix problems in your JavaScript/TypeScript code
- **[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** - Code formatter for consistent code style

### **Productivity & Editing**

- **[Auto Import - ES6, TS, JSX, TSX](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)** - Automatically finds, parses and provides code actions for all available imports
- **[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)** - Automatically rename paired HTML/XML tags
- **[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)** - Spelling checker for source code

### **Git & Version Control**

- **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)** - Supercharge Git capabilities in VS Code

### **Development Server**

- **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** - Launch a development local server with live reload feature

### **UI & Themes**

- **[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=pkief.material-icon-theme)** - Material Design icons for VS Code

### **AI Assistant**

- **[GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=github.copilot)** - AI pair programmer that helps you write code faster

## Installation

### Via VS Code Marketplace

1. Open VS Code
2. Go to Extensions (`Ctrl+Shift+X` or `Cmd+Shift+X`)
3. Search for "One Pack Master"
4. Click "Install"

### Via Command Line

```bash
code --install-extension devLocifer.one-pack-master
```

## Quick Start

After installation, all extensions will be automatically installed and ready to use. Here are some quick tips to get started:

1. **Open a project** - The extensions will automatically detect your project type
2. **Configure Prettier** - Add a `.prettierrc` file for consistent formatting
3. **Set up ESLint** - Add an `.eslintrc` file for code linting rules
4. **Start Live Server** - Right-click on an HTML file and select "Open with Live Server"

## Recommended Settings

Add these settings to your VS Code `settings.json` for the best experience:

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "tailwindCSS.includeLanguages": {
    "html": "html",
    "javascript": "javascript",
    "css": "css"
  },
  "material-icon-theme.activeIconPack": "react",
  "liveServer.settings.donotShowInfoMsg": true
}
```

## Perfect For

- **React/Next.js** projects
- **Vue.js** applications
- **Svelte/SvelteKit** projects
- **HTML/CSS/JavaScript** development
- **TypeScript** projects
- **Tailwind CSS** styling
- **Node.js** backend development

## Contributing

Found a bug or have a suggestion? We'd love to hear from you!

- **Issues**: [Report bugs or request features](https://github.com/diazdjul19/one-pack-master/issues)
- **Email**: [diazdjul19@gmail.com](mailto:diazdjul19@gmail.com)

## License

This extension pack is released under the [MIT License](LICENSE).

## Author

**Diaz Djuliansyah**

- Email: [diazdjul19@gmail.com](mailto:diazdjul19@gmail.com)
- Publisher: devLocifer
