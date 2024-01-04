---
layout: page
permalink: /publications/2023-12-26-conference-CheXNet/index.html
title: 2023-12-26-conference-CheXNet
---

[CheXNet: Combing Transformer and CNN for Thorax Disease Diagnosis from Chest X-ray Images](https://xinwu74.github.io/mypaper/Conference/2023PRCV-CheXNet.pdf)

<br>

DOI: [10.1007/978-981-99-8558-6_7](https://link.springer.com/chapter/10.1007/978-981-99-8558-6_7) [supp](https://xinwu74.github.io/mypaper/Conference/2023PRCV-CheXNet_Supp.pdf)

<br>

**Xin W**, Yue F, et al. (2023 Chinese Conference on Pattern Recognition and Computer Vision, CCF-C)  &nbsp;&nbsp;[Code](https://github.com/wuliwuxin/CheXNet) 

<br>


## Abstract
<br>

Multi-label chest X-ray (CXR) image classification aims to perform multiple disease label prediction tasks. This concept is more challenging than single-label classification problems. For instance, convolutional neural networks (CNNs) often struggle to capture the statistical dependencies between labels. Furthermore, the drawback of concatenating CNN and Transformer is the lack of direct interaction and information exchange between the two models. To address these issues, we propose a hybrid deep learning network named CheXNet. It consists of three main parts in the CNN and Transformer branches: Label Embedding and Multi-Scale Pooling module (MEMSP), Inner Branch module (IB), and Information Interaction module (IIM). Firstly, we employ label embedding to automatically capture label dependencies. Secondly, we utilize Multi-Scale Pooling (MSP) to fuse features from different scales and an IB to incorporate local detailed features. Additionally, we introduce a parallel structure that allows interaction between the CNN and the Transformer through the IIM. CNN can provide richer inputs to the Transformer through bottom-up feature extraction, whilst the Transformer can guide feature extraction in the CNN using top-down attention mechanisms. The effectiveness of the proposed method has been validated through qualitative and quantitative experiments on two large-scale multi-label CXR datasets with average AUCs of 82.56% and 76.80% for CXR11 and CXR14, respectively.

### Keywords

`Hybird network` `Multi-label` `Chest X-ray image`


**Model**
![model](https://xinwu74.github.io/publications/picture_model/CheXNet.png)

<br>

```bash
@inproceedings{wu2023chexnet,
  title={CheXNet: Combing Transformer and CNN for Thorax Disease Diagnosis from Chest X-ray Images},
  author={Wu, Xin and Feng, Yue and Xu, Hong and Lin, Zhuosheng and Li, Shengke and Qiu, Shihan and Liu, QiChao and Ma, Yuangang},
  booktitle={Chinese Conference on Pattern Recognition and Computer Vision (PRCV)},
  pages={73--84},
  year={2023},
  organization={Springer},
  doi={10.1007/978-981-99-8558-6_7}
}
```