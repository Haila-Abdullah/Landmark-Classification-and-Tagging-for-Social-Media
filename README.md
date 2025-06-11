# Landmark Classification & Tagging for Social Media

## 📌 Project Overview

Photo sharing and storage services heavily rely on **location data** to enhance user experience through features such as:

- Automatic suggestion of relevant tags  
- Location-based photo organization  
- Improved search and personalized recommendations

However, many photos uploaded to these services lack this metadata due to:

- Cameras without GPS capabilities  
- Metadata being manually removed for privacy reasons

To address this, the project focuses on **automatically detecting and classifying landmarks** in images to infer their locations. Given the vast number of landmarks worldwide and the massive volume of uploaded images, manual labeling is not feasible.

This project covers the entire machine learning pipeline, including:

- Data exploration and preprocessing  
- Designing and training Convolutional Neural Networks (CNNs)  
- Comparing the accuracy of different CNN architectures  
- Exporting the best performing model  
- Building interactive app for landmark classification 

![Landmarks Example](images/landmarks-example.jpg)

*Examples from the landmarks dataset: a road in Death Valley, the Brooklyn Bridge, and the Eiffel Tower.*

---

## 📚 Project Steps

1. **Training a CNN from Scratch**  
   Build and train a CNN to classify landmarks. Focus on data visualization, processing, and network architecture. Export the best model with TorchScript.  
   *Notebook: `cnn_from_scratch.ipynb`*

2. **Using Transfer Learning**  
   Explore and apply pre-trained models for landmark classification. Train, evaluate, and export the best transfer learning model.  
   *Notebook: `transfer_learning.ipynb`*

3. **Deploying the Model**  
   Build an interactive app for users to classify landmarks using the trained model.  
   *Notebook: `app.ipynb`*

## 🚀 How to Run

1. Clone this repository  
2. Create and activate a Python environment (e.g., with conda or virtualenv)  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt

