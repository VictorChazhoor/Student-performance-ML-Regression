# Problem Statement 
This data set consists of the marks secured by the students in Maths, Writing and Reading and background of the students from which they belong.
## Dataset

The dataset used is the StudentsPerformance.csv(https://www.kaggle.com/spscientist/students-performance-in-exams). 

The target variable is **Writing score**. **Writing Score** is scored by students in writing test. So, it can be predicting if **Reading score** is given.

**Target Variable: Writing Score**
<br>
**Mean Writing Score:** 68.054
<br>
**Max Writing Score:** 10
<br>
**Min Writing Score:** 100


## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.


