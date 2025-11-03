# 🛡️ Threat Detection Model V1

A Roboflow-powered object detection model trained to identify civilian-grade drones from aerial imagery.  
Model V1 was developed as an entry-level research and annotation project to explore AI-driven threat detection within counter-UAS contexts.

---

## 🚀 Overview
This project demonstrates the full cycle of AI model development:
- Dataset design and annotation  
- Model training and evaluation  
- Metric tracking and visual performance analysis  

The model was trained on **200 annotated drone images** using **YOLOv5**, achieving strong detection accuracy despite the small dataset size.

---

## 📊 Model V1 Performance

| Metric | Value |
|:--------|:------|
| **Precision** | 0.89 |
| **Recall** | 0.91 |
| **mAP@0.5** | 0.92 |
| **mAP@0.5–0.95** | 0.64 |

---

## 🧠 Methodology
1. **Data Collection** – Civilian drone imagery gathered from publicly available datasets and verified sources.  
2. **Annotation** – Bounding boxes manually drawn and validated in Roboflow.  
3. **Model Training** – YOLOv5, trained for 50 epochs using Google Colab.  
4. **Evaluation** – Standard COCO metrics used for precision, recall, and mAP analysis.

---

## 📂 Repository Structure
