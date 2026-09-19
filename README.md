# 📹 Real-Time ASCII Matrix Video Stream

A high-performance, real-time webcam to ASCII video converter built using Python and OpenCV. It captures live camera feeds, maps grayscale pixel intensity values to custom ASCII characters, and renders a live Matrix-style stream.

---

## 💡 Key Features

- **Zero Web Latency:** Renders directly on a native OpenCV canvas rather than web-wrapper DOM elements to maintain high frame rates.
- **Grayscale Quantization:** Maps pixel scalar values ($0–255$) directly to character density indices.
- **Matrix Aesthetics:** Renders dynamic green-on-black monospace font streams in real time.
- **Robust Event Polling:** Listens for `q`, `ESC`, and native window close (`X`) events to safely release camera drivers and system RAM.

---

## 🛠️ Installation & Setup

### 1. Download or Clone the Files
Ensure `ascii_cam.py` is in your project directory.

### 2. Create and Activate Virtual Environment
```bash
# Windows
python -m venv env
.\env\Scripts\activate

# macOS / Linux
python3 -m venv env
source env/bin/activate

bash---------

pip install opencv-python numpy


.
