# DL-Inverse-Kinematics
## Open Projects 2022

<p align = "center">
<img src = "https://github.com/zeus2x7/DL-Inverse-kinematics/blob/main/Images%20and%20Videos/images/webapp3.png" alt = "cover image">
<br>fig1 <i>cover image</i> <br></br>


## Abstract
<p align = "justify">The aim of this project is to predict the inverse kinematics of a two link simulator or in 
simpler words we have to predict the angles q1 and q2 which would get the desired end affector position given as input, of a robotic arm with 2 degree of freedom.  </p>

## Motivation
<p align = "justify">Deep Learning has been such a great tool in field of robotics. The ability to do define set of rules given a lot of input and output data, 
has made it a lot of use in research projects.
<br></br>
Our project inspires us to solve many real world problem like autonomous robotic arm with desired degree of freedoms.
</p>

<p align = "center">
<img src = "https://github.com/zeus2x7/DL-Inverse-kinematics/blob/main/Images%20and%20Videos/images/robotic%20arm.jpg" alt = "robotic arm">
<br>fig2 <i>robotic arm</i></p>

## Software Aspect of the Design
### Tech Stack
* <p align = "justify"><b>Python</b> - It is an <b>interpreted high-level object-oriented</b> programming language designed by <b>Guido van Rossum</b>. It emphasizes code readability with significant use of indentation. It has tons of third-party open-source libraries (which can be installed using its own package manager <b><i>pip</i></b>) to assist all types of programs.</p>
* <p align = "justify"><b>Jupyter Notebook</b> - It is a product developed under <b><i>Project Jupyter</i></b> (spun off from <b><i>IPython</i></b> in 2014 by <b>Fernando Perez</b>) and is used to create documents containing live code, equations, visualizations and narrative text. It is used in data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, etc.</p>
* <p align = "justify"><b>NumPy</b> - It is a Python library providing fundamental package for scientific computing. It is used for working with arrays in the domain of linear algebra, fourier transform, matrices, etc. Numpy arrays are 50x faster than Python lists.</p>
* <p align = "justify"><b>Tensorflow</b> - TensorFlow is an open-source library developed by Google primarily for deep learning applications. 
  
  ### Working
* #### Terminologies
  * <p align = "justify"><b>Data Creation</b> -The data(inputs) to be given to the neural network for its training is to be generated.</p>
  * <p align = "justify"><b>Epochs</b> - A complete pass through the whole training dataset while training is referred as a epoch, you can control that how much your model gets trained by controlling the number of epochs or complete passes.</p>
  * <p align = "justify"><b>Neural Network</b> - Artificial neural networks (ANNs) are comprised of a node layers, containing an input layer, one or more hidden layers, and an output layer. Each node, or artificial neuron, connects to another and has an associated weight and threshold.</p>
 <p align = "center">
  <img src = "https://github.com/zeus2x7/DL-Inverse-kinematics/blob/main/Images%20and%20Videos/images/neural%20network%20(1).png" alt = "Neural Network"><br>fig3 <i>Neural Network</i></p>

  * <p align = "justify"><b>Adam</b> - Adam means Adaptative Moment Estimation. It will be used as the optimizer in this project for neural network weights and biases updatation </p>
 <p align = "center">
  <img src = "https://github.com/zeus2x7/DL-Inverse-kinematics/blob/main/Images%20and%20Videos/images/adam%20optimizer%20(1).png" alt = "Adam optimizer"><br>fig4 <i>Adam optimizer</i></p>
  * <p align = "justify"><b>MAE</b> - MAE or Mean Absolute Error is the loss function to be used in this model</p>
  <p align = "center">
  <img src = "https://github.com/zeus2x7/DL-Inverse-kinematics/blob/main/Images%20and%20Videos/images/MAE%20loss%20function.png" alt = "Mean Absolute Error"><br>fig5 <i>Mean Absolute Error</i></p>


## Cost Structure
| Software (Components) | Cost |
|:---------------------:|:----:|
| Python | Open-Source/None |
| Jupyter Notebook | Open-Source/None |
| NumPy | Open-Source/None |
| Tensorflow | Open-Source/None |

## Applications
<p align = "justify">This project can be used to develop a robotic arm with 2 degree of freedom. </p>

## Limitations
At the current state, our project has a few limitations :
* <p align = "justify">At present the model is limited only for 2d.</p>


## Future Improvements
In future, we plan to :
* <p align = "justify">decrease losses further by taking the domains of the function to be mimicked by the neural network </p>
* <p align = "justify">implement <b>this Approach for 3 or even more DOF</b>



## Team Members
* [Aditya Raj](https://github.com/zeus2x7)
* [Rajib Das](https://github.com/dasrajib02)

## Mentors
* [Apurba Prasad Padhy](https://github.com/apurba-pp)
* [Tushar Sahu](https://github.com/tushdon2)

## References
* Python :
  * [Youtube/freeCodeCamp.org](https://www.youtube.com/watch?v=rfscVS0vtbw)
  * [Programiz](https://www.programiz.com/python-programming)
  * [W3Schools](https://www.w3schools.com/python/)
* Deep Neural Network :
  * [Youtube/3blue1brown](https://www.youtube.com/watch?v=aircAruvnKk)
  * [Youtube/Andrew Ng Deep Neural Network](https://www.youtube.com/watch?v=CS4cs9xVecg&list=PLpFsSf5Dm-pd5d3rjNtIXUHT-v7bdaEIe)
  * [Tutorials Point](https://www.tutorialspoint.com/python_deep_learning/python_deep_learning_deep_neural_networks.htm)
  * [Towards Data Science](https://towardsdatascience.com/code-a-deep-neural-network-a5fd26ec41c4)
* Tensorflow :
  * [Tensorflow docs](https://www.tensorflow.org/learn)
* Streamlit :
  * [Streamlit docs](https://docs.streamlit.io/)




