# urban-video-annotation-paris

## 🎬 Urban Scene Video Annotation – Paris (5,145 Frames)

---

## 📌 Project Overview

This project showcases a frame-by-frame video annotation workflow applied to a 5-minute urban scene dataset (5,145 frames). The annotations capture dynamic real-world environments including moving vehicles, infrastructure, and street elements.

The goal of this project is to demonstrate practical skills in dataset creation for computer vision tasks such as object detection and urban scene understanding.

All annotations were created using CVAT and exported in industry-standard formats.

---

## 🛠️ Tools & Techniques

- CVAT  
- Frame-by-frame video annotation  
- Bounding boxes & polygon annotation  
- Dataset export (COCO & YOLO formats)  

---

## 🏷️ Annotation Classes

The dataset focuses on key urban objects:

**Primary Classes:**
- Car  
- Tower  
- Lamp  

**Class Grouping (for structured modeling):**
- Vehicles: Car,motorist,cyclist,bus  
- Infrastructure: Tower,crosswalk, 
- Street Elements: Lamp , taffic light

---

## ⚙️ Annotation Details

- Total Frames: 5,145  
- Annotation Type: Bounding Boxes + Polygons  
- Environment: Urban / Traffic / Landmark scenes  
- Scenario Challenges: Motion blur, occlusion, varying lighting conditions  

---

## 📸 Sample Results

### Before Annotation
Raw video frames extracted from the dataset.

### After Annotation
Annotated frames with bounding boxes and polygons highlighting:
- Vehicles in motion  
- Fixed structures (towers)  
- Street objects (lamps)  

(See `/samples/after_frames/

---

## 🧪 Quality Assurance Process

To ensure high-quality annotations, the following QA steps were applied:

- Maintained consistent labeling across all frames  
- Used tight bounding boxes aligned with true object boundaries  
- Excluded shadows and reflections from annotations  
- Verified annotations across sequential frames for temporal consistency  
- Reviewed edge cases including occlusion and motion blur  

---

## ⚠️ Challenges & Solutions

### Challenges:
- Motion blur in fast-moving vehicles  
- Partial occlusion of objects in dense scenes  
- Difficulty distinguishing object boundaries from shadows  
- Annotation loss due to label schema modification  

### Solutions:
- Applied consistent rules for labeling partially visible objects  
- Used frame continuity to infer object boundaries  
- Focused on true object edges rather than shadows  
- Reconstructed label schema and re-annotated affected objects with improved consistency  

---

## 📊 Annotation Metrics

- Total Frames: 5,145  
- Frames Annotated: (347)  
- Average Speed: ~180–220 frames/hour  
- Annotation Type: Bounding boxes & polygons  
- Classes Used: Car, Tower, Lamp  

---

## 📦 Dataset Format

The dataset is exported in:

- COCO JSON (for advanced ML pipelines)  
- YOLO TXT (for lightweight object detection models)  

---

## 🤖 Use Cases

This dataset can be applied in:

- Object detection model training (e.g., YOLO, Faster R-CNN)  
- Autonomous driving research  
- Urban scene understanding  
- Smart city and traffic analysis systems  

---

## 📁 Repository Strucure
urban-video-annotation-paris/
│── README.md
│── samples/
│ ├── before_frames/
│ ├── after_frames/
│── annotations/
│ ├── coco_annotations.json
│ ├── yolo_labels/
│── guidelines/
│ ├── labeling_rules.md
│── progress_log.csv



---

## 🧠 Key Learnings

- Developed strong attention to detail in frame-level annotation  
- Improved consistency across sequential video frames  
- Gained experience handling real-world annotation challenges  
- Applied QA workflows to ensure dataset reliability  

---

## 🚀 Future Improvements

- Expand annotation classes (pedestrians, roads, signage)  
- Increase dataset coverage across more frames  
- Implement object tracking (ID-based annotation)  
- Enhance dataset with segmentation masks  

---

## 👤 Author

Data Annotation & AI Training Portfolio Project
