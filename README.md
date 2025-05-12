# machinelearning-assignment-2--classification-using-logistic-regression-and-decision-trees-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Assignment 2 -Classification using Logistic Regression and Decision Trees Solved](https://www.ankitcodinghub.com/product/machinelearning-assignment-2-classification-using-logistic-regression-and-decision-trees-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90963&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Assignment 2 -Classification using Logistic Regression and Decision Trees Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

In this assignment, you are asked to implement Logistic Regression Classifier and Decision Tree classifier. You also need to use scikit-learn to test out these classifiers.

Task 1: Dataset Generation

Download the ​winequality-red.csv from this ​link​. It contains various chemical properties of red wine samples, along with the quality of wine. We want to train classifiers to predict the quality. We shall create two modified datasets from this data.

<ol>
<li>Convertallthevaluesinqualityattributeto0(bad)ifthevalueislessthanorequalto‘6’ and to 1 (good) otherwise. Normalize all the other attributes between 0 and 1 by min-max scaling​. ​Use this dataset (dataset A) for Logistic Regression​.</li>
<li>Convert all the values in quality attribute to 0 (bad) if the value is less than ‘5’, to 1 (good) if the value is ‘5’ or ‘6’ and to 2 (great) otherwise. Normalize all the other attributes by ​Z-score normalization​, and segregate them into 4 equal spaced bins each giving the values between [0 to 3], and replace the values for that attribute with the number corresponding to the interval they belong.For example, suppose after normalization an attribute has values between [-0.5,1.5], i.e., minimum value of the attribute is -0.5 and maximum value is 1.5, then form 4 bins:

bin 0: [-0.5,0.0],

bin 1: [0.0,0.5],bin 2: [0.5,1.0],

bin 3: [1.0,1.5].

Now, if a data instance has a value of 0.73 for that attribute, replace 0.73 with 2. Use this dataset (dataset B) for Decision Tree​.</li>
</ol>
Task 2: Logistic Regression

Use ​dataset A ​for this part.

1. Implement a standard Logistic Regression Classifier as discussed in class. Do NOT use

scikit-learn for this part.

2. Test out the implementation of Logistic Regression from scikit-learn package, using

saga solver​ and using no regularization penalty.

3. Cross validate both the classifiers with 3-folds and print the mean accuracy, precision

and recall for the class 1 (good) for both the classifiers. You may or may not use the scikit-learn implementations for computing these metrics and cross validation.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Task 3: Decision Tree

Use ​dataset B​ for this part.

1. Implement the standard ID3 Decision tree algorithm as discussed in class, using

information gain to choose which attribute to split at each point. Stop splitting a node if it

has less than 10 data points. Do NOT use scikit-learn for this part.

<ol start="2">
<li>Test out the implementation of Decision Tree Classifier from scikit-learn package, usinginformation gain. Here also stop splitting a node if it has less than 10 data points.</li>
<li>Cross validate the classifiers with 3-folds and print the mean macro accuracy, macro precision and macro recall for both the classifiers. You may or may not use thescikit-learn implementations for computing these metrics and cross validation.</li>
</ol>
&nbsp;

</div>
</div>
</div>
</div>
