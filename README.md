# Chest X-Ray Object Detection System

## 🔍 Overview
This project focuses on medical image analysis using a deep learning pipeline that combines **object detection**, **image enhancement**, and **natural language processing (NLP)** for automated interpretation of chest X-ray images.

### 🧠 Key Features

- **YOLOv8-Based Detection:** Utilizes the YOLOv8 model to detect and localize anomalies in chest X-rays such as nodules, opacities, or infiltrates.
- **GAN-Based Enhancement:** Enhances image clarity using a Generative Adversarial Network (GAN) to support better diagnosis and visualization.
- **NLP for Voice Descriptions:** Converts detection results into **natural language descriptions** and generates corresponding **voice output**, making the system user-friendly for both doctors and patients.

---

## ⚙️ Technologies Used

- **YOLOv8** - for fast and accurate object detection on medical images.
- **GAN (SRGAN/ESRGAN)** - for high-quality image resolution enhancement.
- **Transformers/NLP Toolkit** - to generate and synthesize descriptive text.
- **Text-to-Speech (TTS)** - for converting the diagnosis into voice.

---

## 🛠️ How It Works

1. **Input:** Chest X-ray image is uploaded.
2. **Detection:** YOLOv8 identifies and draws bounding boxes on abnormal regions.
3. **Enhancement:** GAN enhances image quality for better visual clarity.
4. **Description:** Detected results are translated into textual summaries using NLP.
5. **Audio Output:** The text is converted into voice for accessibility.

---



