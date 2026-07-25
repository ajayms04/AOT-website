# ⚔️ Attack on Titan – Interactive Cinematic Storytelling

An immersive, scroll-driven storytelling experience inspired by **Attack on Titan**, built entirely with **Vanilla HTML, CSS, and JavaScript**.

This project transforms a traditional webpage into a cinematic journey where every scroll advances the story through animated image sequences, smooth transitions, atmospheric visuals, and ambient background music.

> *"If you win, you live. If you lose, you die. If you don't fight, you can't win."*  
> — **Eren Yeager**

---

## ✨ Features

- 🎬 Scroll-controlled cinematic image sequence animation
- 🖼️ HTML5 Canvas rendering for smooth frame playback
- 📖 Interactive storytelling experience
- ✨ Smooth fade-in content animations
- 🎵 Ambient background music with mute/unmute control
- 🌑 Dark cinematic UI inspired by Attack on Titan
- 📱 Fully responsive design
- 🎨 Elegant typography using Google Fonts
- 🖱️ Sticky hero section with immersive scrolling

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**

### Browser Features Used

- HTML5 Canvas
- HTML5 Audio
- Intersection Observer
- CSS Variables
- Flexbox
- Sticky Positioning
- CSS Animations & Transitions
- Media Queries

---

## 📂 Project Structure

```
Attack-On-Titan-Interactive-Story/
│
├── index.html
├── style.css
├── script.js
│
├── AOT_VIDEO/
│   ├── ezgif-frame-001.jpg
│   ├── ezgif-frame-002.jpg
│   ├── ...
│   └── ezgif-frame-050.jpg
│
├── preview/
│   ├── hero.png
│   └── story.png
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Attack-On-Titan-Interactive-Story.git
```

### 2. Navigate into the Project

```bash
cd Attack-On-Titan-Interactive-Story
```

### 3. Run the Project

Open `index.html` in your browser.

For the best experience, use **Live Server** in Visual Studio Code.

---

## 🎬 How It Works

### Scroll Animation

The hero section uses an image sequence consisting of **50 extracted frames**.

As the user scrolls, JavaScript calculates the scroll progress and renders the corresponding frame onto an HTML5 Canvas, creating a smooth cinematic animation.

### Story Reveal

Each story section fades into view using the **Intersection Observer**, providing a seamless reading experience.

### Background Music

A built-in audio player allows users to enable or disable ambient orchestral music without interrupting the experience.

---

## 🎨 Design Highlights

- Minimal cinematic aesthetic
- Dark monochrome theme with crimson accents
- Large cinematic typography
- Smooth scrolling interactions
- Responsive layouts
- Subtle vignette and lighting effects
- Elegant content reveal animations

---

## 📱 Responsive Design

The website is optimized for:

- 💻 Desktop
- 📱 Mobile
- 📟 Tablets

Responsive typography is implemented using CSS `clamp()` and flexible layouts powered by Flexbox.

---

## 📁 Assets

This project includes:

- Extracted image sequence (`AOT_VIDEO/`)
- Royalty-free orchestral background music
- Google Fonts (`Cinzel` & `Inter`)

---

## 💡 Inspiration

Inspired by the storytelling techniques of modern interactive websites, this project recreates the emotional atmosphere of **Attack on Titan** through web technologies.

Rather than presenting information traditionally, the story unfolds naturally as the user scrolls, creating a cinematic experience.

---

## 🔮 Future Improvements

- Higher frame-count animations
- Particle effects (dust, smoke, embers)
- Character introduction scenes
- Sound effects synchronized with scrolling
- Dynamic lighting and color grading
- Three.js/WebGL version
- Accessibility improvements
- Loading screen with progress indicator

---

## ⚠️ Disclaimer

This is a **fan-made, non-commercial project** created for educational and portfolio purposes.

Attack on Titan and all related characters, names, and intellectual property belong to their respective copyright holders.

---

## 🤝 Contributing

Contributions are welcome!

If you have ideas to improve animations, optimize performance, or enhance the storytelling experience:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Support

If you enjoyed this project, consider giving it a **⭐ Star** on GitHub.

It helps others discover the project and motivates future improvements.

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use this project for learning and personal development.
