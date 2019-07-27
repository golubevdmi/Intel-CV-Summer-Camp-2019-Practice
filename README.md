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
