# Hyper Scoreboard
A lightweight, customizable, PlaceholderAPI-powered scoreboard plugin for modern Spigot/Paper servers.

Hyper Scoreboard is built for performance, clean code, and easy customization.  
It supports live placeholders, reload commands, version checking, and a modular multi-file structure for easy development.

---

## ✨ Features

- Lightweight & efficient (pure Bukkit API)
- Fully customizable scoreboard (title + lines)
- Live updates every second
- PlaceholderAPI support
- Multi-file clean architecture
- `/hyper` command system
- `/hyper scoreboard reload` to refresh all scoreboards
- `/hyper version` to check for updates
- Async version checker
- TAB-proof (won’t get overridden by TAB plugin)
- No NMS, no FastBoard, no packets — works on all modern versions

---

## 📥 Installation

1. Download the latest release from the Releases page.
2. Drop the `.jar` into your server’s `plugins/` folder.
3. Install PlaceholderAPI (required).
4. Restart your server.
5. Edit `config.yml` to customize your scoreboard.

---

## 📎 Required Papi downloads


Make sure Placeholder API is installed and on the latest version:
/papi ecloud install Player
/papi ecloud install Server
/papi ecloud install Statistic
/papi ecloud install Vault
/papi ecloud install LuckPerms
/papi reload

---

## 🧾 Commands

| Command | Description |
|--------|-------------|
| `/hyper` | Shows help menu |
| `/hyper scoreboard reload` | Reloads scoreboard + reapplies to all players |
| `/hyper version` | Shows current version + checks for updates |


---

## 🤝 Dependencies

- PlaceholderAPI (soft-depend)
- Vault (optional)
- LuckPerms (optional)

---

## ❤️ Credits

Developed by ClaretDigit1  

