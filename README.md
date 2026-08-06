# One Graph, Multiple Gains: Single High-Quality Item-Item Graph for Multimodal Recommendation

## Introduction

This is the Pytorch implementation for IIMRec paper:

>  One Graph, Multiple Gains: Single High-Quality Item-Item Graph for Multimodal Recommendation

## Environment Requirement

> Python 3.9
Pytorch 2.1.0

## Dataset

> All experiments conducted on four processed datasets: Baby, Sports, Clothing, TikTok

## Training
  ```
  cd ./src
  python main.py
  ```
## Result
<img src="image/result.png" width="900px" height="380px"/>

## Citing IIMRec

If you find IIMRec useful in your research, please consider citing our [paper](https://arxiv.org/pdf/2607.24607).

```
@article{xu2026one,
  title={One Graph, Multiple Gains: Single High-Quality Item-Item Graph for Multimodal Recommendation},
  author={Xu, Jinfeng and Chen, Zheyu and Peng, Ziyue and Yang, Shuo and Li, Jinze and Liu, Zewei and Li, Shujie and Du, Yipeng and Ngai, Edith CH},
  journal={arXiv preprint arXiv:2607.24607},
  year={2026}
}
```


## Acknowledgement

The structure of this code is based on [MRLib](https://github.com/Jinfeng-Xu/Multimodal-Recommendation-Library) and [MMRec](https://github.com/enoche/MMRec). Thank for their work.

*We will contribute this work to [MRLib](https://github.com/Jinfeng-Xu/Multimodal-Recommendation-Library), so that it can be used directly for fair benchmarking.*