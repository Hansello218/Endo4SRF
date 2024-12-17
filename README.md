# Endo4SRF:Learning Radiance Field for Dynamic Surface Reconstruction of Surgical Tissues with Obstacle Stealth Under Single-view and Depth-free Monocular Endoscopy
*Bo Lu, Member, IEEE, Chao He, Wenjie Hou, Lijun Han, Hesheng Wang, Senior Member, IEEE,
Lining Sun, Zhaolei Jiang, and Peng Qi, Member, IEEE*

### [[Paper](https://ieeexplore.ieee.org/document/10797692)]

<img src="figfile/fig2.png" alt="Setting" width="600"/>

Abstract: *Monocular endoscope-based reconstruction of dynamic 3D surgical fields is beneficial for both intraoperative manual/robotic manipulation and post-operative surgical skills training. However, the natural characteristics of tissue deformations with instruments and blood obscuration bring great challenges to 3D scene awareness, especially under sparse viewpoints limited by laparoscopic movements. In this work, we propose Endo-4 S RF, an effective Neural Radiance Field (NeRF)-based method that can reconstruct deformable tissues with instruments stealth by solely relying on monocular endoscopic image flows from a single viewpoint. Specifically, to enhance the 3D reconstruction accuracy under the deficiency of depth ground truth, we devised a dynamic Gaussian-based neural sampling strategy, leveraging the depth inherently obtained from NeRF and the conjunction information inferred by a prior learning-based depth estimation network. Besides, we integrated the Signed Distance Function (SDF) and resolved its singularity problem by furnishing additional geometric constraints for the neural radiance field, thereby achieving precise reconstruction of dynamic scenes devoid of depth ground truth supervision. Furthermore, adopting spherical harmonic functions for color fitting has significantly improved our model's computational efficiency and rendering quality. We extensively performed cross-validation experiments to verify the performance using public and in-house datasets. Our quantitative and qualitative results demonstrate remarkable superiority over the state-of-the-art (SOTA) approaches concerning depth prediction accuracy, image rendering quality, model training efficiency, and 3D reconstruction outcomes.*


### Pipeline

<img src="figfile/fig1.png" alt="Pipeline" width="800"/>

## News
- [2024-12-05] Our paper has been accpetd by IEEE Journal of Biomedical and Health Informatics!
- [2024-12-17] Code is coming soon!
