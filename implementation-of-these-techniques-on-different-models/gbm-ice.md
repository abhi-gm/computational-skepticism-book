# GBM - ICE

[Code Implementation Here](https://colab.research.google.com/drive/1hIEPr60uUd0wZjjJcR4ZH5l5DZPmQ1T0?usp=sharing)

### What is GBM?

* Gradient Boosting Machine is a machine learning algorithm that forms an ensemble of weakly predicted decision trees
* It constructs a forward stage-wise additive model by implementing gradient descent in function space
* Also known as MART \(Multiple Additive Regression Trees\) and GBRT \(Gradient Boosted Regression Trees\)

### Making the Model

**Dataset:** Medical Cost Personal  ; **Target:** charges

The data is trained by calling the GradientBoostingClassifier function from Scikit learn Library

**Accuracy:** 

### **Implementation of Interpretability**

In this section we will interpret a GBM using ICE plots.

![](../.gitbook/assets/image%20%2872%29.png)



We use the Pycebox library and generate ICE plots for "Smoker" feature against out predicted output of "Charges"

### Visualizations

**ICE plot**

![](../.gitbook/assets/image%20%28125%29.png)

In the above plot, we see multiple lines plotted. Each line corresponds to a row in our data. We can see that for some individuals BMI does not affect the charges. But for a few of them, a high BMI seems to increase the charges. Such interpretation can be very useful in showing people the repercussions of having a high BMI.

**ICE plot with PDP line**

![](../.gitbook/assets/image%20%28127%29.png)

The above plot shows the ICE plot along with the aggregation line shown in black. The aggregation line is the same as the PDP line. The PDP line shows that the overall effect of the age is not much, though the charges increase a small bit after a certain age.  

**Centered ICE plot**

![](../.gitbook/assets/image%20%28124%29.png)

The Centered ICE plot is centering the curves at a certain point in the feature and displaying only the differences in prediction so that it is easy to interpret.

