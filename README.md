# 📸 Photo Booth Web Application

A modern, browser-based photo booth application that allows users to capture photos with real-time filters using their device's camera. Built with vanilla HTML5, CSS3, and JavaScript - **everything in a single file!**

## 🎮 Live Demo

**Just download and run!** This is a single-file application - no installation required.

### Quick Preview
- **Modern Photo Booth Interface** with live camera preview
- **12 Creative Filters** applied in real-time
- **Responsive Design** works on desktop and mobile
- **Built-in Gallery** with download functionality

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
- No additional software required!

### Installation & Setup

1. **Download the File**
   ```bash
   # Download from GitHub
   wget https://github.com/yourusername/photo-booth/raw/main/photo-booth.html
   
   # Or simply click "Download" on GitHub and save the HTML file
   ```

2. **Run the Application**:

   **Option A: Direct Browser (Simplest)**
   - Double-click `photo-booth.html` 
   - Opens directly in your default browser
   - Allow camera permissions when prompted

   **Option B: Using VS Code Live Server (Recommended for Development)**
   - Install VS Code and the "Live Server" extension
   - Open `photo-booth.html` in VS Code
   - Right-click and select "Open with Live Server"
   - Automatically opens in browser with HTTPS support

   **Option C: Local Server (For HTTPS)**
   ```bash
   # Using Python (if installed)
   python -m http.server 8000
   # Then open: http://localhost:8000
   
   # Using Node.js (if installed)
   npx http-server
   ```

3. **That's It!**
   - No dependencies to install
   - No build process required
   - Just one HTML file with everything included

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
└── photo-booth.html          # Complete application (HTML + CSS + JavaScript)
```

**That's it!** This is a single-file application with everything included:
- HTML structure
- CSS styling and animations  
- JavaScript functionality
- All dependencies embedded

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

## 🚀 Try It Now!

1. **[Download photo-booth.html](https://github.com/yourusername/photo-booth/raw/main/photo-booth.html)** (Right-click → Save As)
2. **Double-click** the downloaded file
3. **Allow camera access** when prompted
4. **Start taking photos!** 📸

## 💡 Key Advantages

- **Zero Installation**: Just download and run
- **No Dependencies**: Everything included in one file
- **Cross-Platform**: Works on Windows, Mac, Linux
- **Mobile Friendly**: Responsive design for phones/tablets
- **Privacy First**: No data sent to servers, all processing local

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Download and modify** `photo-booth.html`
3. **Test your changes** thoroughly
4. **Create a Pull Request** with your improvements

### Ideas for Contributions
- Additional filter effects (add new CSS filters)
- UI/UX improvements (better styling, animations)
- New features (face detection, video recording)
- Mobile optimizations
- Accessibility improvements
- Performance enhancements

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
