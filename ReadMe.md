## 🌈 Live & Static Virtual Spectrometer

A robust, dark-themed desktop application built with PyQt6 and OpenCV to analyze light spectra from live camera feeds and static images. 

## ✨ Features
- **Dual Input Modes:** Analyze spectra in real-time using a local USB webcam or an IP camera (e.g., DroidCam), or upload static images (PNG, JPG, WEBP).
- **Wavelength Calibration:** Perform a 2-point linear calibration to map pixel positions to physical wavelengths (nm).
- **Advanced Signal Processing:** Adjust noise averaging (smoothing) and peak detection sensitivity dynamically using UI sliders.
- **Vibrant Visualization:** Real-time plotting using Matplotlib with a sleek dark theme and glowing graph traces for intensity.
- **Data Export:** Easily save your spectral data (Pixel/Wavelength vs. Intensity) to a CSV file for further analysis in Excel or other tools.

## 🛠️ Prerequisites
Make sure you have Python 3.7+ installed. The application relies on several standard data science and computer vision libraries:
- `PyQt6`
- `pyqtdarktheme`
- `opencv-python`
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`

## 🚀 Installation
1. Clone this repository or download the source code (`spectrometer.py`).
2. Install the required dependencies using pip:
