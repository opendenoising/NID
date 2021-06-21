# NID
Natural Interception Dataset

## Purpose 
This repository stores the natural interception dataset (NID). The system used to intercept the electro-magnetic leakage emitted by a screen is detailed in the ICASSP20 paper named *Electro-Magnetic Side-Channel Attack Through Learned Denoising and Classification*" --> [ArXiv](https://arxiv.org/pdf/1910.07201.pdf) or [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9053913) 

## Repository Content 
* data
    * train: 424 images based on BSD432 samples:	
    	* in: eavesdropped samples
    	* ref: reference grayscale samples
    * val: 68 BSD68 samples 
    	* in: eavesdropped samples
    	* ref: reference grayscale samples
    * missing: the 8 ref samples missing in the train dataset
    	* ref
