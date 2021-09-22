---
layout: post
title: AutoEncoders-Fraud Detection
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<a href='https://github.com/Sk7w4tch3r/universityProjects/blob/master/Seventh%20One/Neural%20Networks/Assignments/P3/P3.ipynb'>
<i class="fa fa-github" style="font-size:30px"></i>
</a><a href="https://github.com/Sk7w4tch3r/universityProjects/blob/master/Seventh%20One/Neural%20Networks/Assignments/P3/Report_p3.pdf">
<i class="fa fa-print" style="font-size:30px"></i>
</a>

Autoencoders are an unsupervised neural network architecture that is consisted of an encoder and a decoder. The encoder part converts input data to a space with much lower dimensions called latent space, and then the decoder part decodes samples from the latent space to a space with exact dimensions as the input to reconstruct a sample same as the input sample. By training an autoencoder to reconstruct samples like the input data (standard transactions) and measuring the MSE between the input data and the reconstructed samples, we can detect the fraud transaction from the normal ones based on this MSE error.

