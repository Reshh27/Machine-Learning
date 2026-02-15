# Lab 5 — Face Detection and Clustering using KMeans


This project demonstrates face detection and clustering using computer vision and machine learning techniques. Faces are detected from an image using the Haar Cascade Classifier, and clustering is performed based on color features extracted from detected faces.



##  Aim
The aim of this experiment is to detect faces in an image and cluster them based on color features (Hue and Saturation) using the KMeans clustering algorithm. A template face image is also classified into one of the clusters.


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



##  Key Findings

- Faces were successfully detected using Haar Cascade.
- KMeans grouped faces based on color similarity.
- Cluster centroids indicated separation between groups.
- Template image was successfully classified into a cluster.
- Visualization helped understand cluster distribution.


##  Visualizations

###  Face Detection Output
![Face Detection](images/face_detection.png)

###  Cluster Visualization
![Cluster Plot](images/cluster_plot.png)

###  Final Classification Plot
![Final Plot](images/final_plot.png)

>  Note: Upload your screenshots inside a folder named **images** in this repository.



##  Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook



##  Results
The clustering results show that faces with similar color features are grouped together. The template face was correctly assigned to the closest cluster based on extracted features.

<img width="1377" height="673" alt="Screenshot 2026-02-15 230150" src="https://github.com/user-attachments/assets/2b7ac26e-9660-4bad-9fec-a216472e305a" />
<img width="1343" height="687" alt="Screenshot 2026-02-15 230226" src="https://github.com/user-attachments/assets/fe6d5bdd-b9b7-4a02-a40d-7b0930cdf907" />
<img width="1326" height="701" alt="Screenshot 2026-02-15 230529" src="https://github.com/user-attachments/assets/13c63154-443e-4232-b6d6-b3e3ca4e63d7" />
<img width="1268" height="684" alt="Screenshot 2026-02-15 230548" src="https://github.com/user-attachments/assets/e2acfcd3-82b7-47c3-94c4-c942f7ef57cd" />





##  Conclusion
This experiment demonstrates how unsupervised learning can be used to group similar data points. KMeans clustering effectively grouped faces based on Hue and Saturation features. The approach shows how feature extraction and clustering can be applied to real-world computer vision problems.



##  Future Improvements

- Use more features such as texture or embeddings.
- Try advanced clustering algorithms like DBSCAN.
- Improve face detection accuracy with deep learning models.
- Use larger datasets for better clustering.



##  Author
Reshma Murali  

