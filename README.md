# comp0078-coursework-1-solved
**TO GET THIS SOLUTION VISIT:** [COMP0078 Coursework 1 Solved](https://www.ankitcodinghub.com/product/comp0078-coursework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101293&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP0078 Coursework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 PART I

1.1 Linear Regression

“Pluralitas non est ponenda sine neccesitate” – William of Ockham (ca. 1285-1349) Linear regression overview: Given a set of data:

{(x1, y1), (x2, y2), . . . , (xm, ym)} (1) where x = (x1,…,xn) is a vector in Rn and y is a real number. Linear regression finds a vector w ∈ Rn

such that the sum of squared errors

m

SSE=􏰊(yt −w·xt)2 (2)

t=1

is minimized. This is expressible in matrix form by defining X to be the m × n matrix

x1,1 x1,2 …x1,n

x2,1 x2,2 …x2,n

X =  . . . . .  , (3)

…. xm,1 xm,2 . . . xm,n

and defining y to be the column vector y = (y1, . . . , ym). The vector w then minimizes (Xw − y)􏰓(Xw − y).

In linear regression with basis functions we fit the data sequence with a linear combination of basis functions (φ1,φ2,…, φk) where φi : Rn → R which defines a feature map from φ : Rn → Rk

φ(x) = (φ1(x),…,φk(x)), x ∈ Rn . We use the basis functions to transform the data as follows

{((φ1(x1), . . . , φk(x1)), y1), . . . , ((φ1(xm), . . . , φk(xm)), ym)}, (4) 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
and then applying linear regression above to this transformed dataset. In matrix notation we may denote this transformed dataset as

</div>
</div>
<div class="layoutArea">
<div class="column">
 φ(x1)   φ1(x1) … φk(x1)  .…

</div>
</div>
<div class="layoutArea">
<div class="column">
Φ :=  .  =  . . . .  , (m × k) (5) φ(xm) φ1(xm) . . . φk(xm)

</div>
</div>
<div class="layoutArea">
<div class="column">
Linear regression on the transformed dataset thus finds a k-dimensional vector w = (w1, . . . , wk) such that

mk

(Φw − y)T (Φw − y) = 􏰊(yt − 􏰊wiφi(xt))2 (6)

t=1 i=1

is minimized.

A common basis (n = 1) used is the polynomial basis {φ1(x) = 1,φ2(x) = x,φ3(x) = x2,φ4(x) =

x3, . . . , φk(x) = xk−1} of dimension k (order k − 1) in the figure below we give a simple fit of four points produced by a linear (k = 2) and cubic (k = 4) polynomial.

</div>
</div>
<div class="layoutArea">
<div class="column">
8 6 4 2

-2 -4

</div>
<div class="column">
12345

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Data set {(1,3),(2,2),(3,0),(4,5)} fitted with basis {1,x} and basis {1,x,x2,x3}

1. [5 pts]: For each of the polynomial bases of dimension k = 1,2,3,4 fit the data set of Figure 1

{(1, 3), (2, 2), (3, 0), (4, 5)}.

<ol>
<li>(a) &nbsp;Produce a plot similar to Figure 1, superimposing the four different curves corresponding to eachfit over the four data points.</li>
<li>(b) &nbsp;Give the equations corresponding to the curves fitted for k = 1, 2, 3. The equation corresponding</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
to k = 4 is −5 + 15.17x − 8.5×2 + 1.33×3.

(c) For each fitted curve k = 1, 2, 3, 4 give the mean square error where MSE = SSE .

</div>
</div>
<div class="layoutArea">
<div class="column">
2. [10 pts]: In this part we will illustrate the phenomena of overfitting. (a) Define

gσ(x) := sin2(2πx) + ε.

</div>
<div class="column">
(7)

</div>
</div>
<div class="layoutArea">
<div class="column">
where ε is a random variable distributed normally with mean 0 and variance σ2 thus gσ(x) is a random function such that sin2(2πx) is computed and then the normal noise is added on each “call” of the function. We then sample “xi ” uniformly at random from the interval [0, 1] 30 times creating (x1 , . . . , x30 ) and apply g0.07 to each x creating the data set

S0.07,30 = {(x1, g0.07(x1)), . . . , (x30, g0.07(x30)}. (8) i. Plot the function sin2(2πx) in the range 0 ≤ x ≤ 1 with the points of the above data set

superimposed. The plot should resemble

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
m

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
0.8

0.6

0.4

0.2

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
0.2 0.4 0.6 0.8 1

</div>
</div>
<div class="layoutArea">
<div class="column">
ii. Fit the data set with a polynomial bases of dimension k = 2, 5, 10, 14, 18 plot each of these 5 curves superimposed over a plot of data points.1

<ol start="2">
<li>(b) &nbsp;Let the training error tek(S) denote the MSE of the fitting of the data set S with polynomial basis of dimension k. Plot the natural log (ln) of the training error versus the polynomial dimension k = 1, . . . , 18 (this should be a decreasing function).</li>
<li>(c) &nbsp;Generate a test set T of a thousand points,

T0.07,1000 = {(x1, g0.07(x1)), . . . , (x1000, g0.07(x1000)}. (9)Define the test error tsek(S,T) to be the MSE of the test set T on the polynomial of dimension k fitted from training set S. Plot the ln of the test error versus the polynomial dimension k = 1, . . . , 18. Unlike the training error this is not a decreasing function. This is the phenomena of overfitting. Although the training error decreases with growing k the test error eventually increases since rather than fitting the function, in a loose sense, we begin to fit to the noise.</li>
<li>(d) &nbsp;For any given set of random numbers we will get slightly different training curves and test curves. It is instructive to see these curves smoothed out. For this part repeat items (b) and (c) but instead of plotting the results of a single “run” plot the average results of a 100 runs (note: plot the ln(avg) rather than the avg(ln)).</li>
</ol>
3. [5 pts]: Now use basis (for k = 1,…,18)

{sin(1πx), sin(2πx), sin(3πx), . . . , sin(kπx)}.

Repeat the experiments in 2 (b-d) with the above basis.

1.2 Filtered Boston housing and kernels

In this section we will use kernel methods to extend linear regression. Boston housing is a classic dataset where you are given 13 values and a goal is to predict the 14th which is the median house price. Instead of the original dataset we will instead use a modified dataset removing the ethically-suspect “column B.” Thus we will use 12 attributes to predict the 13th. The unmodified dataset is described in more detail at http://www.cs.toronto.edu/~delve/data/boston/bostonDetail. html. There are 506 entries which we will split into train and test.

The filtered boston housing data set as a “.csv’ file is located at http://www.cs.ucl.ac.uk/staff/M.Herbster/boston-filter

4. [10 pts]: “Baseline versus full linear regression.”

Rather than use all of our attributes for prediction it is often useful to see how well a baseline method works for a problem. In this exercise, we will compare the following:

1Depending on you implementation you may have numerical errors for large values of k this is ‘ok’ for the purposes of this exercise.

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
(a) Predicting with the mean y-value on the training set. (b) Predicting with a single attribute and a bias term.

(c) Predicting with all the attributes

The training set should be 2/3, and the test set should be 1/3, of your data in (a)-(c). In the following average your results over 20 runs (each run based on a different (2/3,1/3) random split).

<ol>
<li>Naive Regression. Create a vector of ones that is the same length as the training set using the function ones. Do the same for the test set. By using these vectors we will be fitting the data with a constant function. Perform linear regression on the training set. Calculate the MSE on the training and test sets and note down the results.</li>
<li>Give a simple interpretation of the constant function in ‘a.’ above.</li>
<li>Linear Regression with single attributes. For each of the twelve attributes, perform a linear regression using only the single attribute but incorporating a bias term so that the inputs are augmented with an additional 1 entry, (xi , 1), so that we learn a weight vector w ∈ R2 .</li>
<li>Linear Regression using all attributes. Now we would like to perform linear regression using all of the data attributes at once.

Perform linear regression on the training set using this regressor, and incorporate a bias term as above. Calculate the MSE on the training and test sets and note down the results. You should find that this method outperforms any of the individual regressors.</li>
</ol>
1.3 Kernelised ridge regression

For nonlinear regression, the dual version will prove important. Obviously, linear regression is not capable of achieving a good predictive performance on a nonlinear data set. Here, the dual formulation will prove extremely useful, in combination with the kernel trick.

For our exercises we will use a slight variation on the optimisation (as compared to the notes) that defines ridge regression for a training set with l examples,

1 􏰊l

</div>
</div>
<div class="layoutArea">
<div class="column">
(x􏰓i w − yi)2 + γw􏰓w. (10) i.e, we have replace the sum of the square errors with the mean square error (MSE).2 For a given

</div>
</div>
<div class="layoutArea">
<div class="column">
w∗ = argminw∈Rn l

kernel function K define the kernel matrix K for a training set of size l elementwise via

</div>
</div>
<div class="layoutArea">
<div class="column">
Ki,j :=K(xi,xj) The dual optimisation formulation after kernelization is

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
1ll ∗􏰊􏰊2􏰓

</div>
</div>
<div class="layoutArea">
<div class="column">
α =argminα∈Rl l ( αjKi,j −yi) +γα Kα. (11) i=1 j=1

</div>
</div>
<div class="layoutArea">
<div class="column">
Now if we use y := (y1, . . . , yl)􏰓 to denote a vector that contain the y-values of training set we may solve in the dual as follows

α∗ = (K + γlIl)−1y (12) where Il denotes the l × l identity matrix. The evaluation of the regression function on a test point

can be reformulated as:

l

ytest =􏰊αi∗K(xi,xtest) (13)

i=1

2The motivation is that we wish the regularisation parameter γ to ‘scale’ somewhat independently of training set size.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
where the K is the kernel function.

</div>
</div>
<div class="layoutArea">
<div class="column">
5. [20 pts] “Kernel Ridge Regression”

In this exercise we will perform kernel ridge regression (KRR) on the data set using the Gaussian kernel,

􏰑 ∥xi−xj∥2􏰒

K(xi,xj) = exp − 2σ2 . (14)

For this question, you will hold out 2/3 of data for training and report the test results on the remaining 1/3.

</div>
</div>
<div class="layoutArea">
<div class="column">
a.

b. c. d.

</div>
<div class="column">
Create a vector of γ values [2−40, 2−39, . . . , 2−26] and a vector of σ values [27, 27.5, . . . , 212.5, 213] (recall that σ is a parameter of the Gaussian kernel see equation (14)). Perform kernel ridge regression on the training set using five-fold cross-validation to choose among all pairing of the values of γ and σ. Choose the γ and σ values that perform the best to compute the predictor (by then retraining with those parameters on the training set) that you will use to report the test and training error.

Plot the “cross-validation error” (mean over folds of validation error) as a function of γ and σ.

Calculate the MSE on the training and test sets for the best γ and σ.

Repeat “exercise 4a,c,d” and “exercise 5a,c” over 20 random (2/3, 1/3) splits of your data. Record the train/test error and the standard deviations (σ′) of the train/test errors and summarise these

</div>
</div>
<div class="layoutArea">
<div class="column">
results in the following type of table. Additional clarification: thus be generating 20 best (γ,σ) pairs.

</div>
<div class="column">
when repeating 5a,c: you will

MSE test

??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′?

</div>
</div>
<div class="layoutArea">
<div class="column">
2 2.1

</div>
</div>
<div class="layoutArea">
<div class="column">
Method

Naive Regression

Linear Regression (attribute 1) Linear Regression (attribute 2) Linear Regression (attribute 3) Linear Regression (attribute 4) Linear Regression (attribute 5) Linear Regression (attribute 6) Linear Regression (attribute 7) Linear Regression (attribute 8) Linear Regression (attribute 9) Linear Regression (attribute 10) Linear Regression (attribute 11) Linear Regression (attribute 12) Linear Regression (all attributes) Kernel Ridge Regression

PART II [20%] k-Nearest Neighbors

</div>
<div class="column">
MSE train

??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′? ??.?? ± σ′?

</div>
</div>
<div class="layoutArea">
<div class="column">
In this section you will implement the k-NN algorithm and explore its performance as a function of k. 2.1.1 Generating the data

A voted-center hypothesis is a function hS,v : [0, 1]2 → {0, 1, 􏰔} where S = {(x1, y1), (x2, y2), . . . , (x|S|, y|S|)} is a set of labeled centers with each xi ∈ [0,1]2 and yi ∈ {0,1} and v is a positive integer. In this coursework we will always set v := 3 for all of of the exercises in this subsection. Where hS,v(x) = 0

if the majority of the v nearest xi’s to x in S are ‘0’, similarly for hS,v(x) = 1 and finally in certain

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Figure 1: A hypothesis hS,v visualized with |S| = 100 and v = 3.

For each k∈{1,…,49} Do 100 runs …

Sample a h from pH

Build a k-NN model with 4000 training points sampled from ph(x,y). Run k-NN estimate generalisation error (for this run)

using 1000 test points sampled from ph(x,y)

The estimated generalization error (y-axis) is then the mean

of these 100 ‘‘run’’ generalisation errors.

Figure 2: Experimental Protocol A: k-NN

“corner” cases the “the majority of v …” will not be well-defined and in that case hS,v(x) = 􏰔. See

Section 2.1.4 for addressing those corner cases.

In Figure 1 one such hypothesis is visualised with |S| = 100 and v = 3. The white area is the mapping to 0 and the turquoise is the mapping to 1, the corresponding centers are green and blue.

6. [5 pts] Produce a visualisation of an hS,v similar to the figure.

First we will need to generate a random h. Do this by sampling 100 centers uniformly at random from [0, 1]2 with 100 corresponding labels sampled uniformly at random from {0, 1}. Later we will need to generate more random hypotheses. Call this distribution over hypotheses generated by this random process pH.

2.1.2 Estimated generalization error of k-NN as a function of k

In this section we visualise the performance as a function of k. You will produce a figure where the

vertical axis is the estimated generalisation error and the horizontal axis is k = 1, . . . , 49.

Generating our noisy data. Given an hS,v the underlying probability distribution ph(x,y) is deter- mined by sampling an x uniformly at random from [0, 1]2 and then its corresponding y value is then generated by flipping biased coin P(heads) = 0.8/P(tails) = 0.2 if heads comes up then y = hS,3(x) otherwise y is sampled uniformly at random from {0, 1}. When you generate training and test sets they will both come from this distribution.

7. [7 pts] a) Produce a visualisation using Protocol A (see Figure 2). b) Using roughly 5 sentences explain why the figure is the approximate shape that it is and comment on any interesting features of the figure.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
For

</div>
<div class="column">
each m ∈ {100, 500, 1000, 1500, . . . , 4000} Do 100 runs …

For each k∈{1,…,49} Sample a h from pH

Build a k-NN model with m training points sampled from ph(x,y). Run k-NN estimate generalisation error (for this run)

using 1000 test points sampled from ph(x,y)

The estimated optimal k (for this run) is then the k

with minimal estimated generalisation error. The estimated optimal k (y-axis) is then the mean

of these 100 ‘‘run ’’ optimal ‘k’s.

Figure 3: Experimental Protocol B: k-NN

2.1.3 Determine the optimal k as a function of the number of training points (m)

In this section you will estimate the optimal k as a function of the number of training points. Perform

the following experimental protocol.

</div>
</div>
<div class="layoutArea">
<div class="column">
8. [8 pts] a) Produce a visualisation using Protocol B (see Figure 3). I.e, plotting m versus optimal k b) Using roughly 4 sentences explain why the figure is the approximate shape that it is.

