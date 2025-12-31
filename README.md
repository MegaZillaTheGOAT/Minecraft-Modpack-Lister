# Minecraft Modpack Lister (MML)

**Minecraft Modpack Lister (MML)** is a user-friendly tool that generates clean, sorted mod lists from your Minecraft modpack `.zip` files. Designed for simplicity, it works directly from the compiled `.exe`—no Python setup required.

---

## Features

- Automatically detects modpack type: **CurseForge** or **Modrinth**.
- Extracts **Minecraft version** and **loader type/version**.
- Detects **duplicate mods** and **client-only mods** (like HUDs or minimaps).
- Generates output in multiple formats:
  - `modlist.txt` – full list of mods with links.
  - `modlist.md` – Markdown-friendly list for documentation or websites.
  - `modlist_discord.txt` – Discord-ready text version.
  - `duplicates.txt` – highlights duplicate mods.
- Outputs everything to an `output` folder located **next to the `.exe`**.
- Automatically sorts mods alphabetically.
- Keeps the console open for 5 seconds after running so you can read messages.

---

## Usage

1. Download the compiled `.exe`.
2. Drag and drop a Minecraft modpack `.zip` onto the `.exe`.
3. Wait a few seconds; the console will show progress messages.
4. Find your output files in the newly created `output` folder next to the `.exe`.

---

## Notes

- Works on **Windows** and should also run on **Linux** if compiled appropriately.
- Requires the modpack `.zip` to include either:
  - `manifest.json` (CurseForge), or
  - `modrinth.index.json` (Modrinth)
- The tool automatically detects and handles duplicate and client-only mods for cleaner lists.

---

## License

This tool is open-source and free to use. Contributions and improvements are welcome!
