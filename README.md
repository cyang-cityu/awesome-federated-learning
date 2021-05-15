# awesome-federated-learning
This repo is a collection of AWESOME things about federated learning, including papers, code, etc. Feel free to star and fork.

# Contents
- [awesome-federated-learning](#awesome-federated-learning)
- [Contents](#contents)
- [Papers](#papers)
    - [Introduction & Survey](#introduction--survey)
    - [Global Model Fusion](#global-model-fusion)
    - [Local Model Training](#local-model-training)
    - [Model Inversion](#model-inversion)
    - [Specific Problem](#specific-problem)
    - [Medical Related](#medical-related)

# Papers
### Introduction & Survey
### Global Model Fusion
* Federated Learning with Fair Averaging [[IJCAI2021]](https://arxiv.org/pdf/2104.14937.pdf)
* Federated Learning with Matched Averaging [[ICLR2020]](https://openreview.net/pdf?id=BkluqlSFDS)[[Pytorch]](https://github.com/IBM/FedMA)
* Model Fusion via Optimal Transport [[NIPS2020]](https://proceedings.neurips.cc/paper/2020/file/fb2697869f56484404c8ceee2985b01d-Paper.pdf)[[Pytorch]](https://github.com/sidak/otfusion)

### Local Model Training
* Model-Contrastive Federated Learning [[CVPR2021]](https://arxiv.org/pdf/2103.16257.pdf)[[Pytorch]](https://github.com/QinbinLi/MOON)
* FedBN: Federated Learning on Non-IID Features via Local Batch Normalization [[ICLR2021]](https://arxiv.org/pdf/2102.07623.pdf)[[Pytorch]](https://github.com/med-air/FedBN)
* FedAMP: Personalized Cross-Silo Federated Learning on Non-IID Data [[AAAI2021]](https://arxiv.org/pdf/2007.03797.pdf)[[API]](https://t.ly/nGN9)
* FedNova: Tackling the Objective Inconsistency Problem in Heterogeneous Federated Optimization [[NIPS2020]](https://proceedings.neurips.cc/paper/2020/file/564127c03caab942e503ee6f810f54fd-Paper.pdf)[[Pytorch]](https://github.com/JYWa/FedNova)
* FedProx: Federated Optimization in Heterogeneous Networks [[MLSys2020]](https://arxiv.org/pdf/1812.06127.pdf)[[Pytorch]](https://github.com/litian96/FedProx)
* Federated Mutual Learning [[Arxiv2020]](https://arxiv.org/pdf/2006.16765.pdf)
* FedAvg: Communication-Efficient Learning of Deep Networks from Decentralized Data [[AISTATS2017]](https://arxiv.org/pdf/1602.05629.pdf)[[Pytorch]](https://github.com/shaoxiongji/federated-learning)
* On the Convergence of FedAvg on Non-IID Data [[ICLR2020]](https://arxiv.org/pdf/1907.02189.pdf)
  
### Model Inversion
* See through Gradients: Image Batch Recovery via GradInversion [[CVPR 2021]](https://arxiv.org/pdf/2104.07586.pdf)
* Provable Defense against Privacy Leakage in Federated Learning from Representation Perspective [[CVPR2021]](https://arxiv.org/pdf/2012.06043.pdf)
* The Secret Revealer: Generative Model-Inversion Attacks Against Deep Neural
Networks [[CVPR2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_The_Secret_Revealer_Generative_Model-Inversion_Attacks_Against_Deep_Neural_Networks_CVPR_2020_paper.pdf)
* Dreaming to Distill: Data-free Knowledge Transfer via DeepInversion [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yin_Dreaming_to_Distill_Data-Free_Knowledge_Transfer_via_DeepInversion_CVPR_2020_paper.pdf)[[Pytorch]](https://github.com/NVlabs/DeepInversion)
* Deep Leakage from Gradients [[NIPS2019]](https://arxiv.org/pdf/1906.08935.pdf)[[Pytorch]](https://github.com/mit-han-lab/dlg)
* iDLG: Improved Deep Leakage from Gradients [[Arxiv2020]](https://arxiv.org/pdf/2001.02610.pdf)
* Inverting Deep Generative models,
One layer at a time [[NIPS2019]](https://proceedings.neurips.cc/paper/2019/file/24389bfe4fe2eba8bf9aa9203a44cdad-Paper.pdf)

### Specific Problem
* Addressing Class Imbalance in Federated Learning [[AAAI2021]](https://arxiv.org/pdf/2008.06217.pdf)[[Pytorch]](https://github.com/balanced-fl/Addressing-Class-Imbalance-FL)
* Learn distributed GAN with Temporary
Discriminators [[ECCV2020]](https://arxiv.org/pdf/2007.09221.pdf)[[Pytorch]](https://github.com/huiqu18/TDGAN-PyTorch)
### Medical Related
* FedDG: Federated Domain Generalization on Medical Image Segmentation via Episodic Learning in Continuous Frequency Space [[CVPR2021]](https://arxiv.org/pdf/2103.06030.pdf)[[Pytorch]](https://github.com/liuquande/FedDG-ELCFS)
* Multi-site fMRI Analysis Using Privacy-preserving Federated Learning and Domain Adaptation: ABIDE Results [[MIA2020]](https://arxiv.org/pdf/2001.05647.pdf)[[Pytorch]](https://github.com/xxlya/Fed_ABIDE)
* Federated Semi-Supervised Learning for COVID Region Segmentation in Chest CT using Multi-National Data from China, Italy, Japan [[MIA2020]](https://arxiv.org/pdf/2011.11750.pdf)
* Variation-Aware Federated Learning with Multi-Source Decentralized Medical Image Data [[JBHI2020]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9268161)

