# Teachable Machine Image Classifier 💍📱⌚

A beautiful real-time image classifier built with [Teachable Machine](https://teachablemachine.withgoogle.com/) and [TensorFlow.js](https://www.tensorflow.org/js).

## Classes
- 💍 Ring
- 📱 Phone
- ⌚ Watch
- ⌚ Hunzallah Watch

## Features
- 🎥 Live webcam feed with scanning animation
- 📊 Animated confidence bars per class
- 🏆 Best-match banner with real-time emoji
- ⚡ FPS counter & confidence display
- 🔧 Configurable model URL (local or hosted)
- 🛡️ Smart error messages (file://, permissions, missing model)

## How to Run

> ⚠️ Browsers block webcam access on `file://`. You must serve via localhost.

```bash
# Python (recommended)
python -m http.server 8080

# Then open:
# http://localhost:8080
```

## Project Structure

```
teachable-machine/
├── index.html       ← Main app
├── my_model/
│   ├── model.json
│   ├── metadata.json
│   └── weights.bin
└── .gitignore
```

## Tech Stack
- [Teachable Machine Image Library](https://github.com/googlecreativelab/teachablemachine-community)
- [TensorFlow.js](https://www.tensorflow.org/js)
- Vanilla HTML / CSS / JavaScript
