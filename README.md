# DP_PATE_MNIST
Section Project for Udacity's Secure and Private AI Scholarship Challenge Nanodegree Program: a Differential Privacy model using the Private Aggregation of Teacher Ensembles method on the MNIST dataset

Secure and Private AI Scholarship Challenge Nanodegree Program

Lession 6: Differential Privacy

Section Project:

For the final project for this section, you're going to train a DP model using this PATE method on the MNIST dataset, provided below.


### Current state of this notebook:

I have something for all of the steps that I think need to be taken for the project, but I'm not sure if I'm doing it correctly, especially with respect to the added Laplacian noise and the PATE analysis.

The PATE analysis shows that for 10 teachers, even when there is high agreement, the Data Dependent Epsilon is very similar to the Data Independent Epsilon.

The student model trained on the 1000 queries from each teacher model reaches about 85% accuracy. This could be improved by using GANs, as in the paper "Semi-Supervised Knowledge Transfer for Deep Learning from Private Training Data"
