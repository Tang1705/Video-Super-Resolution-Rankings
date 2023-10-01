# Video Super-Resolution Rankings

## Video Super-Resolution

| Method                                                                                        | Frames REDS/Vimeo | Params(M) | REDS4 PSNR                    | REDS4 SSIM                     | Vimeo-90K-T PSNR              | Vimeo-90K-T SSIM               | Vid4 PSNR                     | Vid4 SSIM                      |
| --------------------------------------------------------------------------------------------- | :---------------: | :-------: | ----------------------------- | ------------------------------ | ----------------------------- | ------------------------------ | ----------------------------- | ------------------------------ |
| [IART](https://github.com/kai422/IART) [^1]                                                   |       16/7        |   13.4    | <font color=red>32.90</font>  | <font color=red>0.9138</font>  | 38.14                         | 0.9528                         | <font color=blue>28.26</font> | <font color=blue>0.8517</font> |
| MFPI [^2]                                                                                     |        -/-        |    7.3    | <font color=blue>32.81</font> | 0.9106                         | <font color=red>38.28</font>  | 0.9534 | 28.11                         | 0.8481                         |
| [PSRT-recurrent](https://github.com/XPixelGroup/RethinkVSRAlignment) [^3]                     |       16/14       |   13.4    | 32.72                         | 0.9106                         | <font color=blue>38.27</font> | <font color=blue>0.9536</font>  | 28.07                         | 0.8485                         |
|DFVSR|-|7.1|32.76|0.9081|38.25|<font color=red>0.9556</font>|27.92|0.8427|
| [RVRT](https://github.com/JingyunLiang/RVRT) [^4]                                             |       30/14       |   10.8    | 32.75                         | <font color=blue>0.9113</font> | 38.15                         | 0.9527                         | 27.99                         | 0.8426                         |
| [FTVSR++](https://github.com/researchmm/FTVSR)                                                |         -         |   10.8    | 32.42                         | 0.907                          | -                             | -                              | <font color=red>28.80</font>  | <font color=red>0.868</font>   |
| [VRT](https://github.com/JingyunLiang/VRT) [^5]                                               |       16/7        |   35.6    | 32.19                         | 0.9006                         | 38.20                         | 0.9530                         | 27.93                         | 0.8425                         |
| [TTVSR](https://github.com/researchmm/TTVSR) [^6]                                             |       50/-        |    6.8    | 32.12                         | 0.9021                         | 37.92                         | 0.9526                         | 28.40                         | 0.8643                         |
| [TCNet](https://github.com/Kimsure/TCNet-for-VSR)[^6]                                         |         -         |    9.6    | 31.82                         | 0.9002                         | 37.94                         | 0.9514                         | 27.48                         | 0.8380                         |
| [RTA](https://github.com/redrock303/Revisiting-Temporal-Alignment-for-Video-Restoration) [^7] |        5/7        |   17.0    | 31.30                         | 0.8850                         | 37.84                         | 0.9498                         | 27.90                         | 0.8380                         |
| [BasicVSR++](https://github.com/ckkelvinchan/BasicVSR_PlusPlus) [^8]                          |       30/14       |    7.3    | 32.39                         | 0.9069                         | 37.79                         | 0.9500                         | 27.79                         | 0.8400                         |
| [ETDM](https://github.com/junpan19/ETDM) [^9]                                                 |         -         |    8.4    | 32.15                         | 0.9024                         | -                             | -                              | 28.81                         | 0.8725                         |
| [FTVSR](https://github.com/researchmm/FTVSR)                                                  |         -         |   10.8    | 31.82                         | 0.896                          | -                             | -                              | 28.31                         | 0.860                          |
|[MSHPFNL](https://github.com/psychopa4/MSHPFNL)|-|7.77|-|-|36.75|0.9406|27.70|0.8472|
|ICNet|-|18.34|31.71|0.8963|37.72|0.9477|27.43|0.8287|
| [IconVSR](https://github.com/ckkelvinchan/BasicVSR-IconVSR) [^10]                             |       15/14       |    8.7    | 31.67                         | 0.8948                         | 37.47                         | 0.9476                         | 27.39                         | 0.8279                         |
| [BasicVSR](https://github.com/ckkelvinchan/BasicVSR-IconVSR) [^10]                            |       15/14       |    6.3    | 31.42                         | 0.8909                         | 37.18                         | 0.9450                         | 27.24                         | 0.8251                         |
| [VSR-T](https://github.com/caojiezhang/VSR-Transformer) [^11]                                 |        5/7        |   32.6    | 31.19                         | 0.8815                         | 37.71                         | 0.9494                         | 27.36                         | 0.8258                         |
| [TGA](https://github.com/junpan19/VSR_TGA)                                                    |         -         |    5.8    | -                             | -                              | 37.43                         | 0.9480                         | 27.19                         | 0.8213                         |
| [RLSP](https://github.com/dariofuoli/RLSP)                                                    |         -         |    4.2    | -                             | -                              | 37.39                         | 0.9470                         | 27.15                         | 0.8202                         |
| [EDVR](https://github.com/xinntao/EDVR)                                                       |        5/7        |   20.6    | 31.09                         | 0.8800                         | 37.61                         | 0.9489                         | 27.35                         | 0.8264                         |
| MSFFN|-|-|-|-|37.33|0.9467|27.23|0.8218|
| [MuCAN](https://github.com/dvlab-research/Simple-SR)                                          |        5/7        |     -     | 30.88                         | 0.8750                         | 37.32                         | 0.9465                         | -                             | -                              |
| [RBPN](https://github.com/alterzero/RBPN-PyTorch)                                             |        7/7        |   12.2    | 30.09                         | 0.8590                         | 37.07                         | 0.9435                         | 27.12                         | 0.8180                         |
| [PFNL](https://github.com/psychopa4/PFNL)                                                     |        7/7        |    3.0    | 29.63                         | 0.8502                         | 36.14                         | 0.9363                         | 26.73                         | 0.8029                         |
| [DUF](https://github.com/HymEric/VSR-DUF-Reimplement)                                         |        7/7        |    5.8    | 28.63                         | 0.8251                         | -                             | -                              | 27.33                         | 0.8319                         |
| [FRVSR](https://github.com/msmsajjadi/FRVSR)                                                  |         -         |    5.1    | -                             | -                              | -                             | -                              | 26.69                         | 0.8220                         |
|[D3Dnet](https://github.com/XinyiYing/D3Dnet)|-|2.58|-|-|35.65 | 0.933|26.52 |0.799|
|[TOFlow](https://github.com/anchen1011/toflow)|5/7|-|27.98|0.7990|33.08|0.9054|25.89|0.7651|
|[3DSRnet ](https://github.com/sooyekim/3DSRnet)|-|-|-|-|-|-|25.71 |0.7588|
|[SPMC](https://github.com/jiangsutx/SPMC_VideoSR)|-|-|-|-|-|-|25.52|0.76|
|[VESPCN](https://github.com/JuheonYi/VESPCN-PyTorch)|-|-|-|-|-|-|25.35|0.7577|
|VSRNet|-|0.27|-|-|-|-|22.81|0.65|
|Bicubic|-|-|26.14 |0.7292|31.32| 0.8684|23.78|0.6347|


## Space-Time Video Super-Resolution

https://github.com/AIVFI/Video-Frame-Interpolation-Rankings

## Compressed Video Super-Resolution

## Awesome-Super-Resolution

https://github.com/ChaofWang/Awesome-Super-Resolution

[^1]: Rethinking Alignment in Video Super-Resolution

Transformers. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^2]: Rethinking Alignment in Video Super-Resolution
Transformers. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^3]: Rethinking Alignment in Video Super-Resolution
Transformers. [[NeurIPS 2022]](https://openreview.net/pdf?id=NgIf3FpcHie)
[^4]: Recurrent Video Restoration Transformer with Guided Deformable
Attention. [[NeurIPS 2022]](https://openreview.net/pdf?id=GKfNB4BegL)
[^5]: VRT: A Video Restoration Transformer. [[arxiv 2022]](https://arxiv.org/pdf/2201.12288.pdf)
[^6]: Learning Trajectory-Aware Transformer for Video
Super-Resolution. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Trajectory-Aware_Transformer_for_Video_Super-Resolution_CVPR_2022_paper.pdf)
[^7]: Revisiting Temporal Alignment for Video
Restoration . [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Revisiting_Temporal_Alignment_for_Video_Restoration_CVPR_2022_paper.pdf)
[^8]: BasicVSR++: Improving Video Super-Resolution with Enhanced Propagation and
Alignment. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Chan_BasicVSR_Improving_Video_Super-Resolution_With_Enhanced_Propagation_and_Alignment_CVPR_2022_paper.pdf)
[^9]: Look Back and Forth: Video Super-Resolution with Explicit Temporal Difference
Modeling. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Isobe_Look_Back_and_Forth_Video_Super-Resolution_With_Explicit_Temporal_Difference_CVPR_2022_paper.pdf)
[^10]: BasicVSR: The Search for Essential Components in Video Super-Resolution and
Beyond. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Chan_BasicVSR_The_Search_for_Essential_Components_in_Video_Super-Resolution_and_CVPR_2021_paper.pdf)
[^11]: Video Super-Resolution Transformer. [[arxiv 2021]](https://arxiv.org/pdf/2106.06847.pdf)
