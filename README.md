# Lab 5 — Face Detection and Clustering using KMeans

##  Overview
This project demonstrates face detection and clustering using computer vision and machine learning techniques. Faces are detected from an image using the Haar Cascade Classifier, and clustering is performed based on color features extracted from detected faces.

---

##  Aim
The aim of this experiment is to detect faces in an image and cluster them based on color features (Hue and Saturation) using the KMeans clustering algorithm. A template face image is also classified into one of the clusters.

---

##  Methodology

1. **Face Detection**
   - Used OpenCV Haar Cascade Classifier to detect faces in the image.

2. **Feature Extraction**
   - Converted detected face regions into HSV color space.
   - Extracted Hue and Saturation values as features.

3. **Clustering**
   - Applied KMeans clustering to group faces based on similarity.

4. **Template Classification**
   - Extracted features from a template image.
   - Predicted which cluster it belongs to.

5. **Visualization**
   - Scatter plots and thumbnails were used to visualize clusters.

---

##  Key Findings

- Faces were successfully detected using Haar Cascade.
- KMeans grouped faces based on color similarity.
- Cluster centroids indicated separation between groups.
- Template image was successfully classified into a cluster.
- Visualization helped understand cluster distribution.

---

##  Visualizations

###  Face Detection Output
![Face Detection](images/face_detection.png)

###  Cluster Visualization
![Cluster Plot](images/cluster_plot.png)

###  Final Classification Plot
![Final Plot](images/final_plot.png)

>  Note: Upload your screenshots inside a folder named **images** in this repository.

---

##  Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

##  Results
The clustering results show that faces with similar color features are grouped together. The template face was correctly assigned to the closest cluster based on extracted features.

---

##  Conclusion
This experiment demonstrates how unsupervised learning can be used to group similar data points. KMeans clustering effectively grouped faces based on Hue and Saturation features. The approach shows how feature extraction and clustering can be applied to real-world computer vision problems.

---

##  Future Improvements

- Use more features such as texture or embeddings.
- Try advanced clustering algorithms like DBSCAN.
- Improve face detection accuracy with deep learning models.
- Use larger datasets for better clustering.

---

## 👩‍💻 Author
Reshma Murali  

---
