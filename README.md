## *BiPointNet: Binary Neural Network for Point Clouds*
This project is the official implementation of our accepted ICLR 2021 paper: *BiPointNet: Binary Neural Network for Point Clouds*. [[PDF]( https://openreview.net/forum?id=9QLRCVysdlO)]

![prediction example](https://htqin.github.io/Imgs/ICLR/overview_v1.png)

### Introduction
This work is based on our ICLR 2021 paper. To alleviate the resource constraint for real-time point cloud applications that run on edge devices, in this paper we present ***BiPointNet***, the first model binarization approach for efficient deep learning on point clouds. We first discover that the immense performance drop of binarized models for point clouds mainly stems from two challenges: aggregation-induced feature homogenization that leads to a degradation of information entropy, and scale distortion that hinders optimization and invalidates scale-sensitive structures. With theoretical justifications and in-depth analysis, our BiPointNet introduces Entropy-Maximizing Aggregation (EMA) to modulate the distribution before aggregation for the maximum information entropy, and Layer-wise Scale Recovery (LSR) to efficiently restore feature representation capacity. Extensive experiments show that BiPointNet outperforms existing binarization methods by convincing margins, at the level even comparable with the full precision counterpart. We highlight that our techniques are generic, guaranteeing significant improvements on various fundamental tasks and mainstream backbones, e.g., BiPointNet gives an impressive 14.7x speedup and 18.9x storage saving on real-world resource-constrained devices.

### Citation
If you find our work useful in your research, please consider citing:

```
@inproceedings{Qin:iclr21,
  author    = {Haotong Qin and Zhongang Cai and Mingyuan Zhang 
  and Yifu Ding and Haiyu Zhao and Shuai Yi 
  and Xianglong Liu and Hao Su},
  title     = {BiPointNet: Binary Neural Network for Point Clouds},
  booktitle = {ICLR},
  year      = {2021}
}
```

(Our code will be released soon.)

