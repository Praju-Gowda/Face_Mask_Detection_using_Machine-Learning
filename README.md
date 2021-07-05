# Face_Mask_Detection_using_Machine-Learning
This project is to detect the face mask of the person. Here i have used some dataset which i have taken from the Kaggle websit and i have trained the model to detect the facemask. Dataset contain both with mask and without mask images. .

Below are the dependancies needed to run the model. I have put these in a requirements.txt file, so from your cmd prompt you can install by"pip install -r requirements.txt
tensorflow>=1.15.2=>Used for Classification, Prediction, Understanding, Discovering, Prediction and creation.
keras==2.3.1=>is a API designed for human beings not machines, used to make deep learning networks easier with the help of backend engine.
imutils==0.5.3=> A series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, and displaying Matplotlib images easier with OpenCV and both Python 2.7 and Python 3.
numpy==1.18.2=> Numpy makes many mathematical operations used widely in scientific computing fast and easy to use, such as: Vector-Vector multiplication, Matrix-Matrix and Matrix-Vector multiplication, Element-wise operations on vectors and matrices (i.e., adding, subtracting, multiplying, and dividing by a number ), Element-wise or array-wise comparisons
opencv-python==4.2.0.*=>OpenCV is a huge open-source library for computer vision, machine learning, and image processing.
matplotlib==3.2.1=>Matplotlib is widely used in SciPy as most scientific calculations require plotting of graphs and diagrams. It is an open-source programming language, free to use. MATLAB is a commercial platform.
scipy==1.4.1=>The SciPy library is the fundamental library for scientific computing in Python. It provides many efficient and user-friendly interfaces for tasks such as numerical integration, optimization, signal processing, linear algebra, and more. The SciPy library is composed of a number of modules that separate the library into distinct functional units.

Here we detect the face mask using keras, tensorflow, mobilenet and opencv. And i also applied on a live video camera, with further improvements these types of models could be integrated with the CCTV cameras to detect and identify people without masks. The face mask detector didnt use any morphed masked images dataset. The model is accurate and since the MobileNetV2 architecture is used, it's also computationally efficient and thus making it easier to deploy the model to embedded system.

To run the model go to the file path from your cmd prompt and type python followed by file name. It will take sometime to train the model, model and png images will be saved. We only develop the model for mask detection, i dont have any face detector model. In order to do face detection i have downloaded couple of file which is used in face detection. The idea here is with the help of face detector file we will detect the face and with the help of deep learning model (mask_detector.model) we are going to detect the mask. And for camera operation we use openCV. 

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of covid-19. This project can be integrated with embedded systems for application in airports, railways station, schools and colleges to ensure that public safety guidlines are followed.



https://user-images.githubusercontent.com/74085170/124424708-20772480-dd85-11eb-8c34-f44b30b29a4a.mp4




