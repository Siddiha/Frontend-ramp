# Frontend-Ramp 

A 2D platformer game built with the **Godot Engine**.

<img width="400" height="451" alt="Game Screenshot" src="https://github.com/user-attachments/assets/146af47a-2f00-4afa-9e6e-20a5706dba15" />

## 📁 Project Structure

```
Frontend-ramp/
├── scenes/                 # Game scenes (.tscn files)
│   ├── main.tscn          # Main game scene
│   └── main_character.tscn # Player character scene
├── assets/                # Game assets
│   └── images/            # Image and sprite files
│       ├── 01.png
│       ├── icon.svg
│       ├── Tilemap_color1.png
│       └── Water Background color.png
├── scripts/               # GDScript files (game logic)
├── project.godot          # Godot project configuration
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Godot Engine (4.x or later)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Siddiha/Frontend-ramp.git
   cd Frontend-ramp
   ```

2. Open the project in Godot Engine:
   - Launch Godot
   - Click "Open Project"
   - Select the `project.godot` file

3. Run the game:
   - Press `F5` or click the "Play" button

## 📝 Features
- 2D platformer gameplay
- Character movement and animation
- Interactive tilemap environment
- Water/background elements

## 🎮 How to Play

### Objective
Navigate through the level, overcome obstacles, and reach the goal!

### Controls
| Key | Action |
|-----|--------|
| **Arrow Keys** ← → | Move Left/Right |
| **Space** | Jump |
| **W/A/D** | Alternative Movement |

### Gameplay Tips
- Use the tilemap platforms to navigate across levels
- Time your jumps carefully to avoid falling
- Watch out for water obstacles
- Collect items for extra points (if implemented)

## 🛠️ Development

### Project Organization
- **Scenes** are organized in the `scenes/` folder
- **Game assets** (images/sprites) are in `assets/images/`
- Add your **GDScript** files to the `scripts/` folder

### Adding New Features
1. Create scene files in `scenes/`
2. Create scripts in `scripts/`
3. Add assets to `assets/images/`
4. Test with `F5` in Godot

## 🗺️ Roadmap

- [ ] Complete level 1 implementation
- [ ] Add sound effects and background music
- [ ] Implement enemy AI
- [ ] Add health/lives system
- [ ] Create level progression
- [ ] Add pause menu
- [ ] Implement high score system
- [ ] Mobile controls support

## ⚙️ Troubleshooting

### Game won't start
- Ensure Godot is the correct version (4.x or later)
- Check that `project.godot` exists in the root directory
- Verify all asset paths are correct

### Scene not loading
- Check that `.tscn` files are in the `scenes/` folder
- Verify there are no broken node references
- Reload the scene in Godot editor

### Missing textures
- Confirm all image files are in `assets/images/`
- Check the `.import` files are present
- Re-import assets if needed in Godot

## 🐛 Known Issues

- Water collision detection may need refinement
- Some sprite animations may need optimization
- Performance testing needed for larger levels

## 📦 Assets & Credits

### Images Used
- `01.png` - Tilemap sprite
- `icon.svg` - Game icon
- `Tilemap_color1.png` - Level tileset
- `Water Background color.png` - Background/water element

### Tools
- Built with **Godot Engine** (Free & Open Source)
- Developed for 2D game development

## 👨‍💻 Author & Contact

**Project:** Frontend-Ramp (Learning Project)
**Repository:** [GitHub - Siddiha/Frontend-ramp](https://github.com/Siddiha/Frontend-ramp)

Feel free to fork, contribute, or use this as a learning resource!

## 📄 License
MIT License - Feel free to use this project for learning and personal projects!

---

**Made with Godot Game Engine** 💙
