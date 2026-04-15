
Nexus Terminal 📟

A lightweight, single-file, offline-first game library and emulation portal.

Nexus Terminal is designed to run entirely within the browser with zero external server dependencies, making it the perfect portable arcade for preserving classic web games.

✨ Features

Single-File Architecture: The entire portal (UI, styling, logic, and emulators) is contained within a single index.html file. Just download and double-click to run.

Triple-Engine Emulation:

Ruffle Integration: Automatically detects and plays classic Adobe Flash (.swf) files.

Native HTML5 Support: Detects and securely sandboxes web games (.html) in dynamic iFrames.

EmulatorJS Integration: Safely injects a Game Boy Advance core to play .gba ROMs.

Persistent Local Vault: Uses the browser's IndexedDB to securely store hundreds of megabytes of game files locally without slowing down the UI.

Master Backup System: A robust Import/Export feature that packages all your installed games, custom directories, user notes, and in-game saves into a single .json backup file.

Built-in Toolkit:

Directory Management: Organize games into custom folders.

Notes App: An auto-saving text pad for tracking cheat codes, level passwords, and high scores.

Panic Button: Instantly redirects to an educational site by pressing [ESC].

Retro UI: Fully responsive CSS grid with dynamic themes (Green, Amber, Cyan) and a toggleable CRT scanline overlay.

🚀 How to Use

Download the index.html file.

Open the file in any modern web browser (Chrome, Firefox, Edge).

At the boot screen, enter the default developer passcode: nexus.

Click + New Directory to create a folder.

Click Install 1 Game or Bulk Install to upload your downloaded .swf, .html, or .gba files.

Click PLAY to launch.

💾 Saving Your Data

Because the terminal runs 100% locally, your game library is tied to your browser's internal cache. If you clear your browser cache, your games will be wiped.

Always use the Export Backup button to save your Master Backup .json file to your computer. You can use the Import Backup button to instantly restore your entire library and save data at any time.

🛠️ Built With

Vanilla JavaScript

HTML5 / CSS3

IndexedDB & LocalStorage API

Ruffle (Flash Emulator)

EmulatorJS (GBA Core)
* Oh and also thank you mesaredux.com for letting me use the thing whatever it is
