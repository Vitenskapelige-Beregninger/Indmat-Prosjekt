# Project in TMA4320: Introduction to Scientific Computation.
## Project 3: Industrial Mathematics

Introduction:
In this project we are using non-negative matrix factorization (NMF) to compress the data needed to store several low-resolution images called non-fungible tokens (NFTs) that lend themselves to this purpose by having several common features.
We first implement an NMF algorithm and test it on a set of simple matrices. Then we will apply our algorithm to a set of 500 NFTs, where we will be plotting 64 of them.
Then, we demonstrate how the NMF extracts common features and how accurate the reconstruction is, visually and by computing the Frobenius norm.

In the last part of this project we add random noise to the NFTs and then apply the NMF to se how effectively it can denoise the images. We will then again provide a plot of the Frobenius norm of the difference between the original images and the reconstructions for several dimensions of the NMF.
