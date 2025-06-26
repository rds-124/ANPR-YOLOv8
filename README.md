# 🚘 ANPR-YOLOv8: Automatic Number Plate Recognition 

![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Used-critical)
![OpenCV](https://img.shields.io/badge/OpenCV-Enabled-success)
![OCR](https://img.shields.io/badge/OCR-EasyOCR-lightgrey)
![Pandas](https://img.shields.io/badge/Pandas-Used-purple)
![Colab](https://colab.research.google.com/assets/colab-badge.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-informational)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Colab-yellow)
![License](https://img.shields.io/badge/License-MIT-blueviolet)
![Status](https://img.shields.io/badge/Status-Active-green)

> Detect, localize, and extract vehicle license plates from images using **YOLOv8 + OCR** for fast, reliable Automatic Number Plate Recognition (ANPR).

---

## 🚀 About the Project

**ANPR-YOLOv8** is a deep learning-based system for detecting and recognizing vehicle number plates in images or video. It:

- 🚗 Detects license plates in real-time using YOLOv8
- 🔠 Extracts text using OCR (EasyOCR)
- 📊 Logs and displays detected plate data
- 📦 Trained on Indian vehicle plates, customizable for other regions

Ideal for **traffic monitoring**, **parking systems**, and **security applications**.

---

## 🎯 Key Features

* ⚡ Real-time number plate detection (YOLOv8)
* 🔍 Text recognition using OCR (EasyOCR)
* 📷 Works on images, videos, or live webcam
* 📁 Logs detected plate numbers to a CSV file
* 🧠 Easy model retraining for custom datasets

---

## 📚 Project Structure
```bash
ANPR-YOLOv8/
├── Licence_Plate_Detection_YOLO_V8.ipynb # Jupyter Notebook for end-to-end pipeline
├── runs/ # YOLOv8 detection output
├── data.yaml # Dataset config for YOLOv8
├── train.log # Training log output
├── dataset/ # Sample images (optional)
├── .gitignore
└── README.md # Project documentation
```


---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/rds-124/ANPR-YOLOv8.git
cd ANPR-YOLOv8
```
```bash
pip install -r requirements.txt
# or manually:
pip install ultralytics opencv-python easyocr pandas
```
```bash
jupyter notebook Licence_Plate_Detection_YOLO_V8.ipynb
```

## 🔍 How It Works

1. YOLOv8 detects the bounding box around number plates.  
2. Cropped plate regions are extracted.  
3. EasyOCR reads text from the cropped plates.  
4. Plate numbers are printed and logged to CSV.

---

## 🧠 Model Details

- YOLOv8n (nano) model used for speed — can switch to larger variants.
- Trained on Indian license plate dataset (`data.yaml` can be edited).
- OCR with EasyOCR, supporting multiple languages.
- Logs plate text to CSV for later analysis.

---

## 📈 Future Improvements

* 🎥 Real-time video stream support
* 🌍 Multi-country license plate format detection
* 🧪 Database integration for plate validation
* 📲 Web/GUI deployment using Flask or Streamlit

---

## 🙏 Acknowledgements

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [OpenCV](https://opencv.org/)
- [Google Colab](https://colab.research.google.com/)

---

## 📅 License

This project is licensed under the **MIT License**.

---

## 📧 Contact

**Rohith D**  
[LinkedIn](https://www.linkedin.com/in/rohith124) | [GitHub](https://github.com/rds-124)


