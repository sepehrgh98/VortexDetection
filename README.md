# 🌀 Vortex Detection in Video using YOLOv5

This project applies YOLOv5, a cutting-edge object detection framework, to automatically detect and track vortex structures in scientific video data. It is suitable for real-time inference as well as offline batch processing.

---

## 📌 Features

- 🚀 Fast and accurate vortex detection
- 🎥 Video input/output with frame-by-frame annotation
- 🧠 Trained on custom-labeled vortex dataset
- 📈 Easily extensible for new datasets or vortex types

---

## 🛠️ Tech Stack

- [YOLOv5](https://github.com/ultralytics/yolov5) by Ultralytics
- PyTorch
- OpenCV
- Python 3.8+

---

## 🗂️ Project Structure

```bash
VortexDetection/ 
├── Image_collector.ipynb
├── Train.ipynb
├── requirements.txt
├── README.md
```

## 🔧 Installation

```bash
# Clone the project
git clone https://github.com/yourusername/vortex-detection-yolov5.git
cd vortex-detection-yolov5

# Install dependencies
pip install -r requirements.txt
```

## 🏋️‍♂️ Training

```bash
python train.py --img 640 --batch 16 --epochs 50 \
--data ../data/vortex.yaml --weights yolov5s.pt --name vortex_yolov5

```

## 📬 Contact

If you have any questions or feedback, feel free to contact us at:

📧 sepehrghamri@gmail.com