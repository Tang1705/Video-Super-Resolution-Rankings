# Video Super-Resolution Rankings

## Video Super-Resolution

| Method                                                                   |                Frames REDS/Vimeo                | Params(M) | REDS4 PSNR                    | REDS4 SSIM                     | Vimeo-90K-T PSNR              | Vimeo-90K-T SSIM               | Vid4 PSNR                     | Vid4 SSIM                      |
|--------------------------------------------------------------------------|:-----------------:|:---------:|-------------------------------|--------------------------------|-------------------------------|--------------------------------|-------------------------------|--------------------------------|
| [PSRT-recurrent](https://github.com/XPixelGroup/RethinkVSRAlignment) [^1] |       16/14       |   13.4    | <font color=blue>32.72</font> | <font color=blue>0.9106</font> | <font color=red>38.27</font>  | <font color=red>0.9536</font>  | <font color=red>28.07</font>  | <font color=red>0.8485</font>  |
| [RVRT](https://github.com/JingyunLiang/RVRT) [^2]                                                          |                          30/14       |   10.8    | <font color=red>32.75</font>  | <font color=red>0.9113</font>  | 38.15                         | 0.9527                         | <font color=blue>27.99</font> | <font color=blue>0.8426</font> |
| [VRT](https://github.com/JingyunLiang/VRT) [^3]                                                               |                                   16/7        |   35.6    | 32.19                         | 0.9006                         | <font color=blue>38.20</font> | <font color=blue>0.9530</font> | 27.93                         | 0.8425                         |
| [TTVSR](https://github.com/researchmm/TTVSR) [^4]                                                              |50/-|6.8|32.12|0.9021|37.92|0.9526|28.40|0.8643|                                                         |

## Video Frame Interpolation

https://github.com/AIVFI/Video-Frame-Interpolation-Rankings

## Compressed Video Super-Resolution

[^1]: Rethinking Alignment in Video Super-Resolution Transformers. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^2]: Recurrent Video Restoration Transformer with Guided Deformable Attention. [[NeurIPS 2022]](https://openreview.net/pdf?id=GKfNB4BegL)
[^3]: VRT: A Video Restoration Transformer. [[arxiv 2022]](https://arxiv.org/pdf/2201.12288.pdf)
[^4]: Learning Trajectory-Aware Transformer for Video Super-Resolution. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Trajectory-Aware_Transformer_for_Video_Super-Resolution_CVPR_2022_paper.pdf)