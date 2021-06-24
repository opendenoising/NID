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

## Licensing

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

The dataset is free to use until you propagate the licence and you cite our paper using the following format:

@article{lemarchand2019electro,
  title={Electro-Magnetic Side-Channel Attack Through Learned Denoising and Classification},
  author={Lemarchand, Florian and Marlin, Cyril and Montreuil, Florent and Nogues, Erwan and Pelcat, Maxime},
  journal={arXiv preprint arXiv:1910.07201},
  year={2019}
}

## Contact
Florian Lemarchand : A@B.fr, A=florian.lemarchand and B = insa-rennes
