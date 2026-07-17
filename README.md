# 🖼️ Giffin

**Giffin** is a lightweight, browser-based GIF creator built with HTML, CSS, and JavaScript.

Create animated GIFs from your images directly in your browser—no installation, no server, and no image uploads.

---

## Features

- 📁 Import multiple images
- 🎞️ Create animated GIFs
- ⬆️ Reorder frames
- ❌ Remove frames
- ⏱️ Adjustable frame delay
- 👀 Live preview
- 💾 Download your finished GIF
- 🔒 Local processing (your images never leave your device)

---

## Screenshot

*Coming soon.*

---

## Getting Started

### Download

Clone the repository:

```bash
git clone https://github.com/yourusername/giffin.git
```

Or download the repository as a ZIP from GitHub.

### Run

Open `index.html` in any modern web browser.

No installation or build process is required.

---

## Usage

1. Click **Choose Files**.
2. Select one or more images.
3. Arrange the frame order.
4. Set the frame delay.
5. Click **Create GIF**.
6. Wait for encoding to finish.
7. Download the generated GIF.

---

## Supported Formats

### Input

- PNG
- JPG / JPEG
- WebP
- GIF
- BMP (browser support may vary)

### Output

- Animated GIF (.gif)

---

## Technologies

- HTML5
- CSS3
- JavaScript (ES Modules)
- gifenc

---

## Browser Compatibility

Works in most modern browsers including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Brave
- Opera

An internet connection is currently required the first time the application loads because the `gifenc` library is imported from a CDN.

---

## Project Structure

```text
giffin/
├── index.html
├── README.md
└── LICENSE (optional)
```

---

## Roadmap

Planned features include:

- Drag-and-drop frame ordering
- Per-frame delays
- FPS mode
- Frame duplication
- Reverse animation
- Ping-pong animation
- Resize before export
- Crop images
- Rotate and flip frames
- GIF optimization
- Animated WebP export
- APNG export
- Better progress indicator
- Offline bundled version (no CDN)

---

## Privacy

Giffin performs GIF creation entirely in your browser.

No images are uploaded or stored on any server.

---

## License

This project is licensed under the **MIT License**.

You are free to use, modify, distribute, and include this project in your own software, provided that the original copyright notice and license are included.

For full details, see the `LICENSE` file included with this repository.

---

## Credits

Created with HTML, CSS, JavaScript, and **gifenc**.

Designed as a simple, lightweight, local-first GIF creator.
