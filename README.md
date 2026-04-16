# 🖼️ The Gallery — Curated Memory Match

> **VishwaNova 2026 · National Level Weboreel AI Hackathon**

A premium, museum-quality memory card matching game. Select from three distinct art exhibitions (Madhubani, Ukiyo-e, or Post-Impressionism) and test your memory against an elegant, dynamically generated deck of fine art.

## ✨ Features

- 🏛️ **3D CSS Museum Entrance**: The game starts in a gallery entrance complete with a marble texture floor, velvet ropes, and three exhibition doors that swing open in 3D space using CSS perspective and `rotateY`.
- 🎨 **Dynamic AI Art Generation**: Every game is unique. The card faces are fetched dynamically from the `Pollinations.ai` image synthesis API using specific style prompts and random seeds, ensuring a fresh collection of art every time you play.
- 🎴 **Thematic Card Backs**: Each exhibition features a unique CSS-drawn pattern on the back of the cards (Saffron polka-diamonds for Madhubani, Seafoam repeating waves for Ukiyo-e, Cobalt radial swirls for Post-Impressionism).
- 🎵 **Procedural Ambient Drones**: Generative Web Audio API soundscapes adjust their root frequencies to match the cultural vibe of the selected art theme (e.g., Sitar-like drones, Koto intervals).
- ✨ **Elevated Animation Polish**: Cards feature a 3D flip animation. On a successful match, cards float up by 8px, gain a golden glow, and emit a burst of golden particle physics drawn via an HTML5 `<canvas>` layer.
- 🏅 **Elegant End Screen**: A museum-style achievement card displays your moves, final time, and a dynamic performance review based on your efficiency.

## 🛠️ Tech Stack

- **HTML5** — Interface and canvas layering
- **Vanilla CSS3** — 3D transforms, CSS patterns, gradients, and custom layouts
- **Vanilla JavaScript** — Game state logic, AI API URL generation, and particle physics engine
- **Web Audio API** — Generative music
- **Pollinations.ai** — Free, keyless AI image generation

## 📸 Try It Out

Simply double-click the `index.html` file to open it in any modern browser. No servers, build steps, or dependencies required.

---

*Built with ❤️ for VishwaNova 2026*
