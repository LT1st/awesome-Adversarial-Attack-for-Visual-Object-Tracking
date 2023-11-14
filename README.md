# awesome-Adversarial-Attack-for-Visual-Object-Tracking
A paper collection of  Adversarial Attack for Visual Object Tracking. 


|                                               论文                                              |                                                   相关痛点及方法（分点简要总结）                                                  |                                                                                 方法                                                                                | 时间 期刊 |   |
|:-----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------:|---|
| Tracklet-Switch Adversarial Attack against Pedestrian Multi-Object Tracking Trackers	            |  MOT 的关联算法对跟踪过程中的错误具有鲁棒性；通过扰动很少的帧来跟踪后续帧中的目标                                                 | 第一个针对行人 MOT 跟踪器的对抗性攻击                                                                                                                               |           |   |
| Efficient Adversarial Attacks for Visual Object Tracking                                        | l drift loss combined with the embedded feature loss                                                                              |                                                                                                                                                                     | eccv_2020 |   |
| IoU Attack: Towards Temporally Coherent Black-Box Adversarial Attack for Visual Object Tracking |  IoU 攻击，它根据当前帧和历史帧的预测 IoU 分数顺序生成扰动。通过降低 IoU 分数                                                     | 降低了时间相干边界框（即对象运动）的准确性                                                                                                                          | cvpr 21   |   |
| Only Once Attack: Fooling the Tracker With Adversarial Template                                 | 仅针对初始帧进行攻击；攻击次数少                                                                                                  | 基于最小分数和基于最小 IoU 的损失函数                                                                                                                               |           |   |
| AdvBokeh: Learning to Adversarially Defocus Blur                                                | 深度引导的虚化合成网络 (DebsNet)，能够灵活地合成、重新聚焦和调整图像的虚化程度                                                    |                                                                                                                                                                     | eccv_2020 |   |
| SPARK: Spatial-Aware Online Incremental Attack Against Visual Tracking                          | 跟踪对象的移动轨迹                                                                                                                |                                                                                                                                                                     |           |   |
| Cooling-Shrinking Attack: Blinding the Tracker with Imperceptible Noises                        | 冷却热图上目标存在的热点区域，并迫使预测的边界框收缩，使跟踪目标对跟踪器不可见                                                    | 冷却热图上目标存在的热点区域，并迫使预测的边界框收缩，使跟踪目标对跟踪器不可见                                                                                      |           |   |
|  Physical adversarial textures that fool visual object tracking.                                | 纹理以数字或印刷海报的形式显示在物理世界中时，会导致视觉对象跟踪系统变得混乱                                                      | （EOT）算法来生成在不同条件下成像时欺骗跟踪模型的物理对手，但我们比较了不同调节变量（包括视点、照明和外观）的影响，以找到具有高结果的实用攻击设置对抗强度和收敛速度 |           |   |
| One-Shot Adversarial Attacks on Visual Tracking With Dual Attention                             | 初始帧中的目标块上添加轻微的扰动                                                                                                  |                                                                                                                                                                     | CVPR 22   |   |
| Universal Physical Camouflage Attacks on Object Detectors                                       | UPC 通过联合欺骗区域提议网络;对非刚性或非平面物体有效，我们引入了一组用于模仿可变形属性的变换;第一个标准化虚拟数据库 AttackScenes |                                                                                                                                                                     |           |   |
| SPARK: Spatial-Aware Online Incremental Attack Against Visual Tracking                          | 跟踪跟踪对象的移动轨迹；在线生成；1）很难生成可以跨帧传输的难以察觉的扰动，2）实时跟踪器要求攻击满足一定的效率水平。              | 使用 30 作为攻击间隔，因为视频通常为 30 fps，这样的设置自然利用了第 29 帧和第 30 帧之间的潜在延迟                                                                   | ECCV 2020 |   |

## Paper with code
1. FairMOT-attack

[FairMOT-attack](https://github.com/DerryHub/FairMOT-attack)

3. IoUattack
   
[IoUattack](https://github.com/VISION-SJTU/IoUattack)
https://arxiv.org/pdf/2103.14938.pdf

5. jadena
   
"Can You Spot the Chameleon? Adversarially Camouflaging Images from Co-Salient Object Detection" in CVPR 2022

https://github.com/tsingqguo/jadena

4.CSA

 CVPR2020 Paper Cooling-Shrinking Attack: Blinding the tracker with imperceptible noises
 
https://github.com/MasterBin-IIAU/CSA


## Paper without code


