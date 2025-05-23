# ZSH Configuration

A modern, feature-rich ZSH configuration with Powerlevel10k theme, useful plugins, and Vim keybindings.

## Features

- **🎨 Powerlevel10k Theme** - Fast, customizable prompt with instant loading
- **🔌 Plugin Management** - Zinit plugin manager with essential plugins
- **⚡ Smart Suggestions** - Auto-suggestions and syntax highlighting
- **📝 Abbreviations** - Command shortcuts that expand on space
- **⌨️ Vim Mode** - Vi keybindings with visual mode indicators

## What's Included

### Plugins
- `zsh-autosuggestions` - Command suggestions as you type
- `zsh-syntax-highlighting` - Real-time command highlighting
- `zsh-abbr` - Expandable command abbreviations

### Vim Mode
- Full Vim keybindings in terminal
- Visual mode indicator in right prompt
- `jk` mapped to escape (insert → normal mode)
- Cursor shape changes per mode

### Ready-to-Use Abbreviations
Uncomment in the config to enable:
```bash
g      → git
gs     → git status
gc     → git checkout
gcb    → git checkout -b
pi     → pnpm install
pd     → pnpm dev
cl     → clear
```

## Installation

1. **Backup existing config:**
   ```bash
   cp ~/.zshrc ~/.zshrc.backup
   ```

2. **Copy this configuration:**
   ```bash
   cp .zshrc ~/.zshrc
   ```

3. **Restart terminal or reload:**
   ```bash
   source ~/.zshrc
   ```

4. **Configure Powerlevel10k (first run):**
   ```bash
   p10k configure
   ```

## Customization

- **Add abbreviations:** Uncomment desired abbreviations in the config
- **Modify theme:** Run `p10k configure` to customize the prompt
- **Add plugins:** Use `zinit light <plugin-name>` format

The configuration auto-installs Zinit and all dependencies on first use.
