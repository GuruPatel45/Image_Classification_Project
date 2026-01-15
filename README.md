# Image_Classification_Project
Cat vs Dog Image Classification using Transfer Learning with Explainable AI (Grad-CAM). Built using TensorFlow, Keras, and MobileNetV2, including confidence scores and visual heatmap interpretations.

## Project Overview
This project focuses on binary image classification to distinguish between
cats and dogs using deep learning and transfer learning techniques.
A pretrained MobileNetV2 model is used as the backbone.

To enhance model interpretability, the project integrates Explainable AI
using Grad-CAM to visualize important regions influencing predictions.

---

## Key Features
- Cat vs Dog image classification
- Transfer Learning using MobileNetV2
- Confidence-based predictions
- Explainable AI using Grad-CAM
- Heatmap, heap map (grayscale attention), and overlay visualization
- Clean and reproducible project structure

---

## Model Architecture
- Base Model: MobileNetV2 (pretrained on ImageNet)
- Pooling: Global Average Pooling
- Classifier: Dense layer (binary output)
- Framework: TensorFlow & Keras

---

## Project Structure
The complete project and dataset folder structure is documented separately
to keep the repository clean and reproducible.

📄 **Project Structure File:**  
[project_structure.txt](project_structure.txt)

This file explains how to recreate the dataset and project structure
without uploading large image files.

---

## Explainable AI (Grad-CAM)
Grad-CAM is used to:
- Highlight important regions in an image
- Understand model decision-making
- Improve transparency and trust

Generated outputs:
- Grayscale attention map (heap map)
- Colored Grad-CAM heatmap
- Overlay on the original image

---

## Dataset Information

### Dataset Source
The dataset is based on the Microsoft Cats vs Dogs dataset available on Kaggle:

https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset

### Dataset Assumptions
- Images are RGB
- Recommended image size: 224 x 224
- Folder names represent class labels
- Images should be correctly labeled

---

## Recreating the Dataset Structure
To recreate the dataset locally:

1. Create a folder named `dataset`
2. Inside it, create `train` and `test`
3. Inside each, create `cat` and `dog`
4. Place images into their respective folders

The complete structure is documented in `project_structure.txt`.

---

## How to Run
1. Clone the repository
2. Prepare the dataset as per the documented structure
3. Load the trained model (`cat_dog_model.keras`)
4. Run the notebook/script to:
   - Predict Cat or Dog
   - Display confidence score
   - Visualize Grad-CAM outputs

---

## Limitations
- Model performance depends on dataset quality
- Extreme lighting or occlusion may affect predictions
- Intended for educational and internship purposes

---

## Future Improvements
- Multi-class image classification
- Web deployment (Streamlit / Flask)
- Batch image prediction
- Performance monitoring dashboard

---

## Author
Guru Patel  
Machine Learning Project 
