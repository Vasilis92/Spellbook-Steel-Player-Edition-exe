# Spellbook & Steel - Player Edition

*A desktop Dungeons & Dragons companion app for players and DMs built with Rust.*  
Build custom classes, create and level up characters, and track your campaign progress with quests, NPCs, loot, and session notes. A native desktop application that keeps your whole adventure organized locally.

---

## ✨ Features

- **Custom Class Builder** – define hit dice, saving throws, proficiencies, and features by level  
- **Character Creation** – build characters with stats, backgrounds, races, and multiclassing support  
- **Level Progression** – XP-based leveling with automatic proficiency & feature unlocks  
- **Spell Slot Calculator** – supports full, half, and third casters for multiclass setups  
- **Campaign Journal** – track sessions, quests, NPCs, locations, and loot  
- **Local Data Storage** – SQLite database keeps all your data secure and portable  

---

## 🛠️ Tech Stack

- **Language**: Rust
- **GUI Framework**: eframe/egui for native desktop interface
- **Database**: SQLite with rusqlite
- **Platform**: Cross-platform desktop application

---

## 📥 Download & Installation

### Windows
Download the latest release from the [Releases](https://github.com/Vasilis92/Spellbook-Steel-player-edidtion-exe/releases) page and run the setup executable.


The application will create a `spellbooksteel.db` SQLite database file to store your character and campaign data.

---

## 📖 Usage

### Getting Started
1. **Launch the application** - Run the setup executable or built application
2. **First time setup** - The app will create a local SQLite database for your data

### Character Management
- **Create a character** - Use the character creation interface to build your D&D character with stats, race, background, and class
- **Level progression** - Add XP to automatically level up characters and unlock new features
- **Multiclassing** - Support for characters with multiple classes and proper spell slot calculations

### Class Customization
- **Manage classes** - Define custom classes with hit dice, saving throws, proficiencies, and features by level
- **Class presets** - Built-in support for all standard D&D 5e classes
- **Feature progression** - Automatically unlock class features as characters level up

### Campaign Tools
- **Campaign journal** - Record sessions, quests, NPCs, locations, and loot
- **Session notes** - Keep track of important events and story developments
- **Data persistence** - All data is automatically saved to the local SQLite database

---
## 📜 License

This project is licensed under the Apache License 2.0 – see the [LICENSE](LICENSE) file for details.
