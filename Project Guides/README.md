# Session 1: Brace yourselves, folks !

Let's get started with the basic image processing operations:
Install the dependencies.

```sh
$ pip3 install numpy
$ pip3 install opencv-python3 
$ pip3 install matplotlib 
$ pip3 install scikit-learn 
```

# Few basic image processing operations

1. Read an image using OpenCV
2. Resize the image
3. Grayscale the image
4. Perform affine transformations - Image Cropping, scaling, rotation 
(ref: https://setosa.io/ev/image-kernels/)
5. Color spacing (only red component)
6. **Mini project 1** - Live sketching 
    1.  Take a video (or use webcam)
    2.  Read the video frames
    3. Process each frame 
    4. Apply different kernels on image - sharpening, blurring, edge detection, binarization
    *Show your creativity, folks !*
    5. Write frame in the output video and display the frame for your reference
    6. Upload the output video on drive

Session-1:

Getting Acquiented with CNN networks
For that build CNN Network for Hand_written_Digit_recognization
Here uploaded Hand_written_Digit_recognization.ipynb is having a CNN Network with Network for two CONV2D layers,
maxpooling layer,two Droupout layers , two Dense Layers , Flatten Layer.

Session-2:
Getting through a new face_detection methods
1.Haar_cascade_classifier
2.HOG_with_Dlib
3.CNN_with_Dlib
4.Ultra_light_face_detection
5.YOLO Face

here uploaded files has implementation of that methods

Session-3:
Face_recognition
There are Various Method for Face_recognition
1.PCA
2.VGG_Face2

Here we have used Face_regonition_api for building the pipeline for it has 2 model
1. small model of 5 point predictor
2. large model of 68 point predictor
I have implemented both the models
the Feature_Extraction_with_small_model.ipynb has small model for feature extraction of dataset and it would
generate celeb_embb.pickle file
similairy,Feature_Extraction_with_large_model.ipynb has large model for feature extraction of dataset and it would
generate celeb_embb_lage.pickle file
Further for pipeline FR_with_Eucldien_Distance_5_point_model.ipynb has Face_Recognition API and we measure a distance
with Euclidien Distance for further more accuracy i have used SVM Classifier in API it is in file
FR_with_SVM_Classifier.ipynb
There is also a  pipeline FR_with_Eucldien_Distance_68_point_model.ipynb has Face_Recognition API and we measure a distance
with Euclidien Distance.
