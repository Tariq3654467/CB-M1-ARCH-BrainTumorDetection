# 🧠 Brain Tumor Detection using YOLOv11 & SAM2

This project uses advanced deep learning models — **YOLOv11** for tumor detection and **SAM2 (Segment Anything Model)** for precise brain tumor segmentation from MRI images.

---

## 📌 Project Highlights
- Detects brain tumors in MRI scans using YOLOv11
- Refines tumor boundaries with SAM2 segmentation
- Visual output with bounding boxes and masks
- Built using PyTorch, OpenCV, and Meta AI’s SAM2

---

## 🗂️ Folder Structure

BrainTumorDetection/ ├── brain_tumor_code/ │ ├── tumor_detection_yolo_sam.ipynb │ ├── test_images/ │ └── ... ├── requirements.txt ├── .gitignore └── README.md

yaml
Copy
Edit

---

## 🛠 Installation

1. Clone this repo:
```bash
git clone https://github.com/YOUR-USERNAME/BrainTumorDetection.git
cd BrainTumorDetection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🧠 How to Run
Open the main notebook:

bash
Copy
Edit
jupyter notebook brain_tumor_code/tumor_detection_yolo_sam.ipynb
Upload or use sample images in test_images/.

The notebook will:

Load YOLOv11 model

Run detection on the image

Pass detected region to SAM2 for segmentation

Show segmented tumor area with mask overlay

🔗 Download Pretrained Models
These are required but not included in the repo due to size.

YOLOv11 Weights: Download yolo11n.pt

SAM2 Weights: Download sam2_b.pt

Place them in a folder called models/ (which is ignored in Git).

🧪 Sample Results

Original Image	YOLOv11 Detection	SAM2 Segmentation
📊 Dataset
Used a public dataset of brain MRI scans:

Kaggle Brain Tumor Dataset (replace if using a different one)

⚠️ Disclaimer
This project is for research and educational purposes only. It is not approved for clinical use.

🤝 Contribution
Pull requests are welcome. Please open an issue first to discuss major changes.

📧 Contact
Feel free to reach out via GitHub or [your email/LinkedIn].

yaml
Copy
Edit

---

## ✅ 2. Want Me to Clean Your `requirements.txt`?

If you share the current content of your `requirements.txt`, I can remove unnecessary packages like `notebook`, `ipykernel`, or those from your Anaconda environment that aren't needed for deployment.

Just paste it here, and I’ll return a cleaned version!
