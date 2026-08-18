# 🎵 Melodify

> *A Spotify-inspired music streaming UI — built purely with HTML & CSS.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎨 **Dark Theme UI** | Spotify-accurate black & dark-grey palette |
| 📐 **Flexbox Layout** | Entire layout built with CSS Flexbox |
| 📚 **Sidebar Navigation** | Nav links with hover opacity transitions |
| 📖 **Library Section** | "Your Library" panel with action boxes |
| 📌 **Sticky Top Nav** | Header stays fixed during scroll |
| 🃏 **Album Cards** | Responsive cards for "Recently Played" & "Trending" |
| 🎧 **Music Player Bar** | Fixed bottom bar with controls & playback progress |
| 🔤 **Montserrat Typography** | Clean modern font via Google Fonts |

---

## 📁 Project Structure

```
Melodify/
│
├── index.html                  # Main HTML structure
├── Style.css                   # All styling & layout
│
├── assets/
│   ├── logo.png                # Spotify logo
│   ├── library_icon.png        # Library section icon
│   ├── card1img.jpeg           # Album/playlist card images
│   ├── card2img.jpeg
│   ├── card3img.jpeg
│   ├── card4img.jpeg
│   ├── card5img.jpeg
│   ├── card6img.jpeg
│   ├── backward_icon.png       # Player previous button
│   ├── forward_icon.png        # Player next button
│   ├── play_musicbar.png       # Playback bar icon
│   ├── player_icon1.png        # Shuffle icon
│   ├── player_icon2.png        # Previous icon
│   ├── player_icon3.png        # Play/Pause icon
│   ├── player_icon4.png        # Next icon
│   └── player_icon5.png        # Repeat icon
│
└── README.md
```

---

## 🧠 What I Learned

### 1. Setting Up & Basics
- Structuring an HTML project with proper folder organization
- Applying CSS resets, global variables, and consistent font imports via Google Fonts
- Linking Font Awesome icons via CDN for scalable vector icons

### 2. Layout
- Using **CSS Flexbox** to divide the page into sidebar + main content + player
- Managing `height: 100vh` and `overflow: hidden` for full-viewport layouts
- Using `flex: 1` to let the main content area fill available space

### 3. Sidebar (Nav & Library)
- Building vertical navigation with icon + text rows using `display: flex` and `align-items`
- Applying `opacity` transitions on hover for a smooth, interactive feel
- Creating a separate `.library` panel with its own background and border-radius

### 4. Library Boxes
- Designing dark-themed call-to-action cards (`.box`) with rounded corners
- Using `inline-block` styled badges to mimic Spotify's pill-shaped buttons

### 5. Sticky Nav
- Using `position: fixed` and `top: 0` to keep the header locked during page scroll
- Layering z-index to ensure the nav sits above scrollable content

### 6. Cards
- Building a card grid with album art images and text overlays
- Implementing hover effects for an interactive, app-like feel

### 7. Footer Line
- Styling a footer separator using borders and spacing utilities

### 8. Music Player
- Building the fixed bottom player bar with `position: fixed; bottom: 0`
- Structuring three columns: track info | controls | volume — using nested Flexbox
- Styling the **playback progress bar** using a custom-styled range input or div

---

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/aditya-forge/Melodify.git
   ```

2. **Open in browser**
   ```
   Open index.html in your browser
   ```

3. **Explore the UI** — Browse the sidebar, cards, and music player at the bottom!

---

## 🖥️ Preview

| Section | Description |
|---|---|
| Sidebar | Library + Nav with hover effects |
| Main Content | Recently Played & Trending cards |
| Bottom Player | Controls, progress bar & volume |

---

## 🔧 Tech Stack

- **HTML5** — Semantic markup & structure
- **CSS3** — Flexbox, transitions, custom properties
- **Google Fonts** — Montserrat font family
- **Font Awesome 7** — Icons via CDNJS

---

## 👤 Author

**Aditya** — [@aditya-forge](https://github.com/aditya-forge)

---
