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
### 2. Start the App
```bash
npm run start
```
This will generate the qr code for the expo app that can be run both on the android simulator as well as in the localhost as webapp

---
## App Demo Run



https://github.com/user-attachments/assets/1e8759e9-629d-4cbf-bd73-382ccfd0e81d

## App UI
<img width="2136" height="1113" alt="image" src="https://github.com/user-attachments/assets/ec1984ef-8015-479f-8516-dda78fd8d2cb" />
<img width="2166" height="1106" alt="image" src="https://github.com/user-attachments/assets/5bd7d3a2-44c0-49c9-bb06-927296bfc2b8" />

## Sample Results
<img width="2183" height="1218" alt="image" src="https://github.com/user-attachments/assets/a02b28bb-14bc-4db6-976f-44f4f552f106" />
<img width="2206" height="1187" alt="image" src="https://github.com/user-attachments/assets/c17c0491-6f4c-463d-bc58-14d50a09b0d4" />


