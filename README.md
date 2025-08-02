
# 🧠 Smoke Detection using YOLOv8

This project uses the Ultralytics YOLO model to detect smoke in images. It loads a pre-trained YOLO model and runs inference on a set of images, displaying and saving the results.

---

## 📁 Files

- `smoke.py`: Main Python script that loads the model and performs detection.
- `v4.pt`: YOLO model weights (must be in the same directory or provide a path).
- `smoke1.jpg`, `smoke3.jpg`: Input images for detection.

---

## 🚀 Requirements

Install required packages before running the script:

```bash
pip install ultralytics
```

---

## ▶️ How to Run

Make sure `v4.pt` and the input images are in the same directory as `smoke.py`.

Then run:

```bash
python smoke.py
```

The script will:
- Load the YOLO model
- Run detection on the input images
- Display and save the output images with bounding boxes (`result0.jpg`, `result2.jpg`)

---

## 📌 Notes

- `YOLO("v4.pt")` assumes the model file is a YOLOv8-compatible `.pt` file.
- This script uses `YOLOv8` via the [Ultralytics Python package](https://docs.ultralytics.com).
- You can add more images to the list or modify filenames as needed.
