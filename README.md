# Prediciting-Quality-of-Exercise
With wearable tech such as Fitbits and Apple Watches, people can quantify how much of a particular activity they do, but they rarely quantify how well they do it. This project builds a classification algorithm to predict how well six subjects perform a weight lifting exercise. It is undertaken as the final project for Coursera's Practical Machine Learning course.

## Data 
Human Activity Recognition [data](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har) (accelerometer and gyroscope readings) obtained from six participants performing "one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions: exactly according to the specification (Class A), throwing the elbows to the front (Class B), lifting the dumbbell only halfway (Class C), lowering the dumbbell only halfway (Class D) and throwing the hips to the front (Class E)." <a href="#Reference1">[1]</a>.
  
## Method 
- Split training data into train and validation sets
- Build decision tree and random forest models
- Judge model accuracy on validation set
- Apply most accurate model to test data.

## Deliverables: 
<ul >
  <li><code><b>final_proj.Rmd </b> </code>: an R Mardown file that contains the classification algorithm </li>
  <li><code><b>final_proj.html</b></code>: a compiled HTML version of the same.</li>
</ul>

## Operating Environment 
RStudio
Version 1.2.5042 

<br>
<br>
<br>

<p id=Reference 1>[1] Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013. </p>


