# Seminar Stochastic Computational Deep Belief Network
## Chair of Hardware Oriented Computer Science, University of Stuttgart

### Author: Mohammed Muddasser

## Abstract
Deep belief network (DBN) is a type of deep neural network (DNN). The seminar topic discusses the hardware realisation of a re-configurable DBN capable of online learning. It summarises the implementations and outlines the results of the technical paper referred. First phase of DBN training employs a fast-greedy algorithm which learns in an unsupervised way. It is then fine-tuned using adaptive moment estimation (ADAM), an supervised learning technique for faster convergence in the second phase. These algorithms are implemented in re-configurable structures using stochastic computation (SC) circuits. SC circuits have simple hardware realisations for many arithmetic operations. The various activation functions applied at each of the DBN layers are implemented using an approximate SC activation unit (A-SCAU). The A-SCAU implementation is designed invariant to SC correlations in the signals allowing for one circuit to be shared among all neurons. The model is evaluated on MNIST dataset for handwritten digit classification. It achieves similar and improved accuracy when compared to most other DNNs, while having a reduced chip area and significantly low power consumption.

## Contents
The repository contains final analysis report and presentation slides of the Seminar.
