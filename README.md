# 🎮 SKY RUNNER - Ultimate Edition

![Version](https://img.shields.io/badge/version-10.3-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Game](https://img.shields.io/badge/Type-Arcade_Game-brightgreen.svg)

**A complete arcade-style HTML5/JavaScript endless runner game inspired by classic Flash browser games!**

---

## 🌟 Overview

**Sky Runner** is a fully-featured endless runner game built entirely with vanilla HTML5, CSS3, and JavaScript. Jump, survive, and conquer as you dodge obstacles, collect points, utilize unique theme-based abilities, complete missions, fight bosses, and experience dynamic weather effects across 12 unique visual themes!

### 🏆 Jump, Survive, Conquer!

---

## ✨ Key Features

### 🎮 Core Gameplay
- **Endless Runner Mechanics**: Infinite procedural obstacle generation
- **Smooth Physics**: Gravity-based jumping with realistic acceleration
- **Double Jump System**: 5 charges with 10-second cooldown
- **Active Abilities**: 12 unique theme-specific skills (activated with E key)
- **Settings Menu**: Customizable music, sound effects, and FPS with volume controls
- **FPS Control**: Adjustable frame rate (30, 60, 90, 120, Unlimited)
- **Performance Optimization**: Smooth gameplay with optimized rendering
- **Multiple Obstacle Types**: Ground obstacles, aerial enemies, and traps
- **Boss Battles**: Epic boss fights every 200 points with laser and projectile attacks
- **Mission System**: 3 random objectives per run with bonus rewards
- **Combo System**: Chain obstacle dodges for bonus points
- **Progressive Difficulty**: Speed and spawn rate increase with score
- **High Score Tracking**: Persistent localStorage-based leaderboard
- **Sound System**: Theme-based background music and sound effects with volume controls
- **Auto-Play Music**: Music starts automatically when game loads (respects settings)

### 🎨 Visual Themes (12 Styles)
1. **✨ Normal** - Classic sky-blue aesthetic (Ability: Speed Boost)
2. **🌆 Cyberpunk** - Neon pink/cyan futuristic (Ability: Techno Dash)
3. **⚙️ Steampunk** - Industrial bronze/brass (Ability: Clock Work - Freeze)
4. **⚔️ Medieval** - Castle gray with gold accents (Ability: Purification - Invincibility)
5. **🌈 Rainbow** - Vibrant multi-color palette (Ability: Rainbow Shoot)
6. **🌙 Dark** - Monochrome shadowy theme (Ability: Shadow Step - Dash)
7. **🥚 Easter Egg** - Pastel spring colors (Ability: Egg Shield)
8. **⚡ The Glitch** - Corrupted digital effects (Ability: Error Bullets)
9. **👻 Horror** - Spooky dark red atmosphere (Ability: Blood Drain)
10. **🌿 Natural** - Natural green tones (Ability: Natural Disaster - Invincibility)
11. **✨ Fantasy** - Magical purple/pink (Ability: Fairy Wings - Fly)
12. **📦 Basic** - Minimalist grayscale (Passive: 2x Points Multiplier)

### 🎉 Surprise Events (3 Types - Balanced)
- **💎 Double Points** - 2x score multiplier
- **🔥 Giant Mode** - Player grows 1.8x size (warning given, reduced speed)
- **🐭 Tiny Mode** - Player shrinks to 0.5x size (warning given, increased speed)

### ⚡ Theme-Specific Active Abilities
Each theme has a unique ability activated with **E key**:
- **✨ Normal** - Speed Boost: 2x movement speed for 4 seconds
- **💨 Cyberpunk** - Techno Dash: Instant 100px dash forward (10s cooldown)
- **⏰ Steampunk** - Clock Work: Freeze all obstacles for 5 seconds
- **🛡️ Medieval** - Purification: Invincibility for 5 seconds
- **🌈 Rainbow** - Rainbow Shoot: Fire 1 bullet to destroy obstacles (10s cooldown)
- **� Dark** - Shadow Step: 100px dash, can use 2 times (10s cooldown)
- **🥚 Easter** - Egg Shield: Block 1 collision for 10 seconds
- **⚠️ Glitch** - Error Bullet: Single-use activation shoots 3 bullets
- **🩸 Horror** - Blood Drain: Toggle mode - consume 1 pt/s for invincibility
- **🌪️ Natural** - Natural Disaster: Grants invincibility for 5 seconds
- **🧚 Fantasy** - Fairy Wings: Fly freely for 5s with 2s invincibility (12s cooldown)
- **💎 Basic** - Passive 2x Points multiplier (no active ability)

### 🌦️ Dynamic Weather System (4 Types)
- **🌧️ Rain** - Animated falling rain
- **❄️ Snowfall** - Gentle floating snowflakes
- **💨 Strong Winds** - Horizontal wind streaks
- **⛈️ Thunderstorm** - Heavy rain + lightning flashes (reduced frequency)

**Weather adapts to themes** (e.g., Horror gets storms, Fantasy gets snow)
**Event timing**: 20-40s intervals, 6-10s active duration
**Weather timing**: 25-50s intervals, 30s active duration

### 🎨 Visual Effects
- **Particle System**: Dynamic particles for jumps, landings, combos
- **Squash & Stretch**: Character animation on jumps/landings
- **Decorative Clouds**: 10 animated background clouds
- **Flying Objects**: Theme-specific decorations (birds, drones, dragons, fairies, etc.)
- **Weather Particles**: Real-time weather visual effects
- **Smooth Animations**: 60 FPS with requestAnimationFrame
- **Projectile System**: Bullets and laser attacks for abilities and bosses

### 🎯 Advanced Features
- **Mission System**: 3 random objectives per run with bonus point rewards
- **Boss Battles**: Epic boss fights every 200 points with health bars
- **Multiple Obstacle Types**: Ground obstacles, aerial enemies (3 heights), and traps
- **Sound System**: Theme-based background music and comprehensive SFX library
- **Active Abilities**: 12 unique theme-specific skills with cooldowns and toggle modes

### 🎯 Game Modes
- **Main Menu** - Feature showcase with play/exit options
- **Playing Mode** - Active gameplay
- **Paused Mode** - ESC to pause/resume
- **Game Over** - Score display with restart/menu options

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| **SPACE** / **Click** | Jump (first jump) |
| **SPACE** / **Click** (in air) | Double Jump (uses 1 charge) |
| **E** | Activate theme-specific ability |
| **ESC** | Pause / Resume |
| **R** | Restart Game |
| **Arrow Keys** | Adjust volume in settings (when focused on sliders) |

### 📱 Mobile Support
- **Touch/Tap** - Jump (works on mobile devices)

---

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge, Safari)
- No installation required!

