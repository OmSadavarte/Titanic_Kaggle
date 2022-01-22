<h1> Titanic Prediction </h1> 
<div align="center">
   
  <img alt="" src="assets/Titantic.jpeg" height="250 x    "  />
</div>

# About Project
 the Titanic: Machine Learning from Disaster, Kaggle Competition.
In this competition, the goal is to perform a 2-label classification problem: predict which passengers survived the tragedy.
Kaggle offers two datasets. One training (the labels are known) and one testing (the labels are unknown) for which we can submit a file with our predicted labels.
We have access to a bunch of 9 features (numerical, text, categorical). The big challenge with this competition is the size of the data we have. 
The training set is composed of only 891 samples. The testing set is composed of 418 samples.
Therefore, the main issue is to design an algorithm which generalize enough in order to avoid over-fitting. To do so, a bunch of generalized enough features is generated. 
Then, an ensemble modeling method with voting is used in order to get the most generalized model.

# Notes
- pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

- age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

- sibsp: The dataset defines family relations in this way...
- Sibling = brother, sister, stepbrother, stepsister
- Spouse = husband, wife (mistresses and fiancés were ignored)

- parch: The dataset defines family relations in this way...
- Parent = mother, father
- Child = daughter, son, stepdaughter, stepson
- Some children travelled only with a nanny, therefore parch=0 for them.
