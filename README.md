# 🖼️ Giffin

**Giffin** is a simple, browser-based GIF creator. It lets you combine multiple images into an animated GIF without installing any software. Everything runs locally in your web browser.

## Features

- 📁 Upload multiple images
- 🔄 Reorder frames
- ⏱️ Adjustable frame delay
- 👀 Live GIF preview
- 💾 Download your finished GIF
- 🌐 Runs entirely in the browser
- 🖥️ No server required

## Getting Started

### Option 1: Download

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Start creating GIFs.

### Option 2: Host Locally

Serve the project with any static web server.

Examples:

```bash
python -m http.server
```

or

```bash
npx serve
```

Then visit:

```
http://localhost:8000
```

or the URL provided by your server.

## How to Use

1. Click **Choose Files**.
2. Select the images you want.
3. Arrange them in the desired order.
4. Set the frame delay.
5. Click **Create GIF**.
6. Wait for rendering to finish.
7. Download your new GIF.

## Supported Formats

### Input

- PNG
- JPG / JPEG
- WebP
- GIF (first frame is used)

### Output

- Animated GIF

## Browser Compatibility

Giffin works in modern versions of:

- Chrome
- Edge
- Firefox
- Opera
- Brave

Safari support may vary depending on browser version.

## Built With

- HTML5
- CSS3
- JavaScript
- GIF.js

## Project Structure

```
giffin/
├── index.html
└── README.md
```

## Roadmap

Planned features include:

- Drag-and-drop frame ordering
- Per-frame timing
- Crop and resize tools
- Reverse animation
- Ping-pong animation
- Image filters
- GIF compression
- APNG export
- Animated WebP export
- Video-to-GIF conversion
- Dark and light themes

## License

This project is released under the MIT License.

## Credits

Created with HTML, CSS, and JavaScript.

Animated GIF encoding is powered by GIF.js.
