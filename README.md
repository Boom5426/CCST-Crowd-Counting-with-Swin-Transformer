# CCST-Crowd-Counting-with-Swin-Transformer

This is the key code of the paper [CCST: Crowd Counting with Swin Transformer](https://link.springer.com/article/10.1007/s00371-022-02485-3)

## Abstruct:
Accurately estimating the number of individuals contained in an image is the purpose of the crowd counting. It has always faced two major difficulties: uneven distribution of crowd density and large span of head size. Focusing on the former, most CNN-based methods divide the image into multiple patches for processing, ignoring the connection between the patches. For the latter, the multi-scale feature fusion method using feature pyramid ignores the matching relationship between the
head size and the hierarchical features. In response to the above issues, we propose a crowd counting network named CCST based on swin transformer, and tailor a feature adaptive fusion regression head called FAFHead. Swin transformer can fully exchange information within and between patches, and effectively alleviate the problem of uneven distribution of crowd density. FAFHead can adaptively fuse multi-level features, improve the matching relationship between head size and feature
pyramid hierarchy, and relief the problem of large span of head size available. Experimental results on common datasets show that CCST has better counting performance than all weakly supervised counting works and great majority of popular density map-based fully supervised works.

## Overview
![image](https://github.com/Boli-trainee/CCST-Crowd-Counting-with-Swin-Transformer/assets/83391363/cca2ee52-921e-41b0-9be3-ed2b0c379e21)



# Reference
If you find this project is useful for your research, please cite:
```
@article{li2023ccst,
  title={CCST: crowd counting with swin transformer},
  author={Li, Bo and Zhang, Yong and Xu, Haihui and Yin, Baocai},
  journal={The Visual Computer},
  volume={39},
  number={7},
  pages={2671--2682},
  year={2023},
  publisher={Springer}
}
```

## Baseline:
If you want to train the model, please put the module in [Trancrowd](https://github.com/dk-liang/TransCrowd)

```
@article{liang2022transcrowd,
  title={TransCrowd: weakly-supervised crowd counting with transformers},
  author={Liang, Dingkang and Chen, Xiwu and Xu, Wei and Zhou, Yu and Bai, Xiang},
  journal={Science China Information Sciences},
  volume={65},
  number={6},
  pages={1--14},
  year={2022},
  publisher={Springer}
}
```