2.1.4 Additional Clarifications

Note both the k-NN algorithm and the hypothesis h can produced “undefined” results in certain corner cases for individual x’s. Resolve these case by generating either the label or prediction uniformly at random.

3 PART III [30%] 3.1 Questions

Notation: We overload [·] as follows [n] := {1, 2, . . . , n} if n is a positive integer and [pred] = 1 if pred is a logical predicate which is true and [pred] = 0 otherwise.

<ol start="9">
<li>[10 pts] Kernel modification Consider the function Kc (x, z) := c + 􏰈ni=1 xi zi where x, z ∈ Rn .

(a) For what values of c ∈ R is Kc a positive semidefinite kernel? Give an argument supporting yourclaim. (“The closer your argument is to a proof the more likely it is to receive full credit.”)

(b) Suppose we use Kc as a kernel function with linear regression (least squares). Explain how c influences the solution.
</li>
<li>[15 pts] Suppose we perform linear regression with a Gaussian kernel Kβ(x,t) = exp(−β∥x − t∥2) to train a classifier on a dataset (x1, y1), . . . , (xm, ym) ∈ Rn × {−1, 1}. Thus obtaining a function f : Rn → R which is of the form f(t) = 􏰈mi=1 αiKβ(xi,t). The corresponding classifier is then sign(f(t)). This classifier depends on the parameter β selected for the kernel. In what scenario will chosen β enable the trained linear classifier to simulate a 1-Nearest Neighbor classifier trained on the same dataset?Note β ∈ R is a fixed scalar which may be selected as a function of x1,…,xm and the test point t, i.e., we may use a function so that β = βˆ(x1, . . . , xm, t) an exact function βˆ(·) need not be given just an argument that one exists.
Give an argument supporting your reasoning. (“The closer your argument is to a proof the more likely it is to receive full credit.”)
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
11. [5pts]: Hint: “Think about vector spaces ‘broadly’”.

