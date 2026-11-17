# KrishiNetra 🌱
### AI-Based Crop Disease Detection and Advisory System

KrishiNetra is an AI/ML-based project that aims to help farmers identify common crop diseases using leaf images. The system focuses on crops grown in Maharashtra and aims to provide disease-related information and recommendations to support better crop health management.

## Project Overview

Crop diseases can affect agricultural productivity and cause significant losses for farmers. Identifying a disease at an early stage can help farmers take timely action.

KrishiNetra uses machine learning and deep learning models to analyse images of plant leaves, identify the crop, and predict whether the leaf is healthy or affected by a disease.

## Objectives

- Identify the crop from an uploaded leaf image.
- Detect common bacterial, fungal, and viral crop diseases.
- Provide disease information and suitable recommendations.
- Build a simple website through which users can upload leaf images and view predictions.
- Support better and faster crop disease identification.

## Current Project Status

<escape> [x] </escape> Dataset collection and preparation completed.

<escape> [x] </escape> Data cleaning and preprocessing completed.

<escape> [x] </escape> Crop identification model development completed.

<escape> [x] </escape> Disease classification model training completed.

<escape> [x] </escape> Model testing and evaluation completed.

<escape> [x] </escape> Model checkpoints and training reports saved.

<escape> [x] </escape> Initial project architecture and workflow prepared.

<escape> [x] </escape> Website integration planned and interface development in progress.

**Current status:** The crop identification and disease classification models have been trained and tested. The remaining task is to connect the trained models with the website so that users can upload images and receive predictions through the interface. This integration is planned to be completed soon.

## Machine Learning Approach

The project uses two separate deep learning models:

### 1. Crop Identification Model
- Architecture: MobileNetV2
- Purpose: Identify the crop from the uploaded leaf image.
- Developed by: Person 1

### 2. Disease Classification Model
- Architecture: ResNet18
- Pretrained weights: ImageNet
- Purpose: Identify the disease or healthy condition of the selected crop.
- Developed by: Person 2

The disease classification model uses the crop information to restrict predictions to the relevant disease classes wherever applicable.

## Dataset Details

The project uses publicly available plant disease image datasets.

**1. PlantVillage Dataset**
- Used for training and evaluating disease classification.
- Contains images of healthy and diseased plant leaves.
- Covers multiple crop types and disease categories.

**2. MH-SoyaHealthVision Dataset**
- Used to add Maharashtra-relevant soybean leaf images.
- Includes soybean conditions such as:
  - Frog Eye Leaf Spot
  - Mosaic
  - Rust
  - Septoria Brown Spot
  - Healthy leaves

The datasets were cleaned, organised, labelled, and divided into training, validation, and testing sets. A date-grouped split was also prepared for the soybean images to reduce the possibility of similar capture-date images appearing across different splits.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Deep Learning Framework | PyTorch |
| Computer Vision | Torchvision, OpenCV, Pillow |
| ML Architecture | MobileNetV2, ResNet18 |
| Data Processing | NumPy, Pandas |
| Model Evaluation | Scikit-learn |
| Visualisation | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook, VS Code |
| Operating System | Windows with WSL Ubuntu |
| Hardware Acceleration | NVIDIA CUDA |
| Version Control | Git and GitHub |
| Planned Web Integration | HTML, CSS, JavaScript, Python backend |

## Model Evaluation

The disease classification model was evaluated using a separate test dataset.

**Initial evaluation results:**
- Test images: 5,678
- Overall accuracy: 98.64%
- Macro F1-score: 96.02%
- Weighted F1-score: 98.68%

The soybean classes showed comparatively lower performance than several other crops. Further analysis was performed using confusion matrices and visual inspection of misclassified images. A date-grouped dataset split was also prepared to make evaluation more reliable.

These results are from the earlier evaluation run. The final date-grouped training and evaluation results will be reported separately.

## System Workflow

1. User uploads a leaf image through the website.
2. The crop identification model predicts the crop.
3. The disease classification model analyses the leaf image for that crop.
4. The system displays the predicted disease or healthy status.
5. Relevant disease information and recommendations are presented to the user.

## Team Contributions

| Team Member | Responsibility |
|---|---|
| SAMKYAK| Dataset preparation and crop identification model |
| Pranav | Disease classification model, training and evaluation |
| Akanksha | Website development, backend and recommendation integration |

## Future Scope

- Complete integration of trained models with the website.
- Improve prediction accuracy using additional regional datasets.
- Add more crops and disease categories relevant to Maharashtra.
- Provide more detailed disease management recommendations.
- Make the website mobile-friendly and easier to use.
- Explore deployment so that farmers can access the system online.

## Conclusion

KrishiNetra is an attempt to use AI and deep learning to make crop disease identification easier and more accessible. The major machine learning models have been trained and tested, and the project is currently moving towards website integration. The final aim is to provide a simple system that can assist farmers in identifying crop diseases at an early stage.

---

**Project Name:** KrishiNetra  
**Project Type:** AIML / Multidisciplinary Project  
**Domain:** Agriculture and Artificial Intelligence  
**Status:** Model development and evaluation completed; website integration pending.
