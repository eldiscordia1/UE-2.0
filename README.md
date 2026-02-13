---

# **Unity Explorer 2.0**

**Unity Explorer 2.0** is a **powerful runtime inspection tool** for Unity games using **IL2CPP**, built specifically for **BepInEx 6**. It allows modders, developers, and researchers to explore and interact with Unity games in real-time — including inspecting objects, components, and assemblies.

---

## **Features**

* 🔹 **Browse assemblies and types** loaded in the game.
* 🔹 **Inspect GameObjects and Components**, including their fields and properties.
* 🔹 **Modify variables and invoke methods** at runtime.
* 🔹 **Dynamic scene exploration** in Unity.
* 🔹 **IL2CPP compatible** — works on games using Unity's IL2CPP scripting backend.
* 🔹 **Seamless BepInEx 6 integration** for automatic plugin loading.

---

## **Requirements**

* A **Unity game built with IL2CPP**.
* **BepInEx 6** installed in the target game.
* **Windows / Linux** (primarily tested on Windows).

---

## **Installation**

1. Download **BepInEx 6** from [BepInEx Releases](https://github.com/BepInEx/BepInEx/releases).
2. Extract it into the **root directory of your Unity game**.
3. Place **`UnityExplorer2.0.dll`** into the `BepInEx/plugins` folder.
4. Launch the game — **Unity Explorer 2.0 loads automatically** with BepInEx.

---

## **Usage**

* Open the Explorer menu using the default keybinding: **`F1`** (configurable).
* Navigate through **loaded assemblies, objects, and components**.
* Inspect and modify **fields, properties, and methods** safely at runtime.
* Use the **search bar** to quickly locate objects or components.

---

## **Notes / Warnings**

⚠️ **IL2CPP Support Only**: This version is designed exclusively for IL2CPP Unity games.
⚠️ **Experimental Features**: Runtime modifications may cause instability. **Use at your own risk**.
⚠️ **Game Integrity**: Modifying game data may crash the game or corrupt saves. Always **backup files**.
⚠️ **No Online Exploits**: Intended for **offline / single-player use only**. Using in multiplayer can result in **bans**.

---

## **Developer Notes**

* Unity Explorer hooks into **IL2CPP assemblies** using reflection and runtime metadata.
* **Scene object inspection** uses cached `GameObject` references for performance.
* Safe **runtime modifications** use temporary backups of original values to avoid crashes.
* Key targets for extension: **custom inspectors, method invocation UI, search optimization**.

> ⚡ Tip: For large scenes, use the **search filter** to avoid UI lag.

---

## **Changelog**

**v2.0 (Current)**

* ✅ Full **IL2CPP compatibility**.
* ✅ **Redesigned UI** for easier navigation.
* ✅ Enhanced **object search and inspection**.
* ✅ **Improved performance** in large scenes.

---

## **Contributing**

We welcome contributions!

1. Fork the repository.
2. Implement features or fixes.
3. Submit a **pull request with detailed explanations**.
4. Test thoroughly on multiple IL2CPP Unity games.

---

## **Credits**

* Built using **BepInEx 6**.
* Inspired by the **original Unity Explorer projects**.
* Thanks to the **Unity modding community** for guidance and ideas.

---

## **License**

Distributed under the **MIT License**. **Use responsibly** and at your own risk.

---


