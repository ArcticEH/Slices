# Slices - Window Management Made Simple

A lightweight, native macOS window manager that helps you organize your workspace with customizable layouts and keyboard shortcuts.

## ✨ Core Features

- **Visual Layout Editor**: Create and adjust window zones with an intuitive drag-and-drop interface. Just like controlling real macOS windows.
- **Drag-to-Snap**: Hold Shift while dragging any window to see and snap to your layouts. Press Tab to cycle through overlapping zones.
- **Zone Hotkeys**: Use keyboard shortcuts to quickly move the focused window to a specific zone.
- **Menu Bar Access**: Quickly switch layouts and snap windows to zones directly from the menu bar.
- **Multi-Monitor Support**: Fully supports multiple displays with unique layouts for each screen.
- **Lightweight & Native**: Built with SwiftUI for a seamless macOS experience.

## 🚀 Getting Started

### Installation

1. Download the latest `Slices.dmg` from the [Releases page](#)
2. Open the DMG and drag Slices to your Applications folder
3. Launch Slices from your Applications folder

### First-Time Setup

1. **Grant Permissions**
   - Slices requires Accessibility permissions to manage windows
   - You'll be prompted to open System Settings
   - Find "Slices" in the list and enable it

2. **Open the Layout Editor**
   - Click the Slices icon in your menu bar
   - An (empty) initial layout is created
        - Multiple layouts are a Power User Feature
   - Select "Show Editor"

## 🖥️ Creating Layouts

### Add & Edit Zones
- Click "Add Zone" to create a new zone
- Drag to position and resize zones as needed
- Right-click a zone to split it vertically or horizontally

### Save Your Layout
- Click "Save" when you're happy with your layout
- Create multiple layouts for different workflows (Power User Feature)

## ⚡ Using Slices

### Basic Usage
1. Click and start dragging any window
2. Press and hold `Shift` to see your zones
3. Drag to highlight your desired zone
4. Release to snap the window into place

### Power User Mode - Advanced Features
- **Multiple Layouts**: Save different layouts for various tasks (Coding, Design, etc.)
- **Custom Zone Hotkeys**: Customize the modifier keys used for all hotkeys
- **Custom Zone Names**: Name your zones for better organization

> See ⚙️ **Settings** → **Activation** in the app for more information.

## 🎯 Essential Controls

### Layout Editor
| Action | Control |
|--------|----------|
| Open Layout Editor | Menu bar icon → "Show Editor" |
| Add new zone | "Add Zone" button in editor |
| Resize zone | Drag zone edges/corners |
| Move zone | Click and drag zone |
| Split zone | Right-click zone → Split |

### Window Management
| Action | Control |
|--------|----------|
| Snap window to zone | `Shift` + Drag window |
| Cycle through zones | `Tab` (while dragging with `Shift`) |
| Toggle zone overlay | Hold/Release `Shift` (while dragging) |
| Snap with hotkey (Focused Window) | Your Modifiers + Zone Key (e.g., 1, 2) |
| Snap with menu bar buttons (Focused Window) | Tap Zone Button in Menu Bar View |

> 💡 **Tip**: Customize hotkey modifiers and the "Show Editor" shortcut in **Settings** → **Advanced** (Power User Feature).

## 📦 Requirements

- macOS 15.0 or later
- Apple Silicon or Intel processor

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.