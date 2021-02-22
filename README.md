# SureStart Spring 2021

## Responses

<ins>**Day 1: February 8, 2021**</ins>

Throughout the SureStart program, I hope to gain a better understanding about machine learning and artificial intelligence. I am excited to deepen my understanding on how AI and machine learning works. Additionally, I want to gain more confidence speaking about technical topics and more experience working within a team environment. I want to improve my soft skills while continuing to develop my technical skills. I am looking forward to working with and getting to know the wonderful people in the program. I am grateful for the opporunity to learn from my team, mentor, and the sure start team!

<ins>**Day 2: February 9, 2021**</ins>

My team and I had our first team meeting today. We were able to settle on a time for our next three scrums. After completing the action item for today, I am more familiar with machine learning models and algorithms. I learned that machine learning allows computers to learn without being programmed to do so. The two types of learning are supervised ML and unsupervised ML. Supervised ML consists of two major subcategories regression ML systems (systems that attempt to plot predicted values on a continuous spectrum) and classification ML systems (systems that seek a prediction of yes/no). It was fascinating to read how a program makes determinations on new data. Additionally, used Jupyter notebook for the first time to became more familiar with the Scikit-learn library.

**1. What is the difference between supervised and unsupervised learning? **

Supervised learning incorporates a data set for training a program to determine accurate interpretations for data introduced into the system. In contrast, unsupervised learning relies on a program finding patterns and relationships between a given data set and makes correlations between data without the use of training examples.

**2. Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries. **

Scikit-Learn is a machine learning library that provides supervised and unsupervised learning algorithms. The library is mainly used for data modeling, but it is not necessarily helpful for visualizing data. Scikit-Learn is used with other libraries such as Graphviz, Pandas, etc. to assist in the analysis, visualization, and manipulation of data.

<ins>**Day 3: February 10, 2021**</ins>

**1.What are “Tensors” and what are they used for in Machine Learning?**

Tensors are multidimensional data arrays that communicate between the edges of mathematical operations wihin a data flow graph. Tensors can be genrealized to illustrate plane vectors, covectors, and linear operators. In machine learning they are used to train deep learning models and the operations within neural networks. 

**2. What did you notice about the computations that you ran in the TensorFlow
programs (i.e. interactive models) in the tutorial?**

The computations illustrated how the tensor arrays are computed together, how constants do not change the value of the tensors, and that "sess.close()" will close the session automatically.
Additionally, after loading in the data set, you will get a better insight on how the model performs.  

<ins>**Day 4: February 11, 2021**</ins>

I feel that cyber security is a general problem within our technological filled world, more so, having the ability to use artificial intelligence to predict when an attack may happen could be substantial. I found the data set below that contains data regarding cyber security malware. The deep learning algorithm I think would work best for a solution is a generative adversarial neural networks. As an unsupervised algorithm that can work to distinguish genuine samples from fake samples and generate patterns, I think it would be able to predict malicious attacks through the classification of different malware. 
Link to data set: https://www.kaggle.com/c/malware-classification/data

<ins>**Day 5: February 12, 2021**</ins>
I developed a neural network model: Sarcasm Dectector.

<ins>**Day 8: February 15, 2021**</ins>
I learned about convolutional networks and how they work.
The action item for this day involve extending a CNN to use the mnist dataset.

<ins>**Day 9: February 16, 2021**</ins>
Today, I learned about the different types of bias. Biased data affects ML learning and can lead to algorithmic bias that causes programs to make unjust and harmful decisions. It is important when collecting data to evaluate for fairness and inclusion and by using bias mitigation techniques, we can build more ethical AI. During the talk, I learned that humans are implicitly biased. I am more aware of factors that lead to bias and how they can be addressed; the presentation lined up very well with what I learned today.  

**1. How do you think Machine Learning or AI concepts were utilized in the design of this game?**

The game gave little time to think about each candidate as the rounds went on. As I was choosing the candidates, I did not realize the implicit bias that I possessed until the ML algorithm was deciding which candidates to hire based on my data. The AI techniques were evident in the hiring process when the machine began choosing the candidates based on data I gave it. Additionally, the machine needed a larger data set to accomadate ML learning and borrowed so from a bigger corporation. The problem was that the larger data set may not have held my same standards for applications. While playing the game, I did not really take into account how the categories and color of the people could ellict implict bias from me as I mostly looked at the chart and tried to select a well rounded individual. Some of the people the machine let go, I would have hired which made me more aware of how ML can be affected by bias from my data.

**2. Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, andequitable? Please reflect on why you selected this specific biased model.**

A real-world example of a biased machine learning model is racism within US health care. Gernarally, minorities are more likely to face racism and discrimination within the US health care system. This example can be applied to both paitients and health care workers; doctors and nurses may be discriminated against and the target of bias by patients and on the other hand patients have also faced prejudice from health care professionals. I believe that being more open minded and aware of our own implicit biases can create a more fair and inclusive model. I chose this model specifically because as humans we take our health seriously, and I don't believe that healthcare professionals or patients should have to face bias and racism when providing or receiving treatment.

<ins>**Day 10: February 17, 2021**</ins>

A convolutional neural network specializes in image recognition and completing computer vision tasks. CNNs accomplishes the task through a pooling mechanism and a fully connected layer. The pooling or convolution mechanism breaks up an image into features and analyzes them and pass its output into a fully connected layer that uses said output to predict the best label for the image.
A fully connected neural network, on the other hand, is a NN architecture in which all neurons on one layer is connected to all neurons in the next. This type of architecture is inefficent for computer vision tasks as images are considered very large input for a NN and would require a fully connected NN to contain a huge number of connections as well as network parameters. 

The type of layers in a CNN includes:
- convolutional: "filter" pass over image, scanning pixels, and create a map that predicts the class which of each feature
- pooling: reduce amount of information for each feature obtained by the previous layer
- fully connected input: "flattens" output of previous layer into a single vector for the next layer
- first fully connected: takes the input from the feature anaylsis and applies weights
- fully connected output: provides final probabilities for each label

<ins>**Day 11: February 18,2021**</ins>

I developed a CNN for MNIST Handwritten Digit Classification dataset, evaluated the performance of the model, and made predictions for test data by following this guide: https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-from-scratch-for-mnist-handwritten-digit-classification/

I reviewed neural networks and some common terminology including: training data, test data, and loss function. Additionally, I reviewed the common steps in a machine learning task:
1) Preparing the data
2) Building the Network
3) Evaluating the Model

I also learned concepts such as overfitting, "one-hot encoded" vectors, and became more familiar with the MNIST dataset.
