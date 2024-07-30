## HealthNav
# Project Description
Health information needs are changing, and the way people seek information can be observed around the globe. Many people face challenges when looking online for health information regarding diseases, diagnoses, and different treatments. If a recommendation system can be developed for doctors and medicine using review mining, it will save a lot of time. In such a system, users face problems understanding heterogeneous medical vocabulary, as they are laymen. Users are confused because a large amount of medical information is available on different mediums. The idea behind the recommender system is to adapt to cope with the special requirements of the health domain related to users.

# Introduction
With the rise in the number of patients and diseases every year, the medical system is overloaded and has become overpriced in many countries. Most diseases involve consultation with doctors to get treated. With sufficient data, predicting a disease using an algorithm can be very easy and cheap. Prediction of disease by looking at symptoms is an integral part of treatment. In our project, we have tried to accurately predict a disease by analyzing the symptoms of the patient. We used 4 different algorithms for this purpose, achieving an accuracy of 92-95%. Such a system can have a significant potential in the medical treatment of the future. We also designed an interactive interface to facilitate interaction with the system. We attempted to visualize the results of our study and project.

# Database Collection
The dataset for this project was collected from a study by the University of Columbia performed at New York Presbyterian Hospital in 2004. The dataset is available [here](https://example.com).

# Libraries Used
1. **tkinter**  
   Tkinter is a standard GUI library in Python. Combined with tkinter, Python provides a fast and easy way to create a GUI. It provides a powerful object-oriented tool for creating GUIs. We used various widgets such as:
   - Button
   - Canvas
   - Label
   - Entry
   - Check Button
   - List box
   - Message
   - Text
   - Messagebox  
   We used tkinter to create an interactive GUI for our model.

2. **Numpy**  
   Numpy is the core library for scientific computing in Python. It provides powerful tools to deal with multi-dimensional arrays. It is a general-purpose array processing package. We used Numpy for handling data manipulation and processing in arrays while performing various operations.

3. **pandas**  
   Pandas is the most popular Python library for data analysis, providing highly optimized performance. It allows data analysis with Series (one-dimensional array) and DataFrames (two-dimensional data structure). We used pandas extensively to handle datasets for training and testing the algorithms.

4. **sklearn**  
   Sklearn is an open-source Python library implementing a range of machine learning, pre-processing, cross-validation, and visualization algorithms. It features tools for data mining and data processing. We used sklearn for classification algorithms like decision tree, random forest classifier, KNN, and Naive Bayes.

# Models
We used four different models to predict diseases:
1. **Decision Tree**  
   A versatile classification technique, effective in complex problems due to its high adaptability. It gives an accuracy of ~95%.

2. **Random Forest Algorithm**  
   A supervised learning algorithm used for classification and regression, achieving ~95% accuracy.

3. **K Nearest Neighbour (KNN)**  
   A supervised learning algorithm used for pattern recognition and data mining, achieving ~92% accuracy.

4. **Naïve Bayes**  
   Based on the Naïve Bayes theorem, this algorithm assumes that features make an independent and equal contribution to the prediction, achieving ~95% accuracy.

# GUI
We created a simple tkinter GUI consisting of labels, message boxes, buttons, text, title, and option menus. The GUI facilitates user interaction with the model.

# Modules
**Functions used:**
- `plotpercolumbdistribution()`
- `plotScatterMatrix()`
- `scatterplt`
- `scatterinp`

**Algorithms used:**
- Decision Tree
- Random Forest Classifier
- K Nearest Neighbour
- Naive Bayes Classifier

**Code for GUI setup:**
- Labels
- Messagebox
- Option Menu
- Buttons
- Result Display

# Conclusions
We created a system that predicts diseases based on symptoms. Such a system can reduce the rush at hospital OPDs and reduce the workload on medical staff. We achieved an average accuracy of ~94%. The system also stores user data for future reference and has an easy-to-use interface with various visual representations of data and results.

# References
**Dataset:** [University of Columbia Study](https://example.com)