We consider the problem of generalized Whack-A-Mole! We’ll play this game on a board with n × n holes, from which individual moles pop-up. Using a mallet you can then whack a mole and make it go hide underground. As you might know, however, whacking a mole will often have the effect of making other moles rise and come out from the ground. In this version of the game, every time you hit a hole with the mallet you’ll cause the hole and the immediate four adjacent holes to change: any moles currently there will hide, while new moles pop-up from previously empty holes. Imagine, for example, that you find yourself in the following game configuration, and you prepare yourself to hit the hole at position 10 with the mallet.

You will cause the moles in positons 9, 10, 11, and 14 to hide, but you’ll also make a mole appear at position 6. Thus ending up in the next configuration.

If you then hit the hole at position 2, then all of the moles at positions 1, 2, and 6 will hide; but a new one in position 3 will appear.

Example: Consider the 4 × 4 board with moles at positions 1,2,4,8,9,10,11, and 14. This is the same configuration of moles as given in the initial illustration above. After hitting holes at positions 10 then 2, you’ll end up in the following configuration.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
At this point, a single hit to position 4 will clear the board. Thus the hitting sequence (10, 2, 4) is a solution.

Task: Design an algorithm for an n × n board which, given an initial board configuration, finds a sequence of holes that you can hit in order to empty the board if such a sequence exists. The algorithm must be polynomial in n and you must provide an argument that it is correct. No credit will be given for algorithms that are not polynomial in n. There is no need to implement your algorithm.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
