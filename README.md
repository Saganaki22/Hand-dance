

<div align="center">

# Hand Dance
  
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/MediaPipe-0F9D58?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/Canvas%20API-Native-orange?style=for-the-badge" alt="Canvas API" />
  <img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white" alt="WebRTC" />
</div>

<div align="center">

[**🚀 Live Demo**](https://drbaph.is-a.dev/Hand-dance/)

</div>

---


https://github.com/user-attachments/assets/ed07552c-3d09-428c-abb2-7591ccf41427


---

## ✨ Features

Hand Dance is an interactive psychedelic art generator that transforms hand movements into mesmerizing visual effects using real-time computer vision. Simply show your hands to the camera and watch as your fingertips create stunning particle animations.

### Visual Effects
- **Kaleidoscope** - 4-way symmetrical patterns that mirror your movements
- **Spiral Galaxy** - Swirling cosmic patterns following your hands
- **Fireworks** - Explosive bursts emanating from fingertips
- **Liquid Flow** - Fluid, flowing particles with physics simulation
- **Mandala** - 8-way sacred geometry patterns
- **Aurora** - Northern lights effect with ethereal trails
- **Plasma Storm** - Electric energy fields and lightning effects
- **Water Waves** - Ripple waves expanding from fingertips

### Interactive Controls
- **Opacity Control** - Adjust transparency of effects and camera overlay
- **Rotation Speed** - Control particle rotation and swirl intensity
- **Animation Speed** - Modify particle movement velocity
- **Particle Density** - Adjust the number of particles generated
- **Camera Toggle** - Show/hide camera feed behind effects
- **Landmarks Toggle** - Display hand tracking points for debugging
- **Fullscreen Mode** - Immersive full-screen experience
- **FPS Monitor** - Real-time performance indicator

### Technical Features
- Real-time hand tracking using MediaPipe
- Supports up to 2 hands simultaneously
- Mobile-responsive design with touch controls
- Optimized performance for smooth 60fps rendering
- Advanced particle systems with physics simulation
- Multiple blend modes for different visual effects
- Adaptive quality based on device capabilities

## 🚀 Getting Started

### Prerequisites
- Modern web browser with camera support
- Camera permissions enabled
- Stable internet connection (for MediaPipe CDN)

### Installation

1. **Download or Clone**
   ```bash
   git clone https://github.com/yourusername/hand-dance.git
   cd hand-dance
   ```

2. **Serve the Files**
   
   Since the app uses MediaPipe from CDN, you can simply open `index.html` in your browser, or serve it using any web server:
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in Browser**
   Navigate to `http://localhost:8000` and allow camera permissions when prompted.

## 🎮 Usage

1. **Camera Setup** - Allow camera access when prompted
2. **Hand Position** - Hold your hands in front of the camera
3. **Effect Selection** - Use the dropdown menu to choose different visual effects
4. **Customize** - Adjust sliders for opacity, rotation, speed, and particle density
5. **Controls** - Toggle camera visibility, landmarks, and fullscreen mode
6. **Mobile** - Works on mobile devices with touch controls

### Tips for Best Results
- Ensure good lighting for optimal hand detection
- Keep hands within the camera frame
- Try different effects with various hand movements
- Adjust particle density based on your device performance
- Use fullscreen mode for immersive experience

## 🛠️ Technical Details

### Dependencies
- **MediaPipe Hands** - Google's hand tracking solution
- **HTML5 Canvas** - For rendering particles and effects
- **WebRTC** - Camera access and video streaming

### Browser Compatibility
- Chrome 88+ (Recommended)
- Firefox 85+
- Safari 14+
- Edge 88+
- Mobile browsers with camera support

### Performance Optimization
- Adaptive particle limits based on device type
- Efficient particle culling and lifecycle management
- Frame rate monitoring and adjustment
- Mobile-specific optimizations

### Architecture
- **MediaPipe Integration** - Hand landmark detection
- **Particle System** - Custom physics engine for effects
- **Effect Engine** - Modular system for different visual modes
- **Responsive UI** - Touch-friendly controls and mobile optimization

## 📱 Mobile Support

Hand Dance is fully optimized for mobile devices with:
- Touch-friendly interface
- Responsive layout adaptation
- Performance optimization for mobile GPUs
- Gesture-based controls
- Portrait and landscape support

## 🎨 Effect Details

Each effect uses different particle behaviors and rendering techniques:

- **Symmetrical Effects** (Kaleidoscope, Mandala) use mathematical transformations
- **Physics-Based Effects** (Flow, Waves) simulate real-world physics
- **Explosive Effects** (Fireworks, Plasma) use radial particle emission
- **Organic Effects** (Aurora, Spiral) use smooth, flowing animations

## 🔧 Customization

The application supports extensive customization through:
- Real-time parameter adjustment
- Effect switching without restart
- Camera overlay control
- Performance monitoring
- Debug visualization

## 📊 Performance

Optimized for smooth performance across devices:
- **Desktop**: 60fps at 1080p with high particle density
- **Mobile**: 30-60fps with adaptive quality
- **Low-end devices**: Automatic quality reduction for stable performance

---
