# cs532-assignment-8-solved
**TO GET THIS SOLUTION VISIT:** [CS532 Assignment 8 Solved](https://www.ankitcodinghub.com/product/cs532-cs-ece-me532-assignment-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121509&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS532  Assignment 8 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
1. Data Fitting vs. Sparsity Tradeoff. This assignment uses the dataset BreastCancer.mat to explore sparse regularization of a least squares problem. The journal article “A geneexpression signature as a predictor of survival in breast cancer” provides background on the role of genes in breast cancer.

The goal is to solve the Lasso problem

w∗ = arg min kAw

w∈Rn

Here w is the weight vector applied to the expression levels of 8141 genes and there are 295 patients (feature sets and labels). In this problem we will vary λ to explore the tradeoff between data-fitting and sparsity.

Scripts that implement iterative soft thresholding via proximal gradient descent to solve the LASSO problem are available. The scripts use a hot start procedure for finding the solution with different values for λ. The initial guess for the next value of λ is the converged solution for the preceding value. This accelerates convergence when subsequent values of λ lead to similar solutions.

b) Next use your solutions from part a) to plot the error rate on the vertical-axis versus the sparsity on the horizontal-axis as λ varies. Define the error rate as the number of incorrect predictions divided by the total number of predictions and the sparsity as the number of nonzero entries in w∗. For this purpose, we’ll say an entry wi is nonzero if |wi| &gt; 10−6. Calculate the error rate using the training data,

the data used to find the optimal weights. Explain the result.

c) Repeat parts a) and b) to display the residual and error rate, respectively using validation or test data, rows 101-295 of the data matrix, that is, the data not used to design the optimal classifier. Again, explain what you see in each plot.

2. Now compare the performance of the LASSO and ridge regression for the breast cancer dataset using the following steps:

• Randomly split the set of 295 patients into ten subsets of size 29-30.

1 of 2

• Use the data in eight of the subsets to find a solution to the Lasso optimization above and to the ridge regression problem

min kAw .

w

Repeat this for a range of λ values to obtain a set of solutions wλ.

• Compute the prediction error using each wλ on one of the remaining two of the ten subsets. Use the solution that has the smallest prediction error to find the best λ. Note that LASSO and ridge regression will produce different best values for λ.

• Compute the test error on the final subset of the data for the choice of λ that minimizes the prediction error. Compute both the squared error and the error rate.

Repeat this process for different subsets of eight training, one tuning (λ) and one testing subsets, and compute the average squared error and average number of misclassifications across all different subsets.

Note that you should use the identity derived in Problem 1 of the Activity 5.2 in order to speed the computation of ridge regression.

2 of 2
