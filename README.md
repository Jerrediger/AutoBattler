# AutoBattler Game

A Unity-based auto-battler game where players build teams of characters, equip them with items, and watch them battle automatically.

## Project Overview

This project is an auto-battler game where players can:
- Create and customize characters with unique abilities
- Equip characters with items that modify their stats
- Build synergistic teams of characters
- Watch battles unfold automatically with strategic positioning
- Progress through a campaign or compete against other players

## Project Structure

```
Assets/
├── Project/
│   ├── Scripts/
│   │   ├── Core/           # Core game systems and data structures
│   │   │   ├── Character/  # Character-related scripts
│   │   │   │   ├── Character.cs           # Base character class
│   │   │   │   ├── CharacterStats.cs      # Character statistics
│   │   │   │   └── CharacterAbility.cs    # Character abilities
│   │   │   ├── Combat/     # Combat system scripts
│   │   │   │   ├── BattleManager.cs       # Manages battle state
│   │   │   │   ├── BattleUnit.cs          # Battle unit behavior
│   │   │   │   └── AbilitySystem.cs       # Ability execution system
│   │   │   └── Items/      # Item system scripts
│   │   │       ├── Item.cs                # Base item class
│   │   │       ├── Equipment.cs           # Equipment items
│   │   │       └── ItemEffect.cs          # Item effects and modifiers
│   │   └── UI/            # User interface components
│   │       ├── Battle/     # Battle UI elements
│   │       │   ├── BattleHUD.cs           # Main battle interface
│   │       │   ├── HealthBar.cs           # Health display
│   │       │   └── AbilityUI.cs           # Ability cooldown display
│   │       ├── Character/  # Character UI elements
│   │       │   ├── CharacterPortrait.cs   # Character display
│   │       │   ├── StatsDisplay.cs        # Stats visualization
│   │       │   └── LevelProgress.cs       # Level and XP display
│   │       └── Items/      # Item UI elements
│   │           ├── InventoryUI.cs         # Inventory management
│   │           ├── EquipmentSlots.cs      # Equipment interface
│   │           └── ItemTooltip.cs         # Item information display
│   ├── Prefabs/          # Reusable game objects
│   ├── Scenes/           # Game scenes
│   └── Resources/        # Game assets
```

## Development Roadmap

### Phase 1: Core Systems
- [ ] Character system implementation
  - [ ] Base character class
  - [ ] Stats system
  - [ ] Level progression
- [ ] Combat system foundation
  - [ ] Battle manager
  - [ ] Basic ability system
  - [ ] Damage calculation
- [ ] Item system
  - [ ] Equipment slots
  - [ ] Stat modifiers
  - [ ] Item effects

### Phase 2: UI and Interaction
- [ ] Character UI
  - [ ] Portrait display
  - [ ] Stats visualization
  - [ ] Level progress
- [ ] Inventory system
  - [ ] Equipment management
  - [ ] Item tooltips
  - [ ] Drag and drop
- [ ] Battle UI
  - [ ] Health bars
  - [ ] Ability indicators
  - [ ] Battle log

### Phase 3: Gameplay Features
- [ ] Character abilities
  - [ ] Ability selection
  - [ ] Cooldown system
  - [ ] Effect visualization
- [ ] Team building
  - [ ] Character synergies
  - [ ] Team composition
  - [ ] Position management
- [ ] Progression system
  - [ ] Experience gain
  - [ ] Level rewards
  - [ ] Character upgrades

### Phase 4: Polish and Content
- [ ] Visual effects
  - [ ] Ability animations
  - [ ] Hit effects
  - [ ] Status effects
- [ ] Sound system
  - [ ] Battle sounds
  - [ ] UI feedback
  - [ ] Background music
- [ ] Game modes
  - [ ] Campaign mode
  - [ ] Versus mode
  - [ ] Practice mode

## Controls

- Left-click: Select/Interact
- Right-click: Context menu
- Drag and drop: Move items/characters
- Space: Pause/Resume battle
- ESC: Open menu

## Dependencies

- Unity 2022.3.0f1 or later
- TextMeshPro
- Universal Render Pipeline (URP)

## Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/Jerrediger/AutoBattler.git
   ```

2. Open the project in Unity
   - Open Unity Hub
   - Click "Add"
   - Select the cloned AutoBattler folder
   - Open with Unity 2022.3.0f1 or later

3. Open the Main scene
   - Navigate to Assets/Scenes
   - Double-click Main.unity

4. Press Play to test the current functionality

## Git Workflow

### Making Changes
```bash
git pull                    # Get latest changes
# Make your changes...
git add .                   # Stage changes
git commit -m "Description" # Commit changes
git push                    # Push to GitHub
```

### Working on New Computer
```bash
git clone https://github.com/Jerrediger/AutoBattler.git
cd AutoBattler
git pull                    # Get latest changes
# Make your changes...
git add .
git commit -m "Description"
git push
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 