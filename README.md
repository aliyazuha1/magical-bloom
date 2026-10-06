# ✦ Magical Bloom AR

An interactive Augmented Reality web experience that allows users to grow a magical flower from the palm of their hand using real-time hand gestures.

The project uses the device camera and MediaPipe Hands to detect hand movements. The right-hand pinch gesture controls the flower's blooming level, while the left palm acts as the location where the flower grows.

## 🌸 Features

- Real-time hand tracking using MediaPipe Hands
- Camera-based Augmented Reality experience
- Gesture-controlled flower blooming
- Right-hand pinch gesture controls bloom intensity
- Left palm acts as the flower's anchor point
- Animated flower petals, stem, leaves and glowing effects
- Particle streams and magical sparkles
- Interactive visual HUD showing hand detection and bloom percentage
- Runs directly in a web browser

## 🎮 How It Works

The application uses the device camera to capture live video and MediaPipe Hands to detect hand landmarks.

### Left Hand
The left palm determines where the flower grows.

### Right Hand
The distance between the thumb and index finger controls the flower's growth.

- 👐 Fingers apart → Seed / small bloom
- 🤏 Fingers pinched → Full bloom

As the pinch becomes stronger, the flower gradually grows and produces additional visual effects.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML Canvas
- MediaPipe Hands
- Web Camera API
- jsDelivr CDN

## 📁 Project Structure

```text
Magical-Bloom/
│
├── index.html
└── README.md
