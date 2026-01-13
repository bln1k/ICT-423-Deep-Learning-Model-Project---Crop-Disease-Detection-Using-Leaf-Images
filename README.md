# ICT-423-Deep-Learning-Model-Project---Crop-Disease-Detection-Using-Leaf-Images
Deep learning project for plant disease classification from leaf images using CNN from scratch + baselines (MLP &amp; SVM)

# Plant Disease Classification Project
Deep learning project for identifying plant diseases from leaf images using CNN from scratch + MLP and SVM baselines.  
Achieves up to **93%** validation accuracy on a reduced 11-class dataset.

## Implementation Notes
- The entire project is implemented in **one Google Colab notebook** (`plant_disease_detection_dl_model.ipynb`)  
  This is a common and efficient approach for Colab-based ML/DL projects.
- Code is organized into clear, numbered sections (virtual modules) for readability and modularity.
- All requirements are met: from-scratch CNN, 2 baselines, proper splits, seeds for reproducibility, PEP 8 style (mostly), well-commented.

## How to Reproduce
1. Open the notebook directly in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/plant_disease_classification.ipynb)
2. Run cells top to bottom (dependencies are installed in the first cell).
3. Dataset: Reduced PlantVillage-style (~25k images, 11 classes) – upload to Google Drive and mount it in the notebook.

## Requirements
- Python 3.8+
- Google Colab (free tier with GPU recommended)
- Installed packages: see first cell of notebook (torch, torchvision, scikit-learn, matplotlib, seaborn, etc.)

## Project Highlights
- CNN from scratch: 98%+ val acc
- MLP baseline: ~78.5%
- SVM + HOG/Color: ~72.1%
- Full results table and bar chart in Section 8

## Hardware
- Trained on Google Colab T4 GPU
- ~12–16 GB RAM needed for full dataset

All random seeds set to 42 for reproducibility.
