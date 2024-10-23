# Dirichlet Process Gamma Mixture Model for Channel Modelling

This repository contains the **DPGMM Python code** related to the following research article:

**Erhan Karakoca, Güneş Karabulut Kurt, Ali Görçin.**  
*"Hierarchical Dirichlet Process Based Gamma Mixture Modelling for Terahertz Band Wireless Communication Channels."*  
- [arXiv:2205.03812](https://arxiv.org/abs/2205.03812)  
- [IEEE Xplore](https://ieeexplore.ieee.org/document/9852427)  

---

## Abstract

Terahertz (THz) communication channels exhibit unique characteristics that demand thorough modeling to support reliable systems at these frequencies. Traditional statistical models and ray-tracing methods are often insufficient due to the wide bandwidth and dynamic channel behaviors at THz frequencies.

In this study, we introduce a **Hierarchical Dirichlet Process Gamma Mixture Model (DPGMM)** to statistically characterize THz channels without relying on prior knowledge. DPGMM automatically identifies the required number of components and estimates the parameters for each mixture. We propose an enhanced **Expectation-Maximization (EM) algorithm** as a preparatory step for DPGMM.

The **Kullback-Leibler Divergence (KL-Divergence)** metric is used to measure the accuracy of both the EM algorithm and DPGMM in modeling experimental probability density functions (PDFs). We apply these methods to datasets collected from measurements in the **240 GHz to 300 GHz** range. Our results demonstrate that DPGMM not only performs comparably to the EM algorithm but also offers greater flexibility to represent complex distributions, making it a versatile tool for various wireless channels.

---

## Dataset

The dataset used in this research is available at:  
[IEEE DataPort - THz Wireless Channel Measurements (240-300 GHz)](http://ieee-dataport.org/open-access/thz-wireless-channel-measurements-between-240ghz-and-300ghz)

---

## Citation

If you find this code or research helpful, please cite our work as follows:

```bibtex
@ARTICLE{9852427,
  author={Karakoca, Erhan and Karabulut Kurt, Güneş and Görçin, Ali},
  journal={IEEE Access}, 
  title={Hierarchical Dirichlet Process Based Gamma Mixture Modeling for Terahertz Band Wireless Communication Channels}, 
  year={2022}, 
  volume={10}, 
  pages={84635-84647}, 
  doi={10.1109/ACCESS.2022.3197603}
}
