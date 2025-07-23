# Image Outpainter App using SDXL with ControlNet

This React Native app allows users to generate outpainted images by providing an input image, its current aspect ratio, and the desired aspect ratio. It leverages an SDXL-based generative pipeline integrated with ControlNet for high-quality, context-aware outpainting.

- The backend API is built using **FastAPI**.
- **Session history** and **user feedback** are stored in **Appwrite**.

---

## Getting Started

### 1. Install Dependencies

```bash
npm install react-native-paper react-native-image-picker expo-image-picker expo-router expo-device expo-font expo-sharing expo-file-system @react-native-picker/picker @expo/vector-icons react-native-appwrite
```
Start the App
```bash
npm run start
```
This will generate the qr code for the expo app that can be run both on the android simulator as well as in the localhost as webapp

