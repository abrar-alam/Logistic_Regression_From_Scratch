# Objective
The purpose of this project is to build and train a logistic regression classifier that predicts the probabilty of a person having Coronary Heart Disease (CHD) given other features. Learning rate (alpha) can be adjusted. Two
different modes of gradient descent can be used: Batch and Mini-batch. The effects of learning rate and the two modes of gradient descent algorithm will be visualized with log loss vs. number of epochs plots. Finally, the
model coefficents will be compared with the coefficeints calculated by SciKit learn library to check for correctness.

# Dataset
Heart-disease data from Western Cape, South Africa (taken from a larger sample as described in Rousseauw et al,1983, South African Medical Journal) with the following 9 features and 1 target:<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**sbp**: systolic blood pressure<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**tobacco**: cumulative tobacco usage(kg)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**ldl**: low density lipo-protein cholesterol<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**adiposity**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**famhist**: family history of heart disease <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**typea**: Type-A personality trait <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**obesity**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**alcohol**: Alcohol consumption (current)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**age**: current age at the onset of heart-disease<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**chd**: coronary heart disease(label/target)
