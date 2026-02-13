# Unity Explorer 2.0 (W.I.P)

Unity Explorer 2.0 is a powerful runtime inspection tool for Unity games using IL2CPP, built for BepInEx 6. It allows modders, developers, and researchers to explore and interact with Unity games in real-time — inspecting objects, components, and assemblies.

---

## Features

- Browse all loaded assemblies and types.
- Inspect GameObjects, Components, and their fields/properties.
- Modify variables and invoke methods at runtime.
- Explore Unity scenes dynamically.
- Compatible with IL2CPP Unity games.
- Seamless BepInEx 6 integration for automatic plugin loading.

---

## Requirements

- Unity game built with IL2CPP.
- BepInEx 6 installed in the target game.
- Windows / Linux (primarily tested on Windows).

---

## Installation

1. Download BepInEx 6 from [BepInEx Releases](https://github.com/BepInEx/BepInEx/releases).  
2. Extract it into the root directory of your Unity game.  
3. Place `UnityExplorer2.0.dll` into the `BepInEx/plugins` folder.  
4. Launch the game. Unity Explorer 2.0 will load automatically with BepInEx.

---

## Usage

- Open the Explorer menu using the default keybinding: `F1` (configurable).  
- Navigate through loaded assemblies and game objects.  
- Inspect and modify fields, properties, and methods safely at runtime.  
- Use the search bar to quickly locate objects or components.

---

## Notes / Warnings

- **IL2CPP Support Only:** Works only on IL2CPP Unity games.  
- **Experimental Features:** Runtime modifications may cause instability. Use at your own risk.  
- **Game Integrity:** Modifying data may crash the game or corrupt saves. Backup files first.  
- **No Online Exploits:** Intended for offline/single-player testing only.

---

## Developer Notes

- Hooks into IL2CPP assemblies using reflection and runtime metadata.  
- Scene object inspection uses cached `GameObject` references for better performance.  
- Runtime modifications use temporary backups of original values to avoid crashes.  
- Extendable with custom inspectors, method invocation UI, and search optimizations.

> Tip: For large scenes, use the search filter to avoid UI lag.

---

## Changelog

None for now.

---

## Contributing

1. Fork the repository.  
2. Implement features or fixes.  
3. Submit a pull request with explanations.  
4. Test thoroughly on multiple IL2CPP Unity games.

---

## Credits

- Built using BepInEx 6.  
- Inspired by original Unity Explorer projects.  
- Thanks to the Unity modding community for guidance.

---

## License

MIT License. Use responsibly and at your own risk.
