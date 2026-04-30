# GTA: San Andreas — CLEO Redux Modding API Documentation
> Comprehensive reference for JavaScript modding in GTA San Andreas using CLEO Redux and Sanny Builder Library v1.52.

---

## 📂 Repository Overview
This repository serves as a professional-grade documentation hub for modders developing any type of mod systems in GTA San Andreas[cite: 4, 5, 8]. It transforms thousands of lines of raw TypeScript declarations and Sanny Builder opcodes into searchable, human-readable interfaces[cite: 3, 4, 11].

(Updated on April-May 2026)

### 🌐 HTML Documentation
These are **Interactive Documentation Portals** designed for high-speed development workflow:
*   **Live Search:** Includes a real-time filtering system that strips spaces. Searching for "desert eagle" will instantly find "DesertEagle".
*   **Context Preservation:** Unlike standard text search, these tools collapse irrelevant code while keeping the parent class or enum header visible[cite: 5, 8].
*   **Clarity:** Specifically formatted in **VS Code Dark Mode** style to reduce eye strain during long coding sessions.

### 📝 Markdown (.md) Files
These serve as the **Logical Backbone** and static reference of the API:
*   **Class Reference:** Detailed breakdown of all game classes like Player, Vehicle, and Char, including their inputs and outputs[cite: 4, 12].
*   **Cheat-Style Integration:** Documentation for the "Natural Input" system, allowing scripts to trigger via keyboard commands[cite: 7, 8].
*   **Global Definitions:** Quick tables for global variables such as TIMERA, ONMISSION, and HOST[cite: 7, 11, 12].

---

## 🛠 Core Components

| Component | Technology | Utility |
| :--- | :--- | :--- |
| **Enums** | sa.enums.mts | Defines IDs for weapons, weather, ped types, and animations[cite: 5, 8]. |
| **Opcodes** | sa.json | The "Master Dictionary" used by CLEO Redux to translate JS to game machine code. |
| **Classes** | sa.d.ts | Object-oriented wrappers allowing the use of class methods instead of raw hex addresses[cite: 7, 11, 12]. |
| **Events** | events.d.ts | Hooks for world triggers like vehicle creation or entity deletion[cite: 10]. |

---

## 👥 Credits
Developed and maintained by **Leuan**. 
*Special thanks to the CLEO Redux and Sanny Builder mods and creations for the underlying API framework.*[cite: 4, 11]
