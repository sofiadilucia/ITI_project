# Information Theory and Inference Project:
# Missing and spurious interactions and the reconstruction of complex networks

This repo contains our project for Information Theory and Inference course. Our aim is to analyze well-known complex networks and reconstruct their properties from noisy observations of the networks themselves. 

To do so, our first approach is to use MCMC methods. For missing/spurious links, we want to determine the reliability of those links, i.e., the prbability that the link truly exists given data. To do so, we implement Metropolis algorithm to sample relevant partitions for the network and then average over all the partition to obtain the reliability of the links.

The dataset we used are: Zachary karate club network dataset. 

