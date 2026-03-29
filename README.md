<div align="center">
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/HTML.svg" width="40" height="40" alt="HTML5" />
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/CSS.svg" width="40" height="40" alt="CSS3" />
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/main/icons/JavaScript.svg" width="40" height="40" alt="JavaScript" />

  <h1>🎉 Immersive Birthday Website</h1>
  <p>A beautifully crafted, interactive, and fully responsive digital birthday experience.</p>

  <p>
    <a href="#features">Features</a> •
    <a href="#project-structure">Project Structure</a> •
    <a href="#navigation-route-flow">Flow</a> •
    <a href="#quick-start">Quick Start</a>
  </p>
</div>

<br>

## ✨ Features

- **Interactive Landing Page (`index.html`)**: Features a beautiful countdown timer, smooth GSAP animations, and an entrance-locked loading screen.
- **Background Music**: Integrated audio player (`hbd.mp3`) with an elegant toggle button that correctly persists playback states across multiple page loads.
- **Memories Gallery (`memories.html`)**: A stunning responsive grid showcasing special moments in perfectly uniform portrait frames, featuring elegant hover zoom transitions and floating hearts with a premium Glassmorphism design.
- **Birthday Timeline (`timeline.html`)**: A scrolling journey highlighting beautiful events, history, and major milestones.
- **Heartfelt Wishes (`wishes.html`)**: Displays heartfelt birthday messages, playful animations, and interactive celebratory confetti.

## 🛠️ Built With

- **HTML5**: Semantic and accessible document structure.
- **CSS3**: Advanced animations, custom variables, grid box model, `aspect-ratio` uniform cropping for portraits, and responsive media queries.
- **Vanilla JavaScript**: DOM manipulation, interactive event listeners, and `localStorage` to persist the audio toggle seamlessly.
- **GSAP (GreenSock)**: Industry-standard animation library handling the smooth entrance and complex sequencing.

## 📂 Project Structure

```text
📦 pranitabday
 ┣ 📂 photos                     # Directory containing gallery photos (e.g. photo-1.jfif)
 ┣ 📜 index.html                 # Entry point / Landing Page & Countdown
 ┣ 📜 home.css                   # Stylesheet for the entry point
 ┣ 📜 home.js                    # Logic for countdown and GSAP entry animations
 ┣ 📜 timeline.html              # Timeline showing history & moments over the years
 ┣ 📜 memories.html              # Responsive photo gallery with uniform image displays
 ┣ 📜 wishes.html                # Special wishes and messages page finalé
 ┣ 📜 wishes.css                 # Styling for the wishes page
 ┣ 📜 wishes.js                  # Logic for handling wishes page animations & confetti
 ┣ 📜 hbd.mp3                    # Persistent background music
 ┣ 📜 background-movable.gif     # High quality animated aesthetic background asset
 ┣ 📜 gif1.gif                   # Playful visual assets
 ┗ 📜 gif2.gif                   # Playful visual assets
```

## 🚀 Navigation Route Flow

The user journey is engineered to be sequential, suspenseful, and deeply personal:

1. **`index.html`**: The user lands here first. A loading screen reveals a "Birthday Countdown" timer. Once the primary action (Click to Enter) is triggered, the digital journey begins.
2. **`timeline.html`**: The user typically proceeds here to scroll through a journey mapping the relationship, history, or chronological milestones.
3. **`memories.html`**: The user navigates here to experience a dynamic grid of cherished memories, styled as matching portrait cards with modern blur aesthetics.
4. **`wishes.html`**: The grand conclusion—a dedicated page filled with written messages and an interactive confetti cannon celebration.

## ⚙️ Quick Start & Customization

### Installation
To get this project on your local machine, run the following command in your terminal:
```bash
git clone https://github.com/iamgajanan70/pranitabday.git
```

### Running Locally
Because this project utilizes standard web technologies without a complex backend, you can explore it simply by opening the files in your browser. 
For the absolute best experience (to ensure `localStorage` and modules work without cross-origin constraints), run it using **Live Server** in VS Code:
1. Open the project folder in VS Code.
2. Right-click `index.html` and select **"Open with Live Server"**.

### Personalizing
If you want to customize this repo for a loved one's birthday, do the following:
1. **Music**: Replace `hbd.mp3` with their favorite song.
2. **Photos**: Swap out the images inside the `photos/` folder. The built-in CSS handles the resizing and portrait styling automatically!
3. **Text & Dates**: Press `Ctrl+F` and search for `<!-- CUSTOMIZE: -->` inside the HTML files to quickly identify where you need to replace names, variables, dates, and messages.

---
<div align="center">
  <i>Created with 💖 to celebrate the ones we care about.</i>
</div>
