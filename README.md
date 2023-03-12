# Image-Classification-Using-BoVW
# Abstract
This project aims to classify images using the Bag of Visual Words (BoVW) technique. The BoVW approach involves retrieving information, or feature descriptors, from an image and then training a classifier on histograms of these features to predict the class of a given data sample. Two different datasets were used in this study: objects dataset and flowers dataset. The object dataset was pre-divided into training and testing segments, while the flowers dataset was split into 80-20 train-test portions before proceeding with the analysis. Both support vector machine (SVM) and random forest algorithms were employed to train the classifier. The results of the study demonstrate the efficacy of the BoVW technique in classifying images, with SVM and random forest models achieving high accuracy rates on both datasets.
A detailed view of working methodology can be seen in the figure below.



![Methodology](https://user-images.githubusercontent.com/127693395/224572829-81a890bd-4df7-4403-b665-8a6c212b6369.png)




The project utilizes a range of software libraries and tools to accomplish its objectives. Specifically, the OpenCV-Python library is employed for image processing and visualization tasks, while the SIFT algorithm from OpenCV-Python is utilized for local feature extraction. The Scikit-learn library is used for k-means clustering to generate a visual vocabulary, and classification models such as SVM and Random Forest are employed for image classification.


# Environment Set up
In order to run the code, it is imperative to ensure that the relevant libraries are installed in the working environment. The libraries required for this purpose include:
OpenCV Python, Python, Scikit-learn, Matplotlib, Seaborn, and Numpy.
To install these libraries, one may run a command in the IDE with the package name appended with an exclamation mark. This will trigger the installation process via the "pip" package manager.
# The Folders Architecture
The main folder consists of test and train folders and each of these folder contain the subfolders of relevant classes.
# Optimal Clusters 
In order to find optimal numbers of visual words elbow method of K-means clustering is used. it is shown in the figure below.
# Optimal Parameters
In order to find optimal parameters of clustering algorithms, Grid search is used. The optimal parameters are given as shown in figure.
# Quantitative Results
Objects Dataset:
Flowers Dataset:
# Qualitative Results
Objects Dataset:
Flowers Dataset:
