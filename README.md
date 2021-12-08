# Identifying Gene regulatory network using PCA-CMI and IC algorithms

We have implemented the PCA-CMI algorithm presented in the paper by Zhang et al. (https://academic.oup.com/bioinformatics/article/28/1/98/221936?login=true) and compared the causal graph obtained, with the gold standard network, as well as the network obtained by the out of the box IC algorithm.

The PC-CMI approach uses a conditional mutual information (CMI) measure to estimate the conditional independence between two variables, given a set of known variables. The PC algorithm starts with a complete graph, and uses a greedy approach to eliminate edges based on the conditional independence test.


Dataset: https://iastate.app.box.com/folder/151080162944
