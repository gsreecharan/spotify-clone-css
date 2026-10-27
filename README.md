# Spotify Web Player Clone

A responsive frontend replica of the desktop Spotify Web Player interface, built using semantic HTML5 and pure CSS3 without external UI frameworks.

---

## Overview

This project focuses on replicating Spotify's core desktop player layout, visual hierarchy, and media player interface. It demonstrates advanced CSS styling techniques, including multi-container flexbox layouts, persistent fixed positioning, custom-styled input sliders for audio track scrubbing, and responsive breakpoints.

### Key Features
- **Sidebar & Navigation:** Dual-panel navigation featuring search, library management, and playlist creation prompts.
- **Sticky Header:** Top navigation bar with directional controls, account buttons, and viewport-adaptive element visibility.
- **Content Grids:** Horizontally wrapping grid layout for music albums, categorized by recently played, local trending, and global charts.
- **Persistent Media Player:** Bottom audio console complete with album metadata, playback control toggles, and volume adjustments.
- **Custom UI Controls:** Formatted range sliders using `::-webkit-slider-runnable-track` and `::-webkit-slider-thumb` to replicate Spotify's green playback progress bar.
- **Responsive Layout:** Media query adjustments hiding non-critical controls on compact screens.

---

## Technical Stack

- **Markup:** HTML5 (Semantic elements)
- **Styling:** CSS3 (Flexbox, Fixed Positioning, Custom WebKit pseudo-elements)
- **Icons & Typography:** Font Awesome 7.0, Google Fonts (Montserrat)

---

## Project Structure

```text
├── Assets/             # Image assets, album artwork, and player icons
├── index.html          # Core application structure and markup
├── Major_Project.css   # Main stylesheet (layout, theme, custom controls)
└── README.md           # Project documentation
