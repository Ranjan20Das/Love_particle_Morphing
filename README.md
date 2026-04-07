🌌 3D Particle Morphing Text (Three.js)

An interactive 3D particle animation project built using Three.js where particles dynamically morph between a heart shape ❤️ and user-entered text in real-time.

**Live working view**
:- see the working of the code through the video.mp4 file provided in the github repo


---

🚀 Features

- ✨ Smooth particle morphing animation
- ❤️ Default animated heart shape
- 🔤 Convert typed text into 3D particle text
- 🖱️ Interactive mouse repulsion effect
- 🎨 Glowing particle visuals using additive blending
- ⚡ Optimized for 40,000 particles
- 📏 Supports up to 50 characters input

---

🛠️ Tech Stack

- Three.js – 3D rendering
- JavaScript (Vanilla)
- HTML5 Canvas – text sampling
- CSS3 – UI styling

---

📂 Project Structure

project/
│── index.html        # Main file (contains HTML, CSS, JS)
│── README.md         # Documentation

---

⚙️ How It Works

1. Particle System

- Uses "THREE.BufferGeometry" to handle 40,000 particles
- Each particle has:
  - Position
  - Velocity
  - Target position

---

2. Shape Morphing

❤️ Heart Shape

Particles are arranged using a mathematical parametric equation:

x = 16 sin³(u)
y = 13cos(u) − 5cos(2u) − 2cos(3u) − cos(4u)
z = cos(t)

---

🔤 Text Shape

- Text is drawn on a hidden canvas
- Pixel data is extracted
- White pixels → converted into particle positions

---

3. Animation Logic

Each frame:

- Particles move toward target positions
- Velocity is applied with damping
- Mouse interaction repels nearby particles

---

4. Mouse Interaction 🖱️

- Cursor creates a repulsion force
- Adds interactivity and realism

---

🧪 How to Run

Option 1: Direct Open

1. Download or clone the project
2. Open "index.html" in your browser

---

Option 2: Live Server (Recommended)

Use VS Code Live Server:

Right Click → Open with Live Server

---

🎮 Usage

- Type anything in the input box
- Watch particles morph into your text
- Clear input → returns to ❤️ heart shape

---

⚠️ Performance Notes

- Uses 40,000 particles → may be heavy on low-end devices
- For better performance:
  - Reduce "particleCount"
  - Lower canvas resolution

---

🔥 Future Improvements

- 📝 Multi-line text support
- 🎥 Export animation as GIF/video
- 🎨 Custom colors & themes
- 📱 Mobile optimization
- 🔊 Sound-reactive particles

---

🤝 Contributing

Feel free to fork and improve this project!

git clone <repo-url>

---

📜 License

This project is open-source and free to use.

---

💡 Inspiration

Inspired by modern creative coding and interactive particle systems used in:

- Digital art
- Landing pages
- AI visualization tools

---

🙌 Author

Ranjan Das

---

⭐ If you like this project, give it a star!
