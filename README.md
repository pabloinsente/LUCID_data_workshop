# Repository for the LUCID data-worshop summer 2019

## Sesion 1: Introduction to data science with R

This session will introduce you working with data in an “integrated development environment” or IDE using the freely available and widely-used software package R. We will briefly discuss what is meant by the term “data science,” why data science is increasingly important in Psychology and Neuroscience, and how it differs from traditional statistical analysis. We will then get a sense for how IDEs work by building, from data generated in the workshop, an interactive graph showing the structure of your mental semantic network.

Preparation for the workshop: (TO DO before arriving on Tuesday!)
– Install R, R Studio, and Swirl on your laptop following the instructions here: swirlstats.com/students  
– Start Swirl as instructed at the website and install the first course module by following the prompts  
– Run yourself through the first course module  

Time to complete: 45-60 minutes. Feel free to work with a partner or in groups!

## Sesion 2: Introduction to data science Tools

In this session we will set up several data science tools and environments: ATOM text editor, Jupyter, IRKernel (to run R on Jupyter), Git (Mac/Linux) or GitBash (Windows), GitHub account, GitHub Repository, a folder system and MATLAB. Then we will go over the basics of how to open, run and test each tool.
Preparation for the workshop:

– Download MATLAB (not install) for your OS (Mac/Windows/Linux) login in the Campus Software Library: it.wisc.edu/services/software  
– Download and install Atom text editor from atom.io  
– Download and install Git* from git-scm.com/downloads  
Windows users: when installing git, make sure you have the ‘GitBash Here’ selected.

## Session 3: Fitting and evaluating linear models

This session will introduce you to working with linear regression models using R. We will briefly discuss why linear regression is useful for Psychology and Educational research, using the topic of numerical cognition as an example.  We will play an educational game to generate our own data in the work shop, form predictions, and test those predictions by modeling gameplay performance. Through this exercise we will cover how to fit linear regression models, assess the fit of those models, plot linear relationships, and draw statistical inferences.

Preparation for the workshop:
– Be ready to uses R, R Studio, and Swirl on your laptop following the instructions here: swirlstats.com/students
–Install the “Regression Models” swirl module using the following commands in R
> library(swirl)
> swirl::install_course(“Regression Models”)
> swirl()

– Run yourself through lessons 1-6 (Introduction-MultiVar Examples) and continue based on your interest.

Time to complete: 45-60 minutes. Feel free to work with a partner or in groups!

## Session 4: Regression as Optimiation and regularization

This session will introduce the idea of optimization and regularization for fitting models.  We'll focus on least squares and polynomial models with examples of two different regularizers.
A rough outline:

    1. Linear regression as an optimization problem
    2. Curve fitting as optimization
    4. Model regularization
        - Small weights
        - Sparsity

Preparation for the workshop:
– Have a working Python3 distribution scikitlearn matplotlib, numpy, jupyter notebooks, and pandas

## Session 5: Pattern recognition and varieties of machine learning
Owen and Ashley will be co-facilitating this session.

This session will introduce basic concepts in machine learning. We will first discuss an overview of the steps involved in the machine learning process and the two main categories of machine learning problems. Then, we will walk through examples in both supervised and unsupervised learning, specifically classification using SVMs (discussing the regularization perspective) and clustering using the k-means clustering algorithm. We will conclude with brief discussion on other popular machine learning algorithms, when to use them, and good resources to learn more.

Preparation for the workshop: 
1. review session 4’s overview  
2. have a working Python3 distribution, scikit-learn, matplotlib, numpy, pandas, and jupyter notebook

## Session 6: Cross-validation
Today’s session will introduce the concept of cross validation. Using instructional videos from the Datacamp Machine Learning toolbox, we will walk through basic examples of cross validation in R using the caret package. We will be using two publicly available data sets in R for example code.

Our goals for this session are :

1) Learn why cross validation is important
2) Learn the basic steps of k-fold cross validation and repeated k-fold cross validation
3) Provide you with basic code to use on your own
Preparation for the workshop:

– Be ready to uses R, R Studio

– Read the Yarkoni & Westfall (2017) through page 5. You can stop reading at “Balancing Flexibility and Robustness: Basic Principles of Machine Learning.” The purpose of this article is just to get you thinking about the discussion we will have during session – it is not necessary to have a crystal clear understanding!

Yarkoni, T., & Westfall, J. (2017). Choosing prediction over explanation in psychology: Lessons from machine learning. Perspectives on Psychological Science, 12(6), 1100-1122.
Materials: Data Science Workshop Cross Validation in R

## Session 7: Neural Networks
Machine learning and artificial intelligence technology is growing at an impressive rate. From robotics and self-driving cars to augmented reality devices and facial recognition software, models that make predictions from data are all around us. Many of these applications implement neural networks, which basically allows the computer to analyze data similar to the way the human brain analyzes data.  

With recent advancements in computing power and the explosion of big data, we can now implement large models that perform end-to-end learning (deep learning). This means that we can create a model, feed it tons and tons of data, and the model will learn features from the data that are important for accomplishing the task.  

Session outline:
- Introduce the simplest neural network, the perceptron
- Discuss the general architecture for neural networks
- Implement a neural network to solve a hand writing recognition task
- Introduce deep learning (convolutional neural networks)
- Implement a deep neural network to solve a hand writing recognition task

Preparation for the workshop:  

Watch the following videos:
- https://www.youtube.com/watch?v=aircAruvnKk
- https://www.youtube.com/watch?v=uXt8qF2Zzfo&t=1973s (Watch first 12 min)
- https://www.youtube.com/watch?v=YRhxdVk_sIs

Pull session 7 materials from GitHub
- https://github.com/pabloinsente/LUCID_data_workshop
