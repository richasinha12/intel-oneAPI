# intel-oneAPI

#### Team Name - Ai Enthusiast 
#### Problem Statement - Learning Equality - Curriculum Recommendations ( open innovation in education)
#### Team Leader Email - richasinhacps@gmail.com




## A Brief of the Prototype:
  
  The idea of the above code is to recommend learning resources to a student based on their learning style. The code uses machine learning techniques such as clustering and PCA to identify the student's learning style, and then recommends resources that are similar to those used by students with similar learning styles.
The code also uses Intel® AI Analytics Toolkits to access and process learning resources data. The SYCL/DCP++ Libraries are used to accelerate machine learning algorithms on Intel hardware.

the code performs the following steps:

Preprocess the data
Create a neural network model
Train the model
Recommend resources
Run the code
Recommendation through Flask web application.

Overall, the code demonstrates how machine learning and neural networks can be used to recommend learning resources to students based on their learning style. The use of Intel® AI Analytics Toolkits and SYCL/DCP++ Libraries enables the code to run faster on Intel hardware, making it more efficient and scalable.

  



## Tech Stack: 
1 SYCL/DPC++: SYCL/DPC++ is used for running the machine learning models on various devices, such as CPUs, GPUs, and FPGAs, which significantly improves the performance of the models.

2.Intel AI Analytics Toolkits: The toolkits provide optimized libraries for deep learning and machine learning, which enable faster and more accurate computation.

3.Pandas and NumPy: Pandas and NumPy are used for data manipulation and analysis, which allows us to preprocess the data efficiently and perform operations on the data.

4.Scikit-learn: Scikit-learn is used for clustering the data and preprocessing the data.

5.Keras: Keras is used for building the neural network model and training it.

   



## Step-by-Step Code Execution Instructions:
  This Section must contain set of instructions required to clone and run the prototype, so that it can be tested and deeply analysed
  
 To execute the prototype using the above code, follow these step-by-step instructions:

1 Clone the repository:
git clone https://github.com/<username>/<repository>.git
Replace <username> and <repository> with your GitHub username and the name of the repository respectively.

2 Install the required libraries:
pip install pandas numpy tensorflow intel-tensorflow sklearn intelai-analytics-zoo

3 Open a command prompt or terminal and navigate to the cloned repository.

4 Run the prototype by executing the following command:
  python prototype.py
  This will run the 'main' function which will preprocess the data, create the machine learning model, train it, and generate recommendations for the example       student with ID 1.

5 The recommended learning resources for the example student will be printed to the console.

Note: Before running the prototype, ensure that you have a compatible Intel CPU/GPU installed and configured to work with the Intel AI Analytics Toolkit. If you encounter any issues, refer to the Intel AI Analytics Toolkit documentation for troubleshooting steps.


  
## What I Learned:
   Write about the biggest learning you had while developing the prototype
   
  The biggest learning i learnt that how to use Intel AI Analytics Toolkits to access and process learning resources data. It demonstrates how to use the sycl module from the intelai.federated package to execute the resource recommendation process on a CPU device. This package can be used to enable Federated Learning on Intel hardware.
   
  Additionally, the application of unsupervised learning techniques like K-means clustering and PCA for grouping students based on their learning styles. This prototype uses K-means clustering to group students based on their learning styles and PCA for dimensionality reduction to improve the clustering performance.
