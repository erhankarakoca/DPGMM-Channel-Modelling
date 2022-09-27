# Dirichlet Process Gamma Mixture Model For Channel Modelling
This is a DPGMM python code related to the following article: \
Erhan Karakoca, Güneş Karabulut Kurt, Ali Görçin, ***"Hierarchical Dirichlet Process Based Gamma Mixture Modelling for Terahertz Band Wireless Communication Channels"***. \
arXiv : https://arxiv.org/abs/2205.03812 \
IEEE Explore : https://ieeexplore.ieee.org/document/9852427
## Abstract

Due to the unique channel characteristics of Terahertz (THz), comprehensive propagation channel modeling is essential to understand the spectrum and to develop reliable communication systems in these bands. Ray tracing and traditional statistical modeling are insufficient to construct a suitable channel model due to the wide bandwidth and rapid changes in the characteristics of THz channels. In this work, we propose the utilization of hierarchical Dirichlet Process Gamma Mixture Model (DPGMM) to characterize THz channels statistically in the absence of any prior knowledge. DPGMM provides mixture component parameters and the required number of components. A revised expectation-maximization (EM) algorithm is also proposed as a pre-step for DPGMM. Kullback-Leibler Divergence (KL-divergence) is utilized as an error metric to examine the amount of inaccuracy of the EM algorithm and DPGMM when modeling the experimental probability density functions (PDFs). DPGMM and EM algorithm are implemented over the measurements taken at frequencies between 240 GHz and 300 GHz. By comparing the results of the DPGMM and EM algorithms for the measurement datasets, we demonstrate how well the DPGMM fits the target distribution. It is shown that the proposed DPGMM can accurately describe the various THz channels as good as the EM algorithm, and its flexibility allows it to represent more complex distributions better than the EM algorithm. We also demonstrated that DPGMM can be used to model any wireless channel due to its versatility. 

## Dataset 
Dataset used in this study can be found in : \
 http://ieee-dataport.org/open-access/thz-wireless-channel-measurements-between-240ghz-and-300ghz
 
 If you find our study and code helpful for your work you can cite as :

@article{karakoca2022hierarchical, \
  title={Hierarchical Dirichlet Process Based Gamma Mixture Modelling for Terahertz Band Wireless Communication Channels}, \
  author={Karakoca, Erhan and Kurt, G{\"u}ne{\c{s}} Karabulut and G{\"o}r{\c{c}}in, Ali}, \
  journal={arXiv preprint arXiv:2205.03812}, \
  year={2022} \
}
