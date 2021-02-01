# Facial-key-points-detection

As explained on the Kaggle platform, we seek to predict keypoint positions on face images. This is a precursor step to analysing faces for various specific purposes -

to track faces in images and video (for example, for cinematic motion capture)
to assess facial expressions, normal and dysmorphic
biometrics, which includes facial recognition
Ultimately our model can also be tested against 1,783 images of data hosted on the Kaggle platform. An RMS error measure will be determined by the platform using expected results it keeps secret.

Inference: We seek to predict the x,y coordinates of 15 facial keypoints using images

Model: For the machine learning model we will use Keras to set up a convolutional neural network solution. Keras sits on top of Tensorflow and greatly simplifies the process of building a model.

Features: Each image comprises 96x96 pixels. We have up to 7049 images with full or partial keypoints to work with. Feature transformation produces additional images with known (transformed) keypoints.

Train: Fit and Test. steps to avoid overfitting : Dropout, Batch Normalization, Early stopping during fitting, Regularization (Activity reg., Weight reg.), Hyperparameter tuning

cost is a function of parameters (RMSE) ; objective minimizes cost.
