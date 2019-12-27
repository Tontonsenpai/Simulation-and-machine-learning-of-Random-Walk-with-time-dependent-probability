# Simulation and machine learning of Random Walk with time dependent probability
The goal of this project is to generate two types of random walk: the standard case or regular and the special case(which is an alternating time step). We want to be able to see if the machine is able to recognize and distinguish the two apart. The methods we will be using from machine learning is supervised learning with log regression since this is the beginning stage of the project and these methods were the easiest ones to do.
 # Table of contents
 - [What is a random walk and the special case?]
    + [Sub-sub-heading]
# What is a random walk and the special case?
Random walk model  is  the behavior of something moving over a certain time and a common example people use would be the drunkward's walk model. The model is an ideal case where the man has a fair probability ½ of moving either 1 step to the left or the right. The one that is presented here is the two step time dependent case where we used a bias proability with an alternating time step. To generate this special case, we do a two step process: the first step is probability p going to the right and 1-p for probability of going to the left. The second step is probability of going to the left is p and 1-p for going to the right. These steps alternate giving an average of ½ going to the left and ½ going to the right. We repeat this process many times to generate a time dependent random walk.
# Packages Required:
Sci-kit learn, pandas most of the packages are provided in Juypter Notebook and anaconda, both are used for generating a confusion matrix and classifying both RWs with supervised learning.
# 
