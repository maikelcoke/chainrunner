# Chain Runner 2079 - Content Creation Guide

Thank you for contributing to **Chain Runner 2079**! Your creativity helps build the dystopian world of Chain Runner. The game will be free-to-play and relies on community support. 

---

## 🛠 Prerequisites

To create buildings for the game, you will need **Blockbench** (a free, open-source 3D modeling tool).

* **Download Blockbench:** [https://www.blockbench.net/](https://www.blockbench.net/)
* **Download the Building Template:** [Insert Template URL Here]

---

## 🏗 Modeling & Naming Conventions

To ensure your models are recognized correctly by the game engine, please follow these naming conventions for your elements within Blockbench:

### 1. Static Building Parts
Use the suffix `_Mat_Base` for all solid, non-emissive structures.
* **Format:** `XXX_Mat_Base` (Replace `XXX` with any name, e.g., `Wall_Mat_Base`)

### 2. Neon Advertisements (Emissive)
There are three specific colors available for neon signs. Use the suffix `_Ad_(COLOR)`:
* **Pink:** `XXX_Ad_Pink`
* **Blue:** `XXX_Ad_Blue`
* **Yellow:** `XXX_Ad_Yellow`

**Example Structure:**
* `Building_Mat_Base`
* `Vent_Mat_Base`
* `Side_Ad_Pink`
* `Door_Ad_Blue`
* `Top_Ad_Yellow`

*Note: You are free to modify, expand, or completely redesign the template as long as the naming conventions are followed.*

---

## 📤 Export Settings

When you are ready to export your model from Blockbench, use the **glTF Export** (*File -> Export -> glTF Export*) and apply these settings:

1.  **Format:** ASCII (glTF) - *Standard*
2.  **Model Export Scale:** `2` (Adjust this value if you intend to make significantly larger or smaller buildings).
3.  **Includes:** * **Embed Textures:** OFF
    * **Export Groups as Armature:** OFF
    * **Export Animations:** OFF
    * *We only require the Mesh data.*

---

## 📺 Testing in the 3D Preview Client

You can test your model instantly in the Chain Runner 3D Preview Client:

1.  Open the **3D Preview Client**.
2.  Click the **"Open Dir"** button to open the local model folder.
3.  Export/Overwrite your model as `model.gltf` into that folder.
4.  Back in the Client, click **"Refresh"** to load your new model.

---

## 💬 Support & Community

If you have questions or run into issues, join our community:

* **Discord:** [https://discord.gg/VayJJVRja7](https://discord.gg/VayJJVRja7)
* **Email:** [chainrunner@tycoono.me](mailto:chainrunner@tycoono.me)

### ☕ Support the Project
Chain Runner 2079 is a free-to-play passion project. If you'd like to support the development, consider a small contribution:
[Support on Ko-fi](https://ko-fi.com/chainrunner2079)

---
*Created by Tycoopolis Development Team 2026*