### How to Play

1. **Open the game**:
   ```bash
   # Simply open the file in your browser
   arcade_game.html
   ```

2. **Or double-click** `arcade_game.html` in your file explorer

3. **Start playing**:
   - Click **▶️ PLAY GAME** button
   - Use **SPACE** or **Click** to jump
   - Avoid obstacles and collect points!

---

## 📁 Project Structure

```
Web_App_Testing/
├── arcade_game.html    # Main game file (self-contained)
└── README.md          # This file
```

**Single File Architecture**: The entire game is contained in one HTML file with embedded CSS and JavaScript - no external dependencies!

---

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas** - 2400x1150 pixel game rendering
- **Vanilla JavaScript (ES6)** - Game logic and physics
- **CSS3** - UI styling and animations
- **LocalStorage API** - High score persistence
- **Web Audio API** - Sound system with theme-based music and SFX

### Architecture
```javascript
// Main Classes
- Player          // 70x70px character with physics and abilities
- Obstacle        // Procedurally generated obstacles (ground, aerial, traps)
- Boss            // Epic boss fights with health and attack patterns
- Projectile      // Bullets and lasers for abilities and boss attacks
- Particle        // Visual effect particles
- Cloud           // Background decoration
- FlyingObject    // Theme-based flying decorations
- SoundManager    // Audio system with music and SFX

// Game Systems
- Physics Engine  // Gravity, collision detection
- Event System    // 3 balanced surprise events with RNG timing
- Weather System  // 4 weather types with style theming
- Mission System  // 3 random objectives with bonus rewards
- Ability System  // 12 unique theme-specific active skills
- Style Manager   // 12 theme configurations
- State Machine   // Menu/Playing/Paused/GameOver
- Boss System     // Periodic boss fights every 200 points
```

### Performance
- **60 FPS** target frame rate
- **Optimized rendering** with efficient particle cleanup
- **Responsive canvas** scaling
- **Smooth animations** using requestAnimationFrame

---

## 📊 Game Statistics

