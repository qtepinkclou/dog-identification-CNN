# dog-identification-CNN

### Motivation of the project

This project aims to identify dog breeds from images using Convolutional Neural Networks so that I will gain experience in handling CNN algorithms and better grasp the concept. Throughout the project I employed 3 different CNN algorithms that are either fully or partially trained across the dataset provided by Udacity. If the image fed to the algorithm is recognized as a human or dog face, most resembling dog breed type is presented as the trained algorithm’s prediction on what is shown in the image. If the algorithm does not recognize a human or a dog, it states so.

### Summary of the project

The project contains the following steps:

- A sub-algorithm for detecting human faces are created.
- A sub-algorithm for detecting dog faces are created.
- Own CNN algorithm is created for dog breed identification, trained using the dataset provided by Udacity.
- VGG16 CNN model is trained using transfer learning method for dog breed identification, trained using the dataset provided by Udacity.
- ResNET-50 CNN model is trained using transfer learning method for dog breed identification, trained using the dataset provided by Udacity.

### Summary of the results

The sub-algorithm called face detector used for detection of human faces was tested across 100 dog images and 100 human images with accuracy results listed below:

- Human faces detected in 100 human face images provided in ratio: 100%, therefore it has 100% accuracy.
- Human faces detected in 100 dog face images provided in ratio: 11%, therefore it has 89% accuracy.

The sub-algorithm called dog detector used for detection of dog faces was tested across 100 dog images and 100 human images with accuracy results listed below:

- Dog faces detected in 100 human face images provided in ratio: 0%, therefore it has 100% accuracy.
- Dog faces detected in 100 dog face images provided in ratio: 100%, therefore it has 100% accuracy.

Own model architecture has reached around 2.8% accuracy in correctly identifying the breed type of the test set of the dog images provided.

VGG16 model architecture has reached around 41.3% accuracy in correctly identifying the breed type of the test set of the dog images provided.

ResNET-50 model architecture has reached around 83.3% accuracy in correctly identifying the breed type of the test set of the dog images provided.

### Files in repository

- `README.md` : (this file) to explain the basics of the project
- `dog_app.ipynb` : Jupyter Notebook where all the calculations and results could be attained.
- `dog_app.html` : Html version of the finalized Jupyter Notebook for ease of access through a web browser application.

### Python libraries used in project are as follows:

- cv2
- keras
- re
- tqdm
- sklearn
- numpy
- matplotlib
- random
- PIL (implicitly)


### Acknowledgments

- License : MIT
- Data source : [Udacity](https://www.udacity.com/)

### References

- https://stackoverflow.com/questions/34980833/python-name-of-np-array-variable-as-string
- https://stackoverflow.com/questions/11854847/how-can-i-display-an-image-from-a-file-in-jupyter-notebook
- https://stackoverflow.com/questions/28663856/how-do-i-count-the-occurrence-of-a-certain-item-in-an-ndarray
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html
- https://regex101.com
- [Udacity](https://www.udacity.com/)


For more information please refer to blog post through this [link](https://medium.com/@qtepinkclou/write-an-algorithm-for-dog-identification-from-images-using-convolutional-neural-network-c33250a518f2).
