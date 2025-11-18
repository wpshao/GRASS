# GRASS: Glass Reflection Artifact Suppression Strategy via Virtual Point Removal in LiDAR Point Clouds

## 👥 Authors
**Wanpeng Shao**<sup>1</sup>, **Yu Zhang**<sup>1</sup>, YIfeiXue, **Tie Ji**, **Yizhen Lao**<sup>*</sup>

<sup>1</sup> These authors contributed equally to this work.  
<sup>*</sup> Corresponding author: yizhenlao@hnu.edu.cn

## 🏫 Affiliations
- **College of Computer Science and Electronic Engineering, Hunan University**  
  Lushan South Road, Lushanmen, Changsha 410082, Hunan, China

- **School of Design, Hunan University**  
  Pailou Road, South Campus, Taozihu, Changsha 410082, Hunan, China

## 📖 Abstract
In building measurement using terrestrial laser scanners (TLS), acquired 3D point clouds (3DPCs) often contain significant reflection artifacts caused by reflective glass surfaces. Such reflection artifacts significantly degrade the performance of downstream applications. This study proposes a novel strategy, called GRASS, to remove these reflections.

Specifically, candidate glass points are identified based on multi-echo returns caused by glass components. These potential glass regions are then refined through planar segmentation using geometric constraints. Then, we trace laser beam trajectories to identify the reflection affected zones based on the estimated glass planes and scanner positions. Finally, reflection artefacts are identified using dual criteria:

1. **Reflection symmetry** between artifacts and their source entities across glass components
2. **Geometric similarity** through a 3D deep neural network

We evaluate the effectiveness of the proposed solution across a variety of 3DPC datasets and demonstrate that the method can reliably estimate multiple glass regions and accurately identify virtual points. Furthermore, both qualitative and quantitative evaluations confirm that GRASS outperforms existing methods in removing reflection artifacts with a significant margin.

## ✨ Key Features
- 🔍 **Multi-echo analysis** for glass point identification
- 📐 **Geometric constraint-based** planar segmentation
- 📡 **Laser beam trajectory tracing** for reflection zone detection
- ⚖️ **Dual-criteria artifact identification** (symmetry + geometric similarity)
- 🧠 **3D deep neural network** integration

## 🏆 Performance Highlights
- ✅ **Significant improvement** in reflection artifact removal compared to existing methods
- ✅ **Reliable estimation** of multiple glass regions
- ✅ **Accurate virtual point identification**
- ✅ **Comprehensive qualitative and quantitative evaluations**

Data Download Link:
通过网盘分享的文件：ResearchData
链接: https://pan.baidu.com/s/1UNk7lZA2XmhW79OZFEgOBg 提取码: v4w5
