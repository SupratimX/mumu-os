# 💗 MumuOS — The World of Us

> **A tiny operating system built for one very special person. ❤️**

MumuOS is an interactive, romantic web experience designed to feel like a tiny personal operating system — filled with memories, letters, games, music, videos, animations, surprises, and little interactions.

Instead of being a traditional website, MumuOS presents everything through a **cute desktop-style interface**, where each feature behaves like an individual application.

---

## ✨ Features

### 🖥️ Desktop-Style Interface

* Interactive MumuOS desktop
* App-style icons
* Animated wallpaper
* Glassmorphism-inspired windows
* Window opening and closing animations
* Draggable application windows
* Responsive mobile layout

### 📸 Memories Gallery

A dedicated gallery for memories and photographs.

* Supports up to **50 memory images**
* Interactive image viewer/lightbox
* Individual memory captions
* Responsive gallery layout

Images are loaded dynamically using the `p1.jpg` → `p50.jpg` naming convention.

### 💌 Love Letters

An interactive collection of personal letters including:

* **Open When: You Miss Me**
* **Open When: You Are Angry**
* **Open When: We Just Fought**
* **Open When: You Can't Sleep**
* **The 2026 Promise**

Clicking a letter reveals its contents directly inside the application.

### 📊 Love Analytics

A playful statistics dashboard featuring:

* Love-level visualization
* Days-together counter
* Relationship statistics
* Fun fictional analytics
* A timeline progressing toward “Forever”

### 🎬 Cinema

A dedicated video section containing multiple playable videos:

* `v1.mp4`
* `v2.mp4`
* `v3.mp4`
* `v4.mp4`

### 🎮 Gahori Adventure

A small browser game built using **HTML Canvas + JavaScript**.

The objective is simple:

> Catch the hearts and pani puri while avoiding the angry emojis. ❤️

The game includes:

* Player movement
* Gravity
* Collectibles
* Obstacles
* Collision detection
* Score tracking
* Game-over state
* Keyboard controls
* Touch controls

### 💍 Interactive Proposal

A dedicated proposal experience featuring:

> **“Mumu, will you be mine forever?”**

It includes:

* Video
* Animated floating hearts
* YES interaction
* Playful NO button that moves away
* Celebration animation
* Sound effects

### 🎨 Draw Our Dream

A built-in drawing canvas where users can draw directly inside MumuOS.

Features include:

* Mouse drawing
* Touch drawing
* Multiple brush colors
* Clear canvas
* HTML Canvas rendering

### 🍕 Gahori's Kitchen

A playful food-ordering interface containing options such as:

* 🥟 Pani Puri
* 🍕 Pizza
* 🍫 Chocolate
* 🍦 Ice Cream
* ☕ Coffee
* ❤️ Deha's Heart

Selecting an item triggers an interactive order animation and notification.

### 🌱 Our Love Garden

An interactive garden experience where the user can plant a seed and watch the experience evolve.

### 🌈 Dynamic Atmosphere

The interface contains animated environmental effects including:

* Moving celestial body
* Floating clouds
* Floating decorative elements
* Animated wallpaper
* Heart animations
* Particle-style effects

### 🔔 Notification System

MumuOS includes its own notification system for displaying messages and interactive events.

There are also randomized notifications such as:

* “Miss you...”
* “Eat something!”
* “Don't overthink!”
* “You look cute today.”

### 🔐 Secret Mode

There is also a hidden Easter egg.

Type:

```text
mumu
```

on the keyboard to activate the secret mode. 🌟

The project then transforms the visual experience and activates a special animated effect.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                      |
| ---------------- | -------------------------------------------- |
| **HTML5**        | Structure and application layout             |
| **CSS3**         | Styling, animations and responsive design    |
| **JavaScript**   | Interactions, logic and application behavior |
| **HTML Canvas**  | Mini-game and drawing application            |
| **SVG**          | Love analytics visualization                 |
| **Font Awesome** | Application icons                            |
| **Google Fonts** | Custom typography                            |
| **HTML5 Audio**  | Music and sound effects                      |
| **HTML5 Video**  | Embedded video experiences                   |

