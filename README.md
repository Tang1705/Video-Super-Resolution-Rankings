# Video Super-Resolution Rankings

## Video Super-Resolution

| Method              |                                     Official Repository                                     | Frames REDS/Vimeo  | Params(M)  | REDS4 PSNR                    | REDS4 SSIM                     | Vimeo-90K-T PSNR | Vimeo-90K-T SSIM | Vid4 PSNR                    | Vid4 SSIM                     |
|---------------------|:-------------------------------------------------------------------------------------------:|:------------------:|:----------:|-------------------------------|--------------------------------|------------------|------------------|------------------------------|-------------------------------|
| PSRT-recurrent [^1] |          [RethinkVSRAlignment](https://github.com/XPixelGroup/RethinkVSRAlignment)          |       16/14        |    13.4    | <font color=blue>32.72</font> | <font color=blue>0.9106</font> |<font color=red>38.27</font>|<font color=red>0.9536</font>| <font color=red>28.07</font> | <font color=red>0.8485</font> |
| RVRT [^2]           |                        [RVRT](https://github.com/JingyunLiang/RVRT)                         |       30/14        |10.8| <font color=red>32.75</font>  |    <font color=red>0.9113</font>|38.15|0.9527|<font color=blue>27.99</font>|<font color=blue>0.8426</font>|

## Video Frame Interpolation

https://github.com/AIVFI/Video-Frame-Interpolation-Rankings

## Compressed Video Super-Resolution

[^1]: Shuwei Shi, Jinjin Gu, Liangbin Xie, Xintao Wang, Yujiu Yang, and Chao Dong. 2022. Rethinking Alignment in Video Super-Resolution Transformers. In Advances in Neural Information Processing Systems. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^2]: Jingyun Liang, Yuchen Fan, Xiaoyu Xiang, Rakesh Ranjan, Eddy Ilg, Simon Green, Jiezhang Cao, Kai Zhang, Radu Timofte, and Luc Van Gool. Recurrent Video Restoration Transformer with Guided Deformable Attention. In Advances in Neural Information Processing Systems. [[NeurIPS 2022]](https://openreview.net/pdf?id=GKfNB4BegL)
