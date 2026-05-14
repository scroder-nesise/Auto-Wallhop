# WALLHOP V2.5

Advanced Roblox wall movement utility featuring Infinite Jump and Camera Flick mechanics with a fully customizable futuristic UI.

Built for movement chaining, wall interaction control, and smooth camera-based flick systems.

---

# ✨ Features

- ⚡ Infinite Jump wall mechanic
- 🎥 Camera Flick movement system
- 🧠 Smart wall detection
- 🎮 Fully draggable UI
- ⚙ Built-in settings panel
- 🔑 Custom keybind system
- 🌈 Animated futuristic interface
- 📱 Mouse + touch support
- 🔄 Smooth flick rotation mode
- 🎯 Adjustable flick angles
- 🚀 Velocity customization
- 🧱 Collision-aware wall checks
- 👤 Player body detection filter
- 🔥 Tween-based UI animations
- 🛡 Auto cleanup for duplicate GUIs

---

# 🎮 Modes

## 1️⃣ Infinite Jump Mode

Allows repeated jumping when near walls.

### Features
- Wall proximity detection
- Adjustable jump cooldown
- Custom jump velocity
- Randomized jump variance
- Prevents spam through cooldown logic

### Default Keybind
```plaintext
Left Control
```

---

## 2️⃣ Camera Flick Mode

Performs rotational camera/body flicks to assist movement chaining and wallhops.

### Features
- Instant or smooth flick rotation
- Adjustable flick angle
- Direction modes:
  - Random
  - Left
  - Right
- Snap-back system
- Jump chain limiter
- Camera + body synchronization

### Default Keybind
```plaintext
Right Alt
```

---

# ⌨ Default Controls

| Key | Action |
|---|---|
| `-` | Toggle ON/OFF |
| `Left Control` | Switch to Inf Jump |
| `Right Alt` | Switch to Cam Flick |

---

# ⚙ Settings Panel

The built-in settings menu includes:

## Infinite Jump Settings
- Inf Jump Cooldown
- Jump Velocity
- Jump Variance

## Camera Flick Settings
- Flick Cooldown
- Flick Direction
- Smooth Flick Toggle
- Smooth Duration

## Other Settings
- Flick Angle
- Max Chain
- Snap Duration
- Player Detection

## Custom Keybinds
Rebind:
- Toggle key
- Inf Jump mode key
- Cam Flick mode key

---

# 🎨 UI Features

WALLHOP V2.5 includes a custom-made futuristic GUI system featuring:

- Neon accent styling
- Animated tab slider
- Smooth tween transitions
- Scrollable settings panel
- Rounded modern design
- Dynamic mode colors
- Drag-and-drop interface
- Minimal compact layout

---

# 🧠 Technical Highlights

## Smart Wall Detection
Uses:
- Raycasting
- Collision filtering
- Overlap checks

to detect nearby valid walls while ignoring unwanted player parts.

---

## Smooth Flick Engine
Optional smooth flick system powered by:
- `RunService.Heartbeat`
- Incremental rotational stepping
- Smoothstep easing interpolation

This prevents physics conflicts and creates natural camera motion.

---

## Player Detection System
When enabled:
- Ignores non-collidable player body parts
- Prevents ghost collisions
- Improves movement consistency

---

## Keybind Rebinding
Interactive rebinding system:
- Click any bind
- Press a new key
- Updates instantly

No restart required.

---

# 🛠 Built With

- Roblox Lua (Luau)
- Roblox TweenService
- Roblox RunService
- Roblox UserInputService
- Roblox Raycasting APIs

---

# 📦 Script Includes

- GUI system
- Drag system
- Settings system
- Movement logic
- Flick engine
- Rebinding system
- Tween animations
- Collision detection
- Camera handling

---

# 🚀 How It Works

## Infinite Jump
1. Detects nearby walls
2. Waits for jump input
3. Applies upward velocity boost
4. Maintains chain movement

## Cam Flick
1. Detects jump/freefall state
2. Applies rotational flick
3. Rotates camera + player body
4. Snaps back automatically

---

# 🔥 Why WALLHOP Exists

WALLHOP was designed to create:
- Faster movement chains
- Cleaner wall interactions
- More advanced movement mechanics
- Adjustable movement behavior
- Stylish movement utilities

while keeping everything lightweight and responsive.

---

# 📱 Compatibility

Supports:
- PC
- Laptop
- Touch devices
- Mouse input
- Keyboard input

---

# 🔮 Future Ideas

Potential future updates:
- More flick modes
- Velocity presets
- Preset save system
- UI themes
- Mobile button controls
- Advanced movement analytics
- Auto chain assist
- Profile configs

---

# 📜 Notes

- Designed for movement-based gameplay.
- Some games may behave differently depending on physics/networking.
- Smooth Flick mode may feel different depending on FPS.

---

# 👾 Version

```plaintext
WALLHOP V2.5
```

---

# ⭐ Credits

Created using Roblox Lua and custom UI systems.

---

# 🔥 Final Note

WALLHOP V2.5 combines advanced movement mechanics with a polished futuristic interface to create a fast, customizable, and responsive wall movement experience.
