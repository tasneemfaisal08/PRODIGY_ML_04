# PRODIGY_ML_04
Develop a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

# DataSet  
 Kaggle link : https://www.kaggle.com/gti-upm/leapgestrecog

# Explanation
1.Data Loading and Preprocessing:
     The code traverses through the LeapGestRecog dataset directories, loads images, resizes them, and normalizes them.
     It encodes the labels into numerical values and one-hot encodes them.

2.Data Augmentation:
     Added ImageDataGenerator to perform data augmentation, which helps prevent overfitting by exposing the model to more varied data.    

3.Model Definition and Training:
     A CNN model is defined using TensorFlow/Keras.
     Training with Augmentation,The model is trained using augmented data.

4.Evaluation and Visualization:
    The model's performance on the test dataset is evaluated and printed.
    A confusion matrix is plotted, and a classification report is printed to evaluate the performance in detail.