### Canvas Size Evolution
- v1.0-2.0: 800x400px
- v2.0-3.0: 1200x600px
- v3.0-4.0: 1600x700px
- v4.0-7.1: 2000x800px
- v7.1: 2400x900px
- v7.2-8.0: 2400x1000px
- v9.0+: **2400x1150px** ⭐

### Feature Count
- **12** Visual Themes (each with unique abilities)
- **3** Balanced Surprise Events
- **4** Weather Types
- **10** Background Clouds
- **8** Flying Objects
- **5** Game States
- **3** Mission Objectives per run
- **3** Obstacle Types (ground, aerial, traps)
- **100+** Particle effects simultaneously

---

## 📜 Version History

### v10.3 - "Performance & Optimization" (Current)
- ⚡ **FPS Optimization**: Major performance improvements throughout the game for smoother gameplay
- 🎯 **FPS Selector**: Added FPS control in Settings menu (30, 60, 90, 120, Unlimited)
- 🎮 **Optimized Game Loop**: Delta time tracking for consistent frame pacing
- 💾 **Persistent FPS Settings**: FPS preference automatically saved to localStorage
- 🔧 **Enhanced Rendering**: Better loop optimization for improved performance
- 🚫 **Balance Update**: Removed "Freeze" event from the game
- ✨ **Performance Boost**: Improved obstacle update logic with reverse iteration
- 📊 **Default Settings**: 60 FPS set as recommended default

### v10.2 - "Audio Control & Enhancement"
- ⚙️ **Settings Menu**: Added comprehensive settings accessible from Main Menu and Pause Menu
- 🎵 **Music Control**: Volume slider (0-100%) and on/off toggle
- 🔊 **Sound Effects Control**: Independent volume slider and toggle
- 💾 **Persistent Settings**: All settings automatically saved to localStorage
- 🎹 **Keyboard Controls**: Arrow keys to adjust volume in settings menu
- 🎶 **Auto-Play Music**: Music now starts automatically on game load (respects user settings)
- 🎮 **Enhanced Audio System**: Better volume management and user experience
- ✨ **Visual Feedback**: Improved UI for settings changes

### v10.1 - "Balance & Refinement"
- ⚖️ **Major Ability Rebalancing**:
  - 🌈 Rainbow: Nerfed to 1 bullet (from 2), increased cooldown to 10s
  - 👤 Dark: Reworked Shadow Step - Now 100px dash, can use 2 times, 10s cooldown
  - 💨 Cyberpunk: Added 10s cooldown to Techno Dash
  - ⏰ Steampunk: Fixed Clock Work to exactly match Freeze mechanics
  - ⚠️ Glitch: Removed toggle mode - Error Bullets now single-use (shoots 3 bullets)
  - 🌪️ Natural: Reworked - Now grants 5s invincibility instead of weather
  - 🧚 Fantasy: Increased Fairy Wings to 5s duration + 2s invincibility, 12s cooldown
  - 💎 Basic: Fixed passive 2x points multiplier
- 🎮 **Event System Overhaul**: Removed 3 events (Freeze, Slow Motion, Speed Boost)
- 🎯 Only 3 balanced events remain: Double Points, Giant Mode, Tiny Mode
- ✨ Updated ability display UI to reflect new mechanics

### v10.0 - "Ultimate Skill System"
- ⚡ **Complete Ability System**: 12 unique theme-specific skills
  - ✨ Normal: Speed Boost (2x speed, 4s)
  - 💨 Cyberpunk: Techno Dash (300px instant dash)
  - ⏰ Steampunk: Clock Work (Freeze obstacles, 5s)
  - 🛡️ Medieval: Purification (Invincibility, 5s)
  - 🌈 Rainbow: Rainbow Shoot (2 bullets)
  - 👤 Dark: Shadow Step (Teleport past 2 obstacles)
  - 🥚 Easter: Egg Shield (Block 1 collision, 10s)
  - ⚠️ Glitch: Error Bullet (Toggle auto-fire, 5-10 pts/shot)
  - 🩸 Horror: Blood Drain (Toggle invincibility, 1 pt/s cost)
  - 🌪️ Natural: Natural Disaster (Trigger all 4 weather types)
  - 🧚 Fantasy: Fairy Wings (Free flight with bounds)
  - 💎 Basic: 2x Points (Passive ability)