The project uses fonts including **Fredoka, Nunito, Pacifico, Quicksand and Sacramento**, along with Font Awesome icons.

---

## 📁 Project Structure

A typical setup for the project is:

```text
mumu-os/
│
├── index.html
│
├── p1.jpg
├── p2.jpg
├── p3.jpg
├── ...
├── p50.jpg
│
├── s1.mp3
├── click.mp3
├── win.mp3
├── magic.mp3
├── rain.mp3
│
├── v1.mp4
├── v2.mp4
├── v3.mp4
├── v4.mp4
├── v_ask.mp4
│
└── README.md
```

> Keep the media filenames consistent with the references inside `index.html`.

---

## 🚀 Running the Project

MumuOS is a client-side web project, so there is no backend or database required for the core experience.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/mumu-os.git
```

### 2. Enter the project directory

```bash
cd mumu-os
```

### 3. Open the website

You can simply open:

```text
index.html
```

in a modern web browser.

For the best experience, however, run it through a local development server.

### VS Code

If you have the **Live Server** extension installed:

1. Open the project in VS Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

---

## 📱 Responsive Design

MumuOS includes mobile-specific optimizations.

On smaller screens:

* Windows expand to use more of the screen
* Gallery columns adjust automatically
* Application icons become smaller
* Typography scales down
* The interface remains touch-friendly

The project specifically includes a responsive breakpoint for screens below `600px`.

---

## 🎵 Media Assets

The experience relies on external media files for its full functionality.

Make sure the required files are placed in the same directory as `index.html`, including:

```text
s1.mp3
click.mp3
win.mp3
magic.mp3
rain.mp3

v1.mp4
v2.mp4
v3.mp4
v4.mp4
v_ask.mp4

p1.jpg
p2.jpg
...
p50.jpg
```

The HTML directly references these assets for music, sound effects, videos and the memory gallery.

---

## 💡 Why I Built This

Most websites are designed to communicate information.

**This one was designed to communicate feelings.**

MumuOS turns memories, messages, photographs, music and small interactive experiences into something that feels less like a website and more like a **little digital world belonging to two people.**

Every application represents a different part of that world.

---

## ❤️ Highlights

> **50 memories.**
> **Letters for different moments.**
> **A tiny game.**
> **A cinema.**
> **A little kitchen.**
> **A place to draw.**
> **A garden.**
> **A proposal.**
> **And a whole operating system built around “us.”**

---

## 🎯 Project Goals

* Experiment with interactive front-end development
* Explore creative UI/UX design
* Practice DOM manipulation
* Work with HTML Canvas
* Implement browser animations
* Build responsive interfaces
* Experiment with multimedia on the web
* Turn a personal concept into an interactive web experience

---

## 🌟 Easter Eggs

MumuOS contains hidden interactions and playful surprises.

Try exploring the interface instead of treating it like a normal website.

You might find something unexpected. 👀

---

## 📌 Current Version

**MumuOS v3.1**

> *Optimizing Love Algorithms...* 💗

The project includes a boot sequence that displays the MumuOS v3.1 update before entering the desktop interface.

---

## 🤝 Contributing

This project is primarily a personal creative project, but suggestions, improvements and creative ideas are welcome.

If you find a bug or have an interesting idea:

1. Open an issue.
2. Describe the idea or problem.
3. Include screenshots when useful.
4. Submit a pull request for improvements.

---

## 📜 License

This project is intended as a personal creative project.

If you want to reuse the code or assets, please respect the original author's work and replace all personal media and content with your own.

---

<div align="center">

### Made with ❤️, JavaScript, and way too much imagination.

**MumuOS — The World of Us**

💗 🐷 🌸 🎮 🎬 💌 🌱 💍

</div>
