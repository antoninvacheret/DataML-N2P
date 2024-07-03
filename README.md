# DataML-N2P
Data Analysis and Machine Learning course for the Erasmus Mundus Degree in Nuclear Physics.

## Teaching progam 

support medium : google colab, Kaggle notebook, jupyter notebook

### Session 1 : Introduction to the Course and machine learning in N&P Physics - AV

Course :
in this session we will start with a brief overviez of machine learning over the last 40 years and type of machine learning and developments in AI. Type of machine learning tasks and where AI is used in theoritical and experimental physics. 
in a second part we will review the use of python libraries used for data analysis and ML. Small examples with pandas, get used to the environment provided, tests some simple code to explore some data. Use of github repository - to later provide project on the repo.
introduction to tensors in pytorch - numpy etc

Practical session KB : 
Continue on the the introduction of tools and data manipulation with exercises  

### Session 2 : Data manipulation, visualisation, basics of data analysis, intro to tensors - GL/AV
Course : introduction to the pdml_extended datasets : type of datasets (reco, low level, time series, images, visualisation methods (PCA), applying selection cuts, correlations, embedding visualisation algorithms (t-SNE, UMAP). Introduction to basic statistical methods. More advanced examples with pandas - Quick introduction to streamlit / plotly / seaborn for interactive plots. Example of how to prepare a labelled dataset for Pytorch/Keras.

Practicals  GL :
study another type of datasets : time series of pulses / other
look at averaging the pulses, visualise each categories, represent those categories and connect to raw data - Visualise dataset on webpage

### Session 3 : Learning from data, Linear Regression, Shallow and deep NN - AV 
Course : introduction to supervised learning, loss function, linear regression, shallow NN and activation functions. Deep NN and look at a first training workflow. 

Practicals : building a simple NN to perform a classification. learn how to build a NN in Scikitlearn and Pytorch and train the model on one of the datasets seen previously. 
Look at effects of changing the number of neurons.

### Session 4 : Applications to classification and regression tasks  - AV

Course - KB : look at classification tasks and common issues in physics data, extension to anomaly detection. Regression tasks, examples of determining energy, quantification of errors, interpretability of results. Relation between classification and regression tasks. confusion matrix, ROC curve and useful metrics.

Practicals : compare shallow and deep NN. Look at effect of type of loss function. accuracy, confusion matrix, decision - tradeoff between accuracy and purity, comparison of ROC curve between simple cut selection and NN. 

### Session 5 : Training, optimisation, ensembling & interpretation - AV
Course : how to design the best model ? No free lunch theorem review of training and optimisation of architectures. Random search, bayesian optimisation. model scaling and compute power. Overview of uncertainties and how to quantify model uncertainties. 
Ensembling methods and algorithms, BDTs, ensembles of NN. Methods to interpret the data.  

Practicals - KB : 

### Session 6 : Other Deep learning layers and model architectures - AV
Course : Intruduction to other type of layers : Convolution layers, CNNs, GNNs, RNN, Auto-Encoders, GANs. Use cases and benchmark of models depending on the application. 

Practicals - IM : Use the dataset to benchmark the models. Look at what has learned a 1D-CNN based on pulse data for instance. Look at the Scinet Auto-encoder (intro to next session). 2D CNN on pdml data. 

### Session 7 : ODE Solvers - AV
Course : Take session from Morten's course and PINNs models based on summer school material.  

Practicals - GM : 

### Session 8 : Transformers and foundation models - AV
Course : Overview and dive into self-attention layer in details. Building a transformer architecture - presenting the applications of transformers. Some introduction to NLP and models used (BERT and GPT models). Scaling law of foundation models. Introduce the tutorial task about anomaly detection. 

Practicals - IM : Application to anomaly detection - used already trained models to explore anomaly detection - in physics hiding different events in different datasets.  

### Session 9 : Hypothesis testing I - GL
Course : Formalism of frequentist approach and Bayes. Chi2 fit. Estimator of the mean. Calculations.

Practicals - GM : Dataset measurement. Estimation of mean, chisquare, likelihood. 

### Session 10 : Hypothesis testing II - GL
Course : Metropolis and Langevin approach. Algorithms and parameters.    

Practicals - GM : Application to Oscillation analysis/ equation of state (neutron star) of MCMC. Sterile oscillation search. 


Responsable : Antonin Vacheret
Enseignants : D. Cussol, G. Lehaut, A. Vacheret.

## Course content 

The rapid rise of Artifical Intelligence (AI) in the last few decades has been quite remarkable. Machine learning a sub-field of AI is very well suited to automate many of the tasks related to modelisation and data analysis found in Nuclear and Particle Physics data. The large amount of multi-dimensional data commonly processed can be deciphered using ML methods which in many areas has surpassed traditional approaches. Those methods enable the learning of complicated concepts and dependencies based on representation of the data.
In this course, we will take a look at the basic concept and methods of machine learning from the point of view of a physicist, exploring and using datasets that are commonly found in theoritical and experimental physics. We will gradually move from simple architectures to more advanced one and cover the most common applications and pitfall of ML with the aim of giving all the basic knowledge needed to start applying those tools.  

The course will cover the following concepts and methods :

Statistical analysis and optimization of data; 
Visualisation of data and embedding;
Basic concepts, expectation values, variance, covariance, correlation functions and errors; 
Shallow and deep neural nets; 
Architecture components and current models;
Classification and regression tasks; Foundation models;  
Central elements of Bayesian statistics and modeling;
Hypothesis testing, Markov chains, Metropolis-Hastings algorithm;

All the above topics will be supported by examples, hands-on exercises and project work.


## Learning outcomes

The course introduces a variety of central algorithms and methods essential for studies of data analysis and machine learning. The course is tutorials and project-based and through the various projects, normally two, the students will be exposed to fundamental research problems in these fields, with the aim to reproduce state of the art scientific results. The students will learn to develop and structure comprehensive machine learning codes and get acquainted with computing practices and learn to handle solving scientific problems with ML. A good scientific and ethical conduct is emphasized throughout the course. More specifically, after this course you will :

* Understand the basics about data analysis, selection and visualisation
* Learn the basics of building and training various type of Machine Learning models
* Be able to use the most common Machine Learning methods to new problems
* Have learned about Transformers and Foundation models
* Have learned how to implement statistical methods for hypothesis testing.
* Have learned to use some of the most common Python libraries used in Artificial intelligence
* Have gained knowledge of central aspects of Monte Carlo methods, Markov chains Monte Carlo and their possible applications

## Prerequisites

Basic knowledge in programming and numerics.




















