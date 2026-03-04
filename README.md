# 🎮 SKY RUNNER - Ultimate Edition

![Version](https://img.shields.io/badge/version-13.0-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Game](https://img.shields.io/badge/Type-Arcade_Game-brightgreen.svg)

**A complete arcade-style HTML5/JavaScript endless runner game inspired by classic Flash browser games!**

---

## 🌟 Overview

**Sky Runner** is a fully-featured endless runner game built entirely with vanilla HTML5, CSS3, and JavaScript. Jump, survive, and conquer as you dodge obstacles, collect points, utilize unique theme-based abilities, complete missions, fight bosses, experience dynamic weather effects, face challenging screen events, and enjoy stunning procedural VFX (style-specific procedural generation with Strategy pattern for 8 themes, parallax backgrounds, screen shake, hit-stop, neon glow, chromatic aberration) across 12 unique visual themes — all rendered 100% procedurally with zero external assets!

### 🏆 Jump, Survive, Conquer!

---

## ✨ Key Features

### 🎮 Core Gameplay
- **Loading Screen**: Beautiful animated loading screen with progress tracking and performance optimization
- **Endless Runner Mechanics**: Infinite procedural obstacle generation
- **Smooth Physics**: Gravity-based jumping with realistic acceleration
- **Double Jump System**: 5 charges with 10-second cooldown
- **Active Abilities**: 12 unique theme-specific skills (activated with E key)
- **Settings Menu**: Customizable music, sound effects, and FPS with volume controls
- **FPS Control**: Adjustable frame rate (30, 60, 90, 120, Unlimited)
- **Performance Optimization**: Smooth gameplay with optimized rendering and adaptive loading
- **Multiple Obstacle Types**: Ground obstacles, aerial enemies, and traps
- **Boss Battles**: Epic boss fights every 200 points with laser and projectile attacks
- **Mission System**: 3 random objectives per run with bonus rewards and failure validation
- **Screen Events (Enhanced v11.1)**: Post-50 point visual challenge events with countdown warnings and global cooldown
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

### � Screen Events System (NEW in v11.0)
Advanced visual challenge events that activate **only after scoring 50 points**:

#### Event Types:
- **🌑 The Dark Descends**
  - Gradual screen darkening to 10% brightness over 2 seconds
  - Stays dark for 3 seconds total
  - Smooth recovery to normal over 1.5 seconds
  - Total duration: ~4.5 seconds
  
- **⚡ Flashbang**
  - Instant white screen flash at 100% brightness
  - Lasts for 1.5 seconds
  - Gradual fade recovery over 1.5 seconds
  - Total duration: ~3 seconds

#### Event Mechanics:
- **⏰ Countdown Warning (NEW v11.1)**: 3-second countdown (3...2...1...) displays before event triggers
- **⚠️ Visual Warning**: Red warning box with gold border appears center-screen during countdown
- **🎭 Dramatic Effect**: Each number pulses and scales with smooth animation
- **Activation Requirement**: Score must be ≥ 50 points
- **Global Cooldown**: 60 seconds shared between both events
- **Random Timing**: Events trigger randomly every 30-60 seconds (after cooldown)
- **No Overlap**: Only one screen event can be active at a time
- **Challenge Factor**: Tests player reaction and adaptation skills
- **Fair Warning**: Countdown gives players time to prepare for the effect

### 🎯 Advanced Mission System (Enhanced in v11.0)
Dynamic mission system with **success tracking and failure validation**:

#### Mission Features:
- **3 Random Objectives** per game session
- **Bonus Rewards**: +10 points per completed mission
- **Visual Feedback**: ✓ for completed, ○ for active, ✗ for failed
- **Real-time Validation**: Continuous checking of mission conditions

#### Mission Types:
1. **Combo Challenges** - Achieve 10x or 15x combo
2. **Score Milestones** - Reach 50 or 100 points
3. **Weather Survival** - Survive 2 weather events
4. **No Double Jump** - Score 20 points without using double jump
   - **Failure Condition**: Using double jump before 20 points
   - **Visual Indicator**: Text turns gray with strikethrough on failure
5. **Ability Master** - Use special ability 3 times
6. **Aerial Avoidance** - Dodge 10 aerial obstacles

#### Mission Failure System:
- **Smart Validation**: AI continuously monitors failure conditions
- **Instant Feedback**: Notification appears when mission fails
- **UI Updates**: Failed missions show with ✗ and gray strikethrough text
- **No Retry**: Failed missions cannot be recovered in the same run

### 🎨 Visual Effects

#### Style-Specific Procedural Renderers (12 Themes)
| Theme | Sky | Mountains/Mid | Ground | Obstacles | Aerials | Weather |
|-------|-----|---------------|--------|-----------|---------|---------|
| **✨ Normal** | Glowing sun with animated rays, fluffy arc clouds | 3-layer rolling mountains | Earthy ground with grass & pebbles | Jagged moss-covered rocks | Flapping birds with beak & tail | Soft blue rain & twinkling snow |
| **🌆 Cyberpunk** | Retrowave sun with horizontal slices | Neon-window skyscrapers (cyan/magenta) | Perspective grid with glow edge | Laser fence pillars with bloom | Angular diamond drones with LEDs | Acid rain (neon glow) & glitch snow |
| **⚙️ Steampunk** | Rotating gears with teeth & hub | Rising steam plumes, chimney skyline | Metal plates with rivets & track rail | Brass pipes with flanges & valve wheel | Hot air balloons with basket | Smog/soot particles |
| **🏰 Medieval** | Gothic castle towers with crenellations | Low-lying fog with drifting wisps | Cobblestone ground | Wooden X-barricades with iron spikes | Leathery bats with red eyes | Heavy dark rain & lightning |
| **🌈 Rainbow** | Flowing sine waves (7-color spectrum, additive blend) | Prismatic light beams | Rainbow gradient with HSL sparkle dots | Crystalline spikes with rainbow gradient | Rotating diamond prisms with HSL aura | Confetti rectangles |
| **🌙 Dark** | Dead twisted tree silhouettes with branching | Near-black jagged horizon, dense fog & wisps | Pitch-black with faint cracks | Pure-black thorn clusters with eerie outline | Shadowy wraiths with glowing white eyes | Falling grey ash |
| **🥚 Easter** | Rolling mint-green hills + giant Easter eggs (zigzag/polka patterns) | Small 5-petal flowers | Pastel-green gradient with grass tufts & daisies | Chocolate bunnies & cracked eggshells | Yellow chicks & painted eggs with bands | Spring petals (bezier teardrops) |
| **⚡ Glitch** | Shifting barcode bars with chromatic aberration (screen composite) | Fragmented data blocks (magenta/green/cyan) | Dark with corrupted color stripes & pixel edge | Data blocks with bitten chunks & chromatic offset | Morphing polygons (3-7 vertices, reshuffling) | Digital static lines |
| **👻 Horror** | Pitch-black/crimson sky with massive Blood Moon & craters | Drifting red fog wisps | Crimson veiny cracks & blood pooling | Fleshy spikes & skeletal hands with vein strokes | Giant eyeballs with tracking iris & optic nerves | Thick dark-red blood rain |
| **🌿 Natural** | God ray sunbeams (lighter composite), recursive fractal trees | Lush sine-bump treeline silhouettes | Rich earth with dense grass & wildflowers | Giant mushrooms (spotted cap) & thorny vines | Drifting leaves & dandelion seeds with flutter | Falling leaves with wide sine sway |
| **✨ Fantasy** | Purple-magenta twilight, Aurora Borealis (4 sine wave layers), floating islands | Mystical purple mountains with peak sparkle | Magical purple ground with glowing runes | Amethyst crystal clusters with shadowBlur glow | Glowing wisps/fairies with soft aura & trail | Pulsing four-pointed star sparkles |
| **📦 Basic** | Pure white sky | Black step-silhouette horizon | Solid black with perspective checkerboard | Pure black triangles/rectangles, white outline | Hollow wireframe diamonds & isometric cubes | CRT static noise (1-frame black lines) |

#### Core VFX Systems
- **Particle System**: Dynamic particles for jumps, landings, combos
- **Squash & Stretch**: Character animation on jumps/landings
- **Decorative Clouds**: 10 animated background clouds
- **Flying Objects**: Theme-specific decorations (birds, drones, dragons, fairies, etc.)
- **Weather Particles**: Real-time weather visual effects with style-specific rendering
- **Screen Effects**: Full-screen overlay animations for events
- **Smooth Animations**: 60 FPS with requestAnimationFrame
- **Projectile System**: Bullets and laser attacks for abilities and bosses
- **3-Layer Parallax**: Sky → Mountains → Ground with independent scroll speeds
- **Screen Shake**: Camera shake with decaying intensity on 5 trigger types
- **Hit-Stop**: 4-frame physics freeze on projectile kills
- **Chromatic Aberration**: Red/cyan offset post-processing (persistent on Glitch, burst on death)
- **Neon Glow**: Additive blending for cyberpunk/glitch/rainbow themes
- **Player Ribbon Trail**: 15-point fading polyline with neon glow on select themes

### 🎯 Advanced Features
- **Mission System**: 3 random objectives with success/failure validation and bonus rewards
- **Screen Events**: Post-50 point visual challenge system with global cooldown
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
- Player            // 70x70px character with physics, abilities, and ribbon trail
- Obstacle          // Procedurally generated obstacles (ground, aerial, traps) with neon glow
- Boss              // Epic boss fights with health and attack patterns
- Projectile        // Bullets and lasers with energy trail VFX
- Particle          // Visual effect particles
- Cloud             // Background decoration
- FlyingObject      // Theme-based flying decorations
- SoundManager      // Audio system with music and SFX
- BackgroundManager // 3-layer procedural parallax backgrounds (sky/mountains/ground)
- FXManager         // Screen shake, hit-stop, and chromatic aberration system
- GroundSplash      // Rain impact splash particles
- StyleRenderers    // Strategy pattern: per-style draw methods (all 12 themes)

// Game Systems
- Physics Engine    // Gravity, collision detection
- Event System      // 3 balanced surprise events with RNG timing
- Weather System    // 4 weather types with style theming
- Mission System    // 3 random objectives with bonus rewards
- Ability System    // 12 unique theme-specific active skills
- Style Manager     // 12 theme configurations
- State Machine     // Menu/Playing/Paused/GameOver
- Boss System       // Periodic boss fights every 200 points
- VFX Pipeline      // Parallax, additive blending, screen shake, hit-stop, chromatic aberration
- Style Rendering   // Strategy pattern delegates draw() per currentStyle with graceful fallback
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
- **12** Style-Specific Procedural Renderers (all 12 themes: normal, cyberpunk, steampunk, medieval, rainbow, dark, easter, glitch, horror, eco, fantasy, basic)
- **6** Per-Style Render Methods (sky, mountains, ground, obstacle, aerial, weather)
- **3** Balanced Surprise Events
- **4** Weather Types
- **3** Parallax Background Layers
- **10** Background Clouds
- **8** Flying Objects
- **5** Game States
- **3** Mission Objectives per run
- **3** Obstacle Types (ground, aerial, traps)
- **100+** Particle effects simultaneously
- **5** Screen Shake trigger types
- **1** Hit-Stop system for projectile kills
- **1** Chromatic Aberration post-process effect

---

## 📜 Version History

### v13.0 - "Style-Specific Procedural Generation" (Current)
- 🏗️ **Strategy Pattern Architecture**: New `StyleRenderers` object — all 12 style keys provide `drawSky`, `drawMountains`, `drawGround`, `drawObstacle`, `drawAerial`, `drawWeather` methods
- 🌄 **Normal Theme**: Glowing sun with animated rays, fluffy arc clouds, 3-layer rolling mountains, earthy ground with grass & pebbles, jagged rock obstacles with moss, flapping birds with beak & tail, soft blue rain & twinkling snow
- 🌃 **Cyberpunk Theme**: Retrowave sun with horizontal slices, neon-window skyscrapers (cyan/magenta), perspective grid ground with glow edge, laser fence pillar obstacles with bloom, angular diamond drones with spinning rotors & LED blink, acid rain (neon green/pink glow) & glitch snow squares
- ⚙️ **Steampunk Theme**: Rotating gears with teeth & hub (ctx.rotate), rising steam plumes, industrial chimney skyline, metal plate ground with rivets & track rail, brass pipe obstacles with flanges/rivets/valve wheel, hot air balloon aerials with striped envelope & basket, smog/soot weather
- 🏰 **Medieval Theme**: Gothic castle tower silhouettes with crenellations & pointed roofs, low-lying fog with drifting wisps, cobblestone ground, wooden X-barricade obstacles with iron spike tips & wood grain, leathery bat aerials with pointed wings/red eyes/ears, heavy dark rain with lightning flashes
- 🌈 **Rainbow Theme**: Flowing 7-color spectrum sine waves with additive blending, prismatic light beams, rainbow gradient ground with HSL sparkle dots, crystalline spike obstacles with rainbow gradient & glow outline, rotating diamond prism aerials with HSL aura, confetti weather
- 🌙 **Dark Theme**: Dead twisted tree silhouettes with recursive branching, faint moon glow, near-black jagged horizon with dense fog & drifting wisps, pitch-black ground with faint cracks, pure-black thorn cluster obstacles with eerie white outline, shadowy wraith aerials with glowing white eyes, falling grey ash weather
- 🥚 **Easter Theme**: Rolling mint-green hills with giant Easter eggs (clipped zigzag/polka patterns), small 5-petal flowers, pastel-green gradient ground with grass tufts & daisies, chocolate bunny & cracked eggshell obstacles, yellow chick & painted egg aerials, spring petal weather (bezier teardrops)
- ⚡ **Glitch Theme**: Shifting barcode bars with cyan/red chromatic aberration (screen composite), fragmented data blocks in magenta/green/cyan, dark ground with corrupted color stripes & pixel edge, data-block obstacles with bitten chunks & chromatic offset, morphing polygon aerials (3-7 vertices reshuffling), digital static weather
- � **Horror Theme**: Pitch-black/deep crimson gradient sky with massive radial-gradient Blood Moon & craters, jagged overlapping thorn-wasteland silhouettes, drifting red fog wisps, veiny cracked crimson ground with blood pooling patches, fleshy spike & skeletal hand obstacles with vein strokes, floating giant eyeball aerials with tracking iris/pupil & trailing bezier optic nerves, thick dark-red blood rain
- 🌿 **Eco (Natural) Theme**: God ray sunbeams with `lighter` composite, distant recursive fractal trees (ctx.scale/rotate branching with leaf clusters), lush sine-bump treeline silhouettes, rich earthy ground with dense swaying quadratic grass & scattered wildflowers, giant mushroom (spotted red bezier cap & white stem) & thorny vine obstacles, drifting leaf & dandelion seed aerials with flutter rotation, falling leaf weather with wide sine sway
- ✨ **Fantasy Theme**: Deep purple-magenta twilight gradient sky, 4-layer Aurora Borealis (thick overlapping sine waves in cyan/purple/pink with `lighter` blending), floating islands with flat grassy tops & jagged rocky bottoms & tiny trees, mystical purple mountains with peak sparkle shimmer, magical purple ground with glowing rune inscriptions, amethyst crystal cluster obstacles with shadowBlur inner glow, glowing wisp/fairy aerials with massive soft aura & trailing particles, pulsing four-pointed star sparkle weather
- 📦 **Basic Theme**: Pure white (#FFFFFF) sky, stark black step-silhouette horizon, solid black ground with perspective checkerboard floor (converging diagonal lines), pure black triangle/rectangle obstacles with thick white outline & cross-hatch detail, hollow wireframe diamond & isometric cube aerials with dashed back edges, CRT screen-tearing static noise weather (1-frame horizontal black lines)
- 🎯 **Zero Physics Changes**: Only `draw()` methods modified; constructors, `update()`, `collidesWith()`, bounding boxes, scoring untouched
- 🎨 **100% Procedural Canvas**: All new art uses pure Canvas API (arcs, gradients, bezier curves, rotate transforms, recursive fractal branching, clip, screen composite)

### v12.0 - "Visual and Game Feel Big Update"
- 🏔️ **Procedural Parallax Backgrounds**: 3-layer scrolling system (sky/stars/moon, mountains, ground) replacing static backgrounds
- 🌙 **Dynamic Moon & Stars**: Radial-gradient moon with theme-specific colors (cyberpunk = magenta, horror = blood red, dark = pale) and twinkling stars on dark themes
- ⛰️ **Procedural Mountain Ranges**: Two noise-based mountain silhouettes scrolling at different parallax speeds (far 15%, near 35%)
- 🌿 **Animated Ground Layer**: Swaying grass blades, moving detail lines, and depth striping replacing old static ground
- 💡 **Additive Blending (Neon Glow)**: Cyberpunk/Glitch/Rainbow themes use `globalCompositeOperation = 'lighter'` for neon glow on all game objects
- 🎀 **Player Ribbon Trail**: 15-point position history drawn as fading polyline behind the player, with neon glow on cyberpunk/glitch
- 💫 **Projectile Energy Trail**: Outer glow ring + 3 fading energy circles behind each projectile with additive blending
- 🔲 **Obstacle Neon Glow**: Outer neon glow rect + animating energy scan line on obstacles for cyberpunk/glitch themes
- 🦇 **Aerial Enemy Living Geometry**: Sinusoidal Y-axis bobbing with per-instance random speed/amplitude, pulsating aura, and energy ring effects
- 💀 **Trap Obstacle VFX**: Bobbing Y motion, pulsating outer glow rings, and rotating inner elements
- 🐉 **Boss Attack VFX**: Laser outer glow + bright core; projectile outer glow + hot center; additive blending on dark themes
- 📳 **Screen Shake System**: Camera shake with decaying intensity triggered on death (12), projectile kills (6), trap hits (5), shield blocks (4), boss kills (15)
- ⏸️ **Hit-Stop System**: 4-frame physics freeze on projectile obstacle destruction while rendering continues — classic "game feel" technique
- 🌈 **Chromatic Aberration**: Red/cyan color offset post-processing — persistent on Glitch theme, burst on death and boss hit
- 🌧️ **Rain Ground Splash**: Rain particles spawn 3 tiny upward-bouncing splash particles on ground impact
- ⛈️ **Storm Neon Rain**: Additive blending on rain during storms for cyberpunk/glitch/dark themes
- 🖼️ **Enhanced Border**: Decorative corner brackets with glitch wobble effect
- 🔧 **BackgroundManager Class**: New dedicated class managing all parallax layers, scrolling, and procedural generation
- 🔧 **FXManager System**: New system for screen shake, hit-stop, and chromatic aberration with full reset support
- 🎮 **Zero External Assets**: All visuals are 100% procedural using Canvas API — no images, no sprites, no external files

### v11.1 - "Enhanced Event Experience"
- ⏰ **3-Second Countdown Warning**: Big countdown timer (3...2...1...) displays before screen events trigger
- ⚠️ **Visual Warning System**: Red warning box with gold border appears center-screen
- 🎭 **Dramatic Animation**: Each countdown number pulses and scales for impact
- 🎯 **Better Player Preparation**: Players now have time to anticipate and prepare for events
- 🔧 **Fixed Z-Index Overlap**: Mission completion notifications now always appear above screen effects
- 📊 **Improved Notification Hierarchy**: Event notifications z-index increased to 150 (was 12)
- ✨ **Smooth Countdown Animation**: CSS keyframe animation with scale and opacity effects
- 🎮 **Enhanced UX**: Critical feedback (mission complete) no longer hidden by visual effects
- 💯 **Better Visibility**: Countdown warning has highest z-index (200) for maximum visibility

### v11.0 - "Advanced Events & Missions"
- 🌑 **Screen Events System**: Two new visual challenge events for players above 50 points
- ⚡ **The Dark Descends**: Gradual screen darkening to 10% brightness with smooth recovery
- 💥 **Flashbang**: Instant white flash for 1.5 seconds followed by fade-out recovery
- ⏱️ **Global Cooldown**: 60-second shared cooldown system prevents event spam
- ✅ **Mission Failure System**: Missions can now fail with real-time validation
- 🎯 **Smart Validation**: "No Double Jump" mission fails if used before reaching 20 points
- ❌ **Visual Feedback**: Failed missions display with ✗ symbol and gray strikethrough
- 🔄 **Continuous Monitoring**: AI constantly checks all mission failure conditions
- 📊 **Enhanced Challenge**: Screen events test player adaptation without unfairness
- 🎮 **Balanced Difficulty**: Post-50 activation ensures players are ready for challenges

### v10.4 - "Loading Screen & Optimization"
- ⏳ **Loading Screen**: Beautiful animated loading screen with progress bar on game startup
- 🎨 **Visual Effects**: Floating particles, rotating spinners, and gradient animations
- 💡 **Loading Tips**: Dynamic tip system displaying helpful game information
- ⚡ **Performance-Aware**: Loading system adapts to device capabilities for optimal experience
-  **Multi-Stage Loading**: Progress tracking through Assets, Engine, Sound, Graphics, and World initialization
- ✨ **Smooth Animations**: Polished fade-out effect when loading completes
- 🎯 **Optimized Initialization**: Enhanced game startup for better performance
- 🔧 **UI Fixes**: Properly centered loading bar with margin alignment

### v10.3 - "Performance & Optimization"
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
- [x] 3-layer procedural parallax backgrounds
- [x] Screen shake on collisions and kills
- [x] Hit-stop on projectile obstacle destruction
- [x] Chromatic aberration post-processing
- [x] Player ribbon trail with neon glow
- [x] Additive blending for cyberpunk/glitch themes
- [x] Living geometry (sinusoidal bobbing) for aerial enemies
- [x] Rain ground splash particles
- [x] Boss attack VFX with additive glow
- [x] 100% procedural rendering (zero external assets)
- [x] 12 style-specific procedural renderers (Strategy pattern — all themes)

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
**Version**: 13.0 "Style-Specific Procedural Generation"  
**Last Updated**: 2026

---

## 🔗 Quick Links

- **Game File**: `arcade_game.html`
- **Current Version**: 13.0
- **Total Versions**: 22 major releases
- **Lines of Code**: 9400+
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
