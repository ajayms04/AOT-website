# ⚔️ Attack on Titan – Interactive Cinematic Storytelling

An immersive, scroll-driven storytelling experience inspired by **Attack on Titan**, built using **HTML, CSS, and JavaScript**. The project recreates a cinematic narrative where users reveal the story through scrolling, accompanied by animated image sequences, smooth transitions, and atmospheric background music.

> *"If you win, you live. If you lose, you die. If you don't fight, you can't win."* — **Eren Yeager**


---

## ✨ Features

- 🎬 Scroll-controlled cinematic image sequence animation
- 🎨 Fullscreen HTML5 Canvas rendering
- 📖 Interactive storytelling layout
- ✨ Smooth fade-in animations using Intersection Observer
- 🎵 Optional ambient background music with mute/unmute control
- 🌑 Dark cinematic Attack on Titan inspired theme
- 📱 Responsive design for desktop and mobile
- 🖱️ Sticky hero section with immersive scrolling experience
- 🎭 Elegant typography using Google Fonts

---

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript (ES6)
- HTML5 Canvas API
- Intersection Observer API
- Google Fonts

---

## 📂 Project Structure

```
Attack-On-Titan-Story/
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

### Clone the repository

```bash
git clone https://github.com/your-username/Attack-On-Titan-Story.git
```

### Navigate into the project

```bash
cd Attack-On-Titan-Story
```

### Run the project

Simply open **index.html** in your browser.

For the best experience, use **Live Server** in Visual Studio Code.

---

## 🎥 Image Sequence

The cinematic intro uses **50 extracted image frames** stored inside:

```
AOT_VIDEO/
```

Images follow the naming convention:

```
ezgif-frame-001.jpg
ezgif-frame-002.jpg
...
ezgif-frame-050.jpg
```

The JavaScript preloads all frames and renders them onto an HTML5 canvas based on the user's scroll position.

---

## 🎵 Background Audio

The project includes ambient orchestral background music.

Features:

- Loop playback
- Mute / Unmute button
- Low-volume cinematic ambience
- Browser autoplay restrictions handled gracefully

---

## 🎨 Color Palette

| Color | Hex |
|--------|------|
| Background | `#030303` |
| Primary Text | `#EDEDED` |
| Accent Red | `#9E0B0F` |
| Glow Red | `#FF1A1A` |

---

## 📱 Responsive Design

The website is optimized for:

- Desktop
- Tablets
- Mobile devices

Responsive typography is achieved using:

```css
clamp()
```

along with flexible layouts and media queries.

---

## ⚡ Technologies Used

### HTML

- Semantic structure
- Audio API
- Canvas element

### CSS

- CSS Variables
- Flexbox
- Sticky positioning
- Animations
- Gradients
- Responsive typography
- Custom scrollbar
- Glassmorphism effects

### JavaScript

- Canvas rendering
- Image preloading
- Scroll-based animation
- Intersection Observer
- Event listeners
- Audio controls
- Responsive canvas resizing

---

## 💡 Inspiration

This project is inspired by the storytelling style of modern interactive websites and the emotional narrative of **Attack on Titan**.

The goal was to create an engaging, cinematic web experience where scrolling becomes part of the story.

---

## 📈 Future Improvements

- 🎞️ Higher frame-count animations
- 🌫️ Particle and smoke effects
- ⚔️ 3D ODM Gear animation
- 🔥 Dynamic lighting effects
- 🎧 Multiple soundtrack options
- 🌍 Full story timeline
- 📖 Character profiles
- 🎬 Scene transitions
- 🩸 Blood and dust visual effects
- WebGL / Three.js enhancements

---

## ⚠️ Disclaimer

This project is a **fan-made, non-commercial** web experience inspired by **Attack on Titan**.

Attack on Titan, its characters, artwork, and related intellectual property belong to their respective copyright holders.

This repository is intended solely for educational and portfolio purposes.

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve animations, optimize performance, or add new cinematic effects:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Show Your Support

If you enjoyed this project, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.

---

## 📜 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for more information.
