# 🌀 Circle Multiplier (Godot Plugin)

A powerful Godot editor plugin for generating **circular and elliptical arrays of 3D objects**.
Perfect for level designers who need to quickly arrange objects in structured or natural circular patterns — with **live preview**, **random variation**, and a **preset system**.

---

## 🚀 Core Features

### 🔹 Circle & Ellipse Generator

* Generates objects along a circle or ellipse
* Fully customizable **radius (X/Z)**, **start & end angle**, **object count**, and **offset**
* Option for **closed circle** or **open arc**
* Supports **vertical rotation (Y)** and **tilt angle** for complex formations

### 🔹 Live Preview

* Real-time preview directly inside the Godot editor
* Multiple display modes: Transparent, Wireframe, Solid, Outline
* Adjustable preview color, transparency, and line thickness
* Optional helper circles and axis guides

---

## 🎨 Advanced Features

* ✅ **Random rotation** (e.g. ±30°) for natural variation
* ✅ **Random scale** (e.g. ±20%) for organic effects
* ✅ **Progressive scaling** from start to end value
* ✅ **Positional jitter** for subtle randomness
* ✅ **Preset System**:

  * Save, load, and delete presets
  * Search and manage through an integrated GUI
  * Stored in `res://circle_generator_presets.cfg`

---

## ⚙️ How to Use

1. Enable the plugin under **Project > Project Settings > Plugins**
2. Select a 3D object in the editor (e.g. a `MeshInstance3D`)
3. Open **“Circle Multiplier”** from the top editor menu
4. Adjust the settings: radius, spacing, scaling, etc.
5. Use **Live Preview** to visualize changes in real time
6. Click **Generate** to create the array permanently in your scene

---

## 🧠 Technical Details

* Duplicates the selected `Node3D` along a circular or elliptical path
* Fully integrated **Undo/Redo** support via Godot’s editor system
* Settings and presets saved persistently within the project
* Written entirely in **GDScript**, compatible with **Godot 4.x**

---

## 💡 Use Cases

* Creating **arena layouts**, **rings**, or **tower formations**
* Building **decorative patterns**, **fences**, **lamps**, or **columns**
* Combine with the *Rectangle Multiplier* for modular level design workflows

---

## 📁 Installation

1. Copy the plugin folder into:
   `res://addons/circle_multiplier/`
2. Enable it in:
   `Project > Project Settings > Plugins`

---

## 🧰 Compatibility

* ✅ Godot 4.2+
* 🧱 Works with all `Node3D`-based objects
* 💾 Cross-platform support: Windows, Linux, macOS

---

## 📸 Preview 

<img width="2554" height="1387" alt="image" src="https://github.com/user-attachments/assets/5eacac4d-4006-45a1-a366-cad5cbfdc0ea" />



---

## ⚙️ License

Released under the **MIT License** — free to use, modify, and distribute.

---

## ✨ Author

**Developed by: iMrArevio
