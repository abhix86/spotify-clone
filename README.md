# Spotify Web Clone
(*NOT COMPLETE YET*)

A responsive, pixel-perfect Spotify web interface clone built with HTML and CSS.  
This project replicates the look and feel of Spotify's desktop application, focusing on UI/UX precision, layout accuracy, and modern design.

---

## Features

- Fully responsive layout optimized for desktop and mobile screens  
- Fixed player bar with interactive elements  
- Custom hover animations and tooltips  
- Radio-button-based dynamic overlay modal system  
- Modular file structure for scalability  
- Inspired by Spotify's official web app with personal enhancements

---

## Folder Structure

```
.
├── index.html                 # Main HTML file
├── styles/
│   ├── styles.css             # Base styles
|   |── player.css             # player styles
│   ├── body/
│   │   ├── body_left/         # Left-side styles
│   │   ├── body_mid/          # Middle section styles
│   │   └── body_right/        # Preview/right styles
│   └── player.css             # Music player styles
├── resources/
│   ├── main_buttons/          # SVG icons and control buttons
│   └── covers/                # Album cover images
```

---

## How It Works

- Radio inputs used for toggling overlays and interaction logic
- CSS `z-index`, `position`, and `transform` handle dynamic layout
- `@media` queries ensure responsive design
- Shadow, hover, and tooltip effects for smooth UX
- No JavaScript — just HTML and CSS

---

## Getting Started

Clone the repository and open `index.html` in any modern browser.

```bash
git clone https://github.com/abhix86/spotify-clone.git
cd spotify-clone
```

Then open the file directly:

```bash
start index.html
```

> Note: You may replace the path and assets with your own resources as needed.

---

## Developer Notes

This project is purely front-end and aims to push the boundaries of what CSS alone can accomplish.  
Further improvements may include JavaScript-based(or maybe not) audio control, animations, or backend integration.

---

**Created by Abhi**  
Feel free to fork, study, or extend it.
