# Intel CV Summer Camp 2019 Practice

## Requirements

1. OpenCV v.4.1.0. Modules: dnn
2. OpenVino.

## Practice 1

### Main Tasks:

Develop an application to open the original image from a file and save the resulting image to a file;
1. filter to translate the image in shades of gray;
2. filter for resizing images.

### Additional Tasks:
1. Develop an application to open an image / video / video stream from a webcam and display data on the screen.
2. Develop a filter for random mixing parts of the picture (see the game "tag").
3. Implement a filter to remove noise using the Gauss method.

## Practice 2

### Main tasks:

1. Download the trained network `squeezenet1.1`.
2. Develop an application for the classification of images.
    
### Additional tasks:

1. Add the possibility of classification by part of the image specified by the user.
2. Implement output of class names (a list of class names is contained in the file `* .labels`).
3. Implement the top-3 (top-5, top-10) output of classes proposed by the classifier.

## Practice 3

### Main tasks:

1. Download the model for detecting objects [mobilenet-ssd] [mobilenetssd].
2. Develop an application for detecting objects on images usingnets of `mobilenet-ssd`.
3. Implement the output image on the screen and draw a rectangle around the objects.
  
### Additional tasks:

1. Implement recording video with rectangles around objects in a file.
2. Implement the functions of statistics (how many objects were in the frame, how much time, etc.).

## Practice 4

### Main tasks:

1. Read the source code tracking.
2. Download the model for detecting objects [mobilenet-ssd] [mobilenetssd].
3. Run the example `practice-4`, make sure it works.
4. Change the code so that you can detect a subset of classes from all available classes.

### Additional tasks:
1. Implement the matching of objects independently, using the brute force algorithm, or write your own version of the Hungarian algorithm.
2. Change the code so that when a neural network detects one object in the video as several objects of different classes, the tracker considers this object as one class.
