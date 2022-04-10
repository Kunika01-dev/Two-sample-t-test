<h2>Problem Statement- To check whether the average experience of white people is equal to average experience of black people</h2>
<br>
<h3>✔️Import the necessary libraries</h3>
  ▶️<i>import numpy as np</i>
  <br>
  ▶️<i>import pandas as pd</i>
  <br>
  ▶️<i>from scipy import stats</i>
<br>
<h3>✔️Create a DataFrame df containing years of experience of different races - 'white' (w) and 'black'(b) </h3>
<h3>✔️Create 2 dataset sample from DataFrame df - 'white' and 'black' </h3>
<h3>✔️Let's assume </h3>
  
   <i>▶️H0 (NULL Hypothesis):  Avg exp. of both the groups is equal </i>
  <br>
   <i>▶️H1 (ALTERNATE Hypothesis):  Avg exp. of both the groups is not equal </i>
  <br>
  <i> ▶️Consider significance level (alpha) = 0.05 </i>
 
<h3>✔️Use stats.ttest_ind() and pass the 2 samples created above (white, black).</h3>
    
   <i> ▶️Stats.ttest_ind():
       It is used to calculate the T test for 2 independent samples. This is a 2 sided test for the null hypothesis that 2 independent samples have identical
   average values.</i>
   <br>
  
  ✔️ <i>On executing the above expression, P value is generated.</i>
  <br>
  ✔️ <i> P value is observed greater than the significance value (alpha) </i><br>
  <i>   Hence, we can consider H0 (NULL Hypothesis) true </i>
  
    
