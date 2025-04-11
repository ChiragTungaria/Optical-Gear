
# Object Detection with ESP32-CAM - Edge Impulse Inferencing Library

This Arduino library enables real-time image and sensor inferencing on the ESP32-CAM and other supported boards using models trained with [Edge Impulse](https://www.edgeimpulse.com/).

## 📦 Features

- 📸 ESP32-CAM support for image-based inferencing using live camera input
- 📸 Camera input for image classification
- ⚡ Works with Edge Impulse models exported as Arduino libraries
- 🧠 Lightweight and efficient on-device ML

## 📁 Folder Structure

```
Object_Detection_Esp32_cam_inferencing/
├── library.properties
└── examples/
    ├── esp32/
    │   ├── esp32_camera/
    │   │   └── esp32_camera.ino
    │   ├── esp32_fusion/
    │   ├── esp32_microphone/
    │   └── esp32_microphone_continuous/
    └── nano_ble33_sense/
        ├── nano_ble33_sense_accelerometer/
        ├── nano_ble33_sense_accelerometer_continuous/
        ├── nano_ble33_sense_camera/
        ├── nano_ble33_sense_fusion/
        └── nano_ble33_sense_microphone/
```

## 🚀 Getting Started

1. **Train a model** using [Edge Impulse Studio](https://studio.edgeimpulse.com/).
2. **Export the model** as an Arduino library (`.zip`).
3. **Install this library** and the exported model library in the Arduino IDE.
4. **Upload an example** (like `esp32_camera.ino`) to your board.

## 🧰 Requirements

- [Arduino IDE](https://www.arduino.cc/en/software)
- ESP32 board package installed in Arduino
- ESP32-CAM with OV2640

## 🛠 Example Use Case: ESP32-CAM

Upload `examples/esp32/esp32_camera/esp32_camera.ino` to your ESP32-CAM to perform live image classification using the onboard camera and your Edge Impulse-trained model.

## 🧑‍💻 Authors

Developed using tools and model formats provided by [Edge Impulse](https://www.edgeimpulse.com/).

## 📄 License

This project is released under the MIT License.
