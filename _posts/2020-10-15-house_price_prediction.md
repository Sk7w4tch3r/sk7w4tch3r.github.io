---
layout: post
title: Predicting House Prices with basic Informtion and Images of the House
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<a href='https://github.com/Sk7w4tch3r/universityProjects/blob/master/Seventh%20One/Neural%20Networks/Assignments/P2/pricePrediction.ipynb'>
<i class="fa fa-github" style="font-size:30px"></i>
</a><a href="https://github.com/Sk7w4tch3r/universityProjects/blob/master/Seventh%20One/Neural%20Networks/Assignments/P2/Report_p2.pdf">
<i class="fa fa-print" style="font-size:30px"></i>
</a>

One way to implement regression in neural networks is to use only one neuron in the last layer so that the output of that neuron gets closer to the target value in each iteration. With this given dataset, a simple way to predict house prices is only based on the structured data, which is relatively straightforward. Another way to do so is to create a ConvNet model with mentioned MLP and concatenating output of these two layers. As conducted experiments suggest, the simple mlp regression model performs better than the combined model.
