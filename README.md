# Breast-Cancer-Wisconsin-Original-
Introduction:<br/>
Cancer remains one of the most formidable health challenges worldwide, affecting millions of lives annually. Among the various types of cancer, breast cancer is particularly prevalent, impacting millions of women globally. It is characterized by the uncontrolled growth of abnormal cells in the breast tissue, which can metastasize to other parts of the body if not detected and treated early. Timely and accurate diagnosis is paramount for effective treatment and improved patient outcomes. Early detection and accurate diagnosis significantly enhance survival rates and the effectiveness of treatment.<br/>
In the realm of medical diagnostics, machine learning algorithms have emerged as vital tools in assisting healthcare professionals with early detection and classification of diseases, including cancer. These algorithms analyze complex datasets to identify patterns and anomalies that may indicate the presence of cancer. The Breast Cancer Wisconsin (Original) dataset, which includes features from fine needle aspirate (FNA) samples of breast masses, is a valuable resource for developing and testing these diagnostic algorithms. By leveraging machine learning techniques, it is possible to enhance the accuracy and efficiency of breast cancer diagnosis, ultimately contributing to better patient care and outcomes. This report aims to explore the application of machine learning models to this dataset, with the goal of improving the prediction and classification of benign and malignant breast tumors.<br/>
<br/>
Dataset Introduction:<br/>
The Breast Cancer Wisconsin (Original) dataset is a widely utilized dataset in medical research and machine learning, particularly in the field of breast cancer diagnosis. Collected by Dr. William H. Wolberg at the University of Wisconsin Hospitals, Madison, from 1989 to 1991, it comprises 699 instances of fine needle aspirate (FNA) samples from breast masses. Each instance is characterized by 30 features, including attributes like clump thickness, uniformity of cell size and shape, marginal adhesion, and bare nuclei. The goal is to classify these samples into benign or malignant categories. This dataset has been instrumental in developing and testing various algorithms for accurate and early detection of breast cancer.<br/>
Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data. This grouping information appears immediately below, having been removed from the data itself:<br/>
Group 1: 367 instances (January 1989)<br/>
Group 2: 70 instances (October 1989)<br/>
Group 3: 31 instances (February 1990)<br/>
Group 4: 17 instances (April 1990)<br/>
Group 5: 48 instances (August 1990)<br/>
Group 6: 49 instances (Updated January 1991)<br/>
Group 7: 31 instances (June 1991)<br/>
Group 8: 86 instances (November 1991)<br/>
Total: 699 points (as of the donated database on 15 July 1992)<br/>
<br/>
Objectives<br/>
The primary objective of this project is to conduct a prediction analysis on the Breast Cancer Wisconsin (Original) dataset. In this notebook, we aim to:<br/>
1. Showcase the steps involved in data preprocessing, model training, evaluation, and interpretation.<br/>
2. Provide insights into feature importance and model performance metrics relevant to cancer diagnosis.<br/>
3. Demonstrate the practical implementation of machine learning models like Random Forest Classifier, Logistic Regression, SVM, etc.<br/>
Our steps:<br/>
Initially, the dataset will be downloaded and meticulously cleaned to address missing values, duplicates, and anomalies. Following this, a stratified random split will be performed to divide the data into training and test sets in an 80/20 ratio, ensuring preserving the benign and malignant sample distribution.<br/>
Next, four different machine learning models (Random Forest Classifier, Logistic Regression, SVM, KNN Classifier) will be applied, and 5-fold cross-validation will be utilized to determine the optimal hyperparameters for each model. These fine-tuned models will then be trained on the training set and evaluated on the test set, using accuracy as the primary metric for assessing the prediction of benign or malignant samples.<br/>
Finally, the analysis will conclude with a thorough examination of the process, supported by solid data evidence, to draw insights such as identifying key features that enhanceclassification accuracy, comparing model performances, and evaluating the impact of various data manipulation techniques. Visualizations will be employed throughout the project to communicate findings and improve the overall analysis effectively.<br/>
<br/>
References:<br/>
This breast cancer databases was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg.<br/>
1. O. L. Mangasarian and W. H. Wolberg: "Cancer diagnosis via linear programming", SIAM News, Volume 23, Number 5, September 1990, pp 1 & 18.<br/>
2. William H. Wolberg and O.L. Mangasarian: "Multisurface method of pattern separation for medical diagnosis applied to breast cytology", Proceedings of the National Academy of Sciences, U.S.A., Volume 87, December 1990, pp 9193-9196.<br/>
3. O. L. Mangasarian, R. Setiono, and W.H. Wolberg: "Pattern recognition via linear programming: Theory and application to medical diagnosis", in: "Large-scale numerical optimization", Thomas F. Coleman and Yuying Li, editors, SIAM Publications, Philadelphia 1990, pp 22-30.<br/>
4. K. P. Bennett & O. L. Mangasarian: "Robust linear programming discrimination of two linearly inseparable sets", Optimization Methods and Software 1, 1992, 23-34 (Gordon & Breach Science Publishers).<br/>
