Poultry Disease Classification using Transfer Learning
-----------------------------------------------------

Description:
-------------
This internship project uses transfer learning to classify poultry diseases based on image data. Pre-trained deep learning models like ResNet50 and EfficientNet were fine-tuned to detect diseases such as Avian Influenza, Coccidiosis, and Newcastle Disease, or to classify poultry products as Healthy vs Rotten.

Main Features:
--------------
- Uses TensorFlow/Keras with pre-trained CNNs.
- Classifies poultry images into Healthy or Rotten.
- Flask web app for image upload and prediction.
- Blog-style frontend to explain the project and share results.

Folder Structure:
------------------
project-folder/
¦
+-- app.py                     # Flask backend script
+-- healthy_vs_rotten.h5       # Trained Keras model
+-- templates/
¦   +-- index.html             # Web form for image upload
¦   +-- blog.html              # Blog homepage
¦   +-- single.html            # Detailed blog post
¦   +-- portfoliodetails.html  # Project case study page
¦   +-- ipython.html           # Static output from Jupyter Notebook
+-- static/
¦   +-- uploads/               # Folder to store uploaded images
+-- README.txt                 # This file
+-- requirements.txt           # List of required Python packages

How to Run:
-----------
1. Install dependencies:
   pip install -r requirements.txt

2. Run the Flask app:
   python app.py

3. Open in browser:
   http://127.0.0.1:5000/

Requirements:
--------------
- Python 3.7+
- Flask
- TensorFlow / Keras
- NumPy
- Pillow
- Bootstrap 5 (CDN)

Credits:
--------
Internship Project by [A.pavani Nandana]
Year: 2025

License:
--------
This project is for educational and academic use only.
