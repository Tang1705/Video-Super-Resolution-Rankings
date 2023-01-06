# Video Super-Resolution Rankings

## Video Super-Resolution

| Method                                                                                        |                Frames REDS/Vimeo                | Params(M)  | REDS4 PSNR                    | REDS4 SSIM                     | Vimeo-90K-T PSNR              | Vimeo-90K-T SSIM               | Vid4 PSNR                     | Vid4 SSIM                      |
|-----------------------------------------------------------------------------------------------|:-----------------:|:----------:|-------------------------------|--------------------------------|-------------------------------|--------------------------------|-------------------------------|--------------------------------|
| [PSRT-recurrent](https://github.com/XPixelGroup/RethinkVSRAlignment) [^1]                     |       16/14       |    13.4    | <font color=blue>32.72</font> | <font color=blue>0.9106</font> | <font color=red>38.27</font>  | <font color=red>0.9536</font>  | <font color=red>28.07</font>  | <font color=red>0.8485</font>  |
| [RVRT](https://github.com/JingyunLiang/RVRT) [^2]                                             |                          30/14       |    10.8    | <font color=red>32.75</font>  | <font color=red>0.9113</font>  | 38.15                         | 0.9527                         | <font color=blue>27.99</font> | <font color=blue>0.8426</font> |
| [VRT](https://github.com/JingyunLiang/VRT) [^3]                                               |                                   16/7        |    35.6    | 32.19                         | 0.9006                         | <font color=blue>38.20</font> | <font color=blue>0.9530</font> | 27.93                         | 0.8425                         |
| [TTVSR](https://github.com/researchmm/TTVSR) [^4]                                             |50/-|    6.8     | 32.12                         | 0.9021                         | 37.92                         | 0.9526                         | 28.40                         |0.8643|                                                         |
| [RTA](https://github.com/redrock303/Revisiting-Temporal-Alignment-for-Video-Restoration) [^5] | 5/7|    17.0    | 31.30                         | 0.8850                         | 37.84                         | 0.9498                         | 27.90                         |0.8380|
| [BasicVSR++](https://github.com/ckkelvinchan/BasicVSR_PlusPlus) [^6]                          |30/14|    7.3     | 32.39                         | 0.9069                         | 37.79                         | 0.9500                         | 27.79                         |0.8400|
| [IconVSR](https://github.com/ckkelvinchan/BasicVSR-IconVSR) [^7]                              |15/14|    8.7     | 31.67                         | 0.8948                        | 37.47                          | 0.9476                        | 27.39                          | 0.8279                        |
| [BasicVSR](https://github.com/ckkelvinchan/BasicVSR-IconVSR) [^7]                             |15/14| 6.3|   31.42                       | 0.8909                        | 37.18                          | 0.9450                        | 27.24                          | 0.8251                        |


## Space-Time Video Super-Resolution

https://github.com/AIVFI/Video-Frame-Interpolation-Rankings

## Compressed Video Super-Resolution

## Awesome-Super-Resolution

https://github.com/ChaofWang/Awesome-Super-Resolution

[^1]: Rethinking Alignment in Video Super-Resolution Transformers. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^2]: Recurrent Video Restoration Transformer with Guided Deformable Attention. [[NeurIPS 2022]](https://openreview.net/pdf?id=GKfNB4BegL)
[^3]: VRT: A Video Restoration Transformer. [[arxiv 2022]](https://arxiv.org/pdf/2201.12288.pdf)
[^4]: Learning Trajectory-Aware Transformer for Video Super-Resolution. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Trajectory-Aware_Transformer_for_Video_Super-Resolution_CVPR_2022_paper.pdf)
[^5]: Revisiting Temporal Alignment for Video Restoration . [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Revisiting_Temporal_Alignment_for_Video_Restoration_CVPR_2022_paper.pdf)
[^6]: BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and Alignment. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Chan_BasicVSR_Improving_Video_Super-Resolution_With_Enhanced_Propagation_and_Alignment_CVPR_2022_paper.pdf)
[^7]: BasicVSR: The Search for Essential Components in Video Super-Resolution and Beyond. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Chan_BasicVSR_The_Search_for_Essential_Components_in_Video_Super-Resolution_and_CVPR_2021_paper.pdf)
