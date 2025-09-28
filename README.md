
# 📸 Photo Booth Web Application

A modern, browser-based photo booth application that allows users to capture photos with real-time filters using their device's camera. Built with vanilla HTML5, CSS3, and JavaScript.





## ✨ Features

### 🎨 Real-time Filters
- **12 Creative Filters**: Normal, Grayscale, Vintage, Blur, Bright, High Contrast, Color Pop, Invert, Vibrant, Warm, Cool, and Dramatic
- **Live Preview**: See filters applied in real-time before capturing
- **One-Click Filter Switch**: Instantly change between different effects

### 📷 Photo Capture
- **3-Second Countdown**: Perfect timing for poses
- **Flash Effect**: Authentic photo booth experience
- **High Quality**: Captures photos at 1280x720 resolution
- **Instant Preview**: See your photo immediately after capture

### 🖼️ Photo Gallery
- **Built-in Gallery**: View all captured photos in a grid layout
- **Download Feature**: Save individual photos as PNG files
- **Photo Counter**: Track how many photos you've taken
- **Timestamp Records**: Each photo includes capture time

### 📱 Responsive Design
- **Mobile-Friendly**: Works on smartphones, tablets, and desktops
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Accessibility**: Proper contrast ratios and semantic markup

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and media elements
- **CSS3**: Modern styling, animations, and responsive design
- **JavaScript (ES6+)**: Camera API integration and interactive features
- **WebRTC API**: Real-time camera access
- **Canvas API**: Image processing and manipulation
- **CSS Filters**: Real-time visual effects

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Device with camera access
- Local web server (recommended for HTTPS)

### Installation & Setup

1. **Clone or Download**
   ```bash
   # Clone the repository (if using Git)
   git clone https://github.com/yourusername/photo-booth.git
   
   # Or download the HTML file directly
   ```

2. **Choose Your Method**:

   **Option A: Simple File Method**
   - Save the code as `photo-booth.html`
   - Double-click to open in your browser
   - Allow camera permissions when prompted

   **Option B: Using VS Code Live Server (Recommended)**
   - Install VS Code and the Live Server extension
   - Open the HTML file in VS Code
   - Right-click and select "Open with Live Server"

   **Option C: Using Python**
   ```bash
   # Navigate to your project folder
   cd path/to/your/project
   
   # Start a local server
   python -m http.server 8000
   
   # Open browser to http://localhost:8000
   ```

   **Option D: Using Node.js**
   ```bash
   # Install http-server globally
   npm install -g http-server
   
   # Start server in your project folder
   http-server
   ```

3. **Grant Permissions**
   - Allow camera access when prompted
   - Ensure good lighting for best results

## 🎯 How to Use

1. **Select a Filter**: Click on any filter button to apply it to the live camera feed
2. **Position Yourself**: Use the live preview to frame your shot
3. **Capture Photo**: Click the "📷 Capture Photo" button
4. **Get Ready**: A 3-second countdown will begin
5. **Strike a Pose**: Photo is automatically captured at the end of the countdown
6. **View Gallery**: Click "🖼️ View Gallery" to see all your photos
7. **Download**: Click the download button on any photo to save it

## 🎨 Available Filters

| Filter Name | Effect Description |
|-------------|-------------------|
| **Normal** | No filter applied - natural camera view |
| **Grayscale** | Classic black and white photography |
| **Vintage** | Warm sepia tones for a retro feel |
| **Blur** | Soft focus artistic effect |
| **Bright** | Enhanced brightness for better lighting |
| **High Contrast** | Dramatic contrast boost |
| **Color Pop** | Vibrant hue rotation for bold colors |
| **Invert** | Negative photo effect |
| **Vibrant** | Super saturated colors |
| **Warm** | Cozy warm color tones |
| **Cool** | Cool blue color tones |
| **Dramatic** | High contrast with enhanced saturation |

## 📁 Project Structure

```
photo-booth/
│
├── photo-booth.html          # Main application file
├── README.md                 # Project documentation
├── screenshots/              # Application screenshots
│   ├── photo-booth-main.png  # Main demo image
│   ├── main-interface.png    # Interface overview
│   ├── gallery-view.png      # Gallery screenshot
│   ├── desktop-view.png      # Desktop responsive view
│   ├── mobile-view.png       # Mobile responsive view
│   ├── filter-normal.png     # Normal filter example
│   ├── filter-vintage.png    # Vintage filter example
│   ├── filter-dramatic.png   # Dramatic filter example
│   ├── filter-grayscale.png  # Grayscale filter example
│   ├── filter-colorpop.png   # Color Pop filter example
│   └── filter-warm.png       # Warm filter example
└── demo/                     # (Optional) Demo videos
    └── photo-booth-demo.gif  # Animated demo
```

## 🔧 Technical Implementation

### Core Components

- **Camera Access**: Uses `navigator.mediaDevices.getUserMedia()` for webcam access
- **Video Processing**: HTML5 `<video>` element for live camera feed
- **Image Capture**: HTML5 `<canvas>` element for photo processing
- **Filter Application**: CSS `filter` property for real-time effects
- **State Management**: JavaScript class-based architecture
- **Photo Storage**: In-memory array storage (browser session only)

### Browser Compatibility

| Browser | Version | Supported |
|---------|---------|-----------|
| Chrome | 60+ | ✅ Full Support |
| Firefox | 55+ | ✅ Full Support |
| Safari | 12+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |
| Mobile Chrome | 60+ | ✅ Full Support |
| Mobile Safari | 12+ | ✅ Full Support |

## 🚨 Troubleshooting

### Common Issues & Solutions

**Camera Not Working**
- Ensure you've granted camera permissions
- Try using HTTPS (use Live Server or local server)
- Check if another application is using the camera
- Refresh the page and try again

**Blank Screen**
- Check browser console (F12) for error messages
- Ensure the HTML file is saved correctly
- Try using a different browser
- Verify your device has a working camera

**Filters Not Working**
- Update to a modern browser version
- Clear browser cache and reload
- Try disabling browser extensions
- Check if hardware acceleration is enabled

**Download Issues**
- Try right-clicking the download button and "Save As"
- Check browser download settings
- Ensure pop-ups are not blocked
- Verify sufficient storage space

## 🎥 Demo

![Demo GIF](./demo/photo-booth-demo.gif)
*Animated demonstration of the photo booth in action*

## 📱 How to Add Your Own Screenshots

To populate the README with actual screenshots:

1. **Take Screenshots**: Use your photo booth app and capture:
   - Main interface with camera preview
   - Different filter examples  
   - Gallery view with multiple photos
   - Mobile responsive views

2. **Create Folder Structure**:
   ```bash
   mkdir screenshots demo
   ```

3. **Save Images**: Place your screenshots in the `screenshots/` folder with these names:
   - `photo-booth-main.png` (main demo image)
   - `main-interface.png` (interface overview)
   - `gallery-view.png` (gallery screenshot)
   - `desktop-view.png` & `mobile-view.png` (responsive views)
   - `filter-[name].png` (individual filter examples)

4. **Optional**: Create an animated GIF demo and save as `demo/photo-booth-demo.gif`

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to the branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Ideas for Contributions
- Additional filter effects
- Face detection integration  
- Social media sharing features
- Video recording capability
- Custom filter creation tools
- Backend integration for photo storage
- PWA (Progressive Web App) features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Built with modern web standards (HTML5, CSS3, ES6+)
- Inspired by popular photo booth applications
- Thanks to the web development community for best practices
- Filter effects inspired by Instagram and Snapchat

## 📞 Support

If you encounter any issues or have questions:

1. **Check the troubleshooting section above**
2. **Search existing issues on GitHub**
3. **Create a new issue with detailed information**
4. **Include browser version and error messages**

---

**Made with ❤️ for creative photography and web development learning**

### 🏷️ Tags
`javascript` `html5` `css3` `photo-booth` `camera` `filters` `web-app` `frontend` `webrtc` `canvas-api`
