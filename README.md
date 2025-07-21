 🌊 Marine Trash Detection using Deep Learning

## 🧠 Overview

Marine pollution, especially plastic and other trash in oceans, poses a significant threat to marine life and ecosystems. This project aims to detect marine trash using computer vision and deep learning techniques, enabling scalable monitoring and cleanup efforts.

## 🎯 Project Goals

- Automatically detect and classify marine trash (plastic, bottles, nets, etc.) in underwater images.
- Build a deep learning model for accurate detection using a custom dataset.
- Contribute to environmental awareness and sustainability through open-source tech.

## 🛠️ Tech Stack

- **Python 3.x**
- **TensorFlow / PyTorch** 
- **OpenCV**
- **NumPy, Matplotlib, Pandas**
- **YOLOv5 / Traditional CNN / YOLOv8 / **
- **LabelImg** for annotation
- **Google Colab / Jupyter Notebook**

## 🗃️ Dataset
- Classes:
  - Plastic bottle
  - Fishing net
  - Can
  - Bag
  - General trash
- Format: COCO

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/SANJAYSS-SRM-26/Marine-Trash-Detection-using-Deep-Learning.git
cd marine-trash-detection
```

2. Create a virtual environment and install dependencies:
```bash
pip install -r requirements.txt
```

3. (Optional) For YOLOv5:
```bash
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
```

## 🧪 Training the Model

```bash
python src/train.py --epochs 50 --batch 16 --data data.yaml --img 640
```

Adjust configurations such as batch size and learning rate as needed.

Output will be saved in the `results/` folder.

## 📈 Future Work

- Increase dataset size and diversity
- Deploy as a real-time marine trash detection API
- Integrate with drones/ROVs for automated collection
- Explore semantic segmentation for better performance