- 🎯 Added Projectile class for shooting mechanics
- 🎮 Toggle abilities for Glitch/Horror themes (E key on/off)
- 🛡️ Enhanced collision detection for shields and teleportation
- 💰 Point multipliers stack (Basic + Double Points = 4x)

### v9.0 - "UX Revolution & Balance Overhaul"
- 🎨 Redesigned Version History modal with professional layout
- 📐 Increased canvas height to **1150px** for improved vertical space
- 🎯 Relocated Missions display to top-right corner (below Score/Combo)
- 🔥 Giant Mode now reduces player speed for strategic gameplay
- 🐭 Tiny Mode now increases player speed for enhanced mobility
- 🌈 Rainbow trail effect integrated into Fantasy theme
- 🎨 Theme selection now restricted to main menu only
- 🌿 Renamed "Eco-Friendly" theme to "Natural"
- 🌦️ Removed Sunny weather; renamed "Rain Storm" to "Rain"
- ⛈️ Reduced Thunderstorm lightning flash frequency
- 💨 Enhanced Strong Wind effects
- ⏰ Increased event duration (20-40s intervals, 6-10s active)
- 🌤️ Increased weather duration (25-50s intervals, 30s active)
- 🎲 Enhanced RNG system for varied timing
- ⚖️ Removed Invincible and Rainbow Trail events

### v8.0 - "Ultimate Gameplay Overhaul"
- 🎵 **Sound System**: Theme-based background music and SFX library
- ⚡ **Active Abilities**: Style-based abilities (E key) - Glitch Dash, Clockwork Gear, Petrify, Fairy Wings
- 🦇 **Aerial Obstacles**: Flying enemies at different heights
- 💀 **Trap Obstacles**: Deduct points and reset combo
- 🐉 **Boss Battles**: Periodic fights every 200 points with laser and projectile attacks
- 🎯 **Mission System**: 3 random objectives per run with bonus rewards
- ⚖️ Balanced random events with weighted selection
- 🎮 Increased event intervals (15-30s) for fairer gameplay

### v7.2 - "Polish & Expansion"
- ⏰ Extended weather duration to 20 seconds
- 📺 Expanded canvas to 2400x1000 pixels
- ✨ Fixed "Ultimate Edition" subtitle formatting
- 🎨 Improved menu visual hierarchy

### v7.1 - "Extended Experience"
- ⏰ Extended weather duration to 15 seconds
- 🎨 Style-based weather system
- 📜 Scrollable style theme menu
- 📺 Canvas expanded to 2400x900
- 🦘 Increased jump distance

### v7.0 - "Weather & Fantasy"
- 🌦️ Dynamic weather system (5 types)
- ☁️ Enhanced clouds + flying objects
- ✨ Fantasy theme added
- 🐛 Fixed Giant/Tiny mode bugs

### v6.2 - "Freeze Fix"
- 🐛 Fixed freeze mode inheritance bug

### v6.1 - "Bug Fixes & Warnings"
- ⚠️ Added warnings for Giant/Tiny modes
- 🐛 Fixed event notification persistence

### v6.0 - "Enhanced Experience"
- ⏰ RNG event timing system
- 👻 Horror + 🌿 Eco-Friendly themes
- 🛠️ Fixed UI flickering

### v5.2 - "Polish & Fixes"
- 🐛 Fixed obstacle speed bugs
- 🏠 Added Main Menu button to pause

### v5.1 - "Medieval Mayhem"
- ⚔️ Medieval theme
- 🎉 4 new events (Giant, Tiny, Freeze, Rainbow)

### v5.0 - "The Glitch Update"
- ⚡ The Glitch theme
- 🦘 Double Jump system
- 📋 Version history modal

### v4.0 - "Style Revolution"
- 🎨 7 visual styles
- ⏸️ Pause/Resume system
- 🎉 Surprise events (4 types)
- 🏅 Combo tracking

### v3.0 - "Big Screen Expansion"
- 📺 Expanded to 2000x800 pixels
- 🖼️ Decorative border

### v2.0 - "Smooth Operator"
- ✨ Advanced particle system
- 🎬 Squash & stretch animations
- 🎮 Reduced difficulty

### v1.0 - "Genesis"
- 🎮 Initial release
- 🦘 Basic jump mechanics
- 🚧 Obstacle spawning
- 💯 Scoring system

---

## 🎯 Game Features Checklist

### ✅ Completed Features
- [x] Endless runner gameplay
- [x] Smooth physics and controls
- [x] Double jump system (5 charges, 10s cooldown)
- [x] 12 unique visual style themes
- [x] 3 balanced surprise events with RNG timing
- [x] 12 theme-specific active abilities
- [x] Sound system with music and SFX
- [x] Mission system with 3 objectives per run
- [x] Boss battles every 200 points
- [x] Multiple obstacle types (ground, aerial, traps)
- [x] 4 dynamic weather types
- [x] Style-based weather theming
- [x] Particle effects system
- [x] Combo tracking
- [x] High score persistence
- [x] Pause/Resume functionality
- [x] Quick restart (R key)
- [x] Main menu system
- [x] Game over screen
- [x] Version history modal
- [x] Mobile touch support
- [x] Responsive canvas
- [x] Theme-specific flying objects
- [x] Event warnings (Giant/Tiny modes)
- [x] Scrollable style menu

---

## 🎨 Screenshots

### Main Menu
- Features showcase with 4 feature badges
- Play Game / Exit buttons
- Version History access

### Gameplay
- 2400x1150 pixel canvas
- Real-time score display
- Double jump counter
- Active ability status (E key)
- Mission objectives display (top right)
- Event notifications (top center)
- Weather notifications (below events)
- Combo display (top right)
- Boss health bar (during boss fights)
- Style switcher (main menu only)

### Themes Preview
Each of the 12 themes has unique:
- Sky gradient colors
- Player character colors
- Obstacle colors
- Ground/grass colors
- Particle effect colors
- Flying object types
- **Active abilities** (or passive for Basic theme)

---

## 🏗️ Development Notes

### Code Quality
- **Clean Architecture**: Organized class-based structure
- **Single Responsibility**: Each class handles one aspect
- **No External Dependencies**: Pure vanilla JavaScript
- **Well Commented**: Clear inline documentation
- **Maintainable**: Easy to extend with new features

### Design Patterns Used
- **State Machine**: Game state management
- **Factory Pattern**: Particle/obstacle creation
- **Observer Pattern**: Event notifications
- **Strategy Pattern**: Theme configurations

---

## 🤝 Contributing

This is a personal game project, but feel free to:
- Fork and modify for your own use
- Learn from the code structure
- Suggest improvements

---

## 📄 License

This is a personal project created for educational and entertainment purposes.

---

## 🎮 Credits

**Game Design & Development**: Solo project  
**Engine**: Vanilla HTML5/JavaScript  
**Inspiration**: Classic Flash arcade games (Flappy Bird, Chrome Dino)  
**Version**: 10.3 "Performance & Optimization"  
**Last Updated**: 2025

---

## 🔗 Quick Links

- **Game File**: `arcade_game.html`
- **Current Version**: 10.3
- **Total Versions**: 19 major releases
- **Lines of Code**: 4700+
- **Development Time**: Multiple iterations

---

## 🎯 Gameplay Tips

1. **Optimize Performance**: Adjust FPS in Settings (⚙️) - 60 FPS recommended for best balance
2. **Adjust Audio Settings**: Use Settings menu to customize music and sound volume
3. **Master Double Jump**: Save charges for tight situations
4. **Use Theme Abilities**: Press E to activate powerful theme-specific skills
5. **Watch Event Warnings**: Giant/Tiny modes give 2-3 second warnings
6. **Complete Missions**: Earn bonus points by finishing 3 random objectives
7. **Fight Bosses Smart**: Dodge lasers and projectiles, aim for weak points
8. **Avoid Traps**: They deduct points and reset your combo streak
9. **Chain Combos**: Pass 3+ obstacles in a row for combo bonuses
10. **Try All Themes**: Each has unique abilities and visual appeal
11. **Weather Awareness**: Weather changes based on current theme
12. **Practice Timing**: Jump distance is generous - use it!
13. **Save Ability Cooldowns**: Use abilities strategically during tough sections
14. **Customize Experience**: Adjust FPS, music, and sound to your preference in settings

---

## 📞 Support

For issues or questions:
- Check the **Version History** modal in-game
- Review the code comments in `arcade_game.html`
- Test in a modern browser (Chrome/Firefox recommended)

---

**🎮 Ready to Play? Open `arcade_game.html` and start your Sky Runner adventure!**

---

*Made with ❤️ using vanilla HTML5, CSS3, and JavaScript*
