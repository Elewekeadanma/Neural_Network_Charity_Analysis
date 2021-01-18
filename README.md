# Neural_Network_Charity_Analysis
## Overview of the analysis
The purpose of this analysis is to analyze the impact of each donation to recipients of AlphabetSoup's funding. We want to predict which organizations are worth donating to and which organizations are high risk. A deep learning neural network wil be designed and trained to evaluate all types of input data and produce clear decision making results.
## Results
---
### Data Preprocessing
The is_successful variable was considered as a target for my model.
The variables considered as features were Status, Income amount,Special considerations and Ask amount.
The variables that should be removed from input data are Name and  Afflliation.
### Compiling, Training an Evaluating the Model
I started out with using 2 layers, increased to 3 layers and finally decided to stay with 2 layers because I was not getting a better accuracy with 3 layers.
The tanh function gave me very low accuaracies , Relu activation function gave a better model performance.
I used 100 epochs. I noticed that when I reduced the number of epochs the accuracy reduced drastically.
![Ist Optimization](https://github.com/Elewekeadanma/Neural_Network_Charity_Analysis/blob/main/images/optimization1.jpg)
![Results of the 1st Optimization](
---
![2nd OPtimization](https://github.com/Elewekeadanma/Neural_Network_Charity_Analysis/blob/main/images/optimization2.jpg)
