# 3D Skeleton Based Person Re-Identification (SRID)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 
[![Visits Badge](https://badges.pufler.dev/visits/Kali-Hac/3D-skeleton-based-person-re-ID-review)](https://badges.pufler.dev/visits/Kali-Hac/3D-skeleton-based-person-re-ID-review)

A professionally curated list of awesome resources (paper, code, data, etc.) on **3D Skeleton Based Person Re-ID (SRID)**, which is the first work to comprehensively and systematically summarize the recent advances of SRID research to the best of our knowledge.

We will continue to update this list with the newest resources. If you find any missed resources (paper/code) or errors, please feel free to open an issue or make a pull request.

<!-- vscode-markdown-toc -->
- [**Benchmark Datasets**](#benchmark-datasets)
- [**Studies by Different Categories**](#Studies-by-Different-Categories)
	- [**Hand-Crafted Methods**](#Hand-Crafted-Methods)
	- [**Sequence Learning Methods**](#Sequence-Learning-Methods)
	- [**Graph Learning Methods**](#Graph-Learning-Methods)
- [**Studies by Different Years**](#Studies-by-Different-Years)
	- [**2023**](#2023)
	- [**2022**](#2022)
	- [**2021**](#2021)
	- [**2020**](#2020)
	- [**2019**](#2019)
	- [**2018**](#2018)
	- [**2017**](#2017)
	- [**2016**](#2016)
	- [**2015**](#2015)
	- [**2014**](#2014)
	- [**Before 2014**](#before-2014)
- [**Leaderboards**](#leaderboards)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## Benchmark Datasets
Overview of commonly-used benchmark datasets for **3D skeleton-based person re-identification** and their statistics. The number of skeletons in the training set is estimated and reported. “Ego” denotes a single or egocentric view. We also include person re-ID datasets with 2D/3D skeletons estimated from RGB videos.

|**# Datasets**    | **Year** | **Source**                  | **# ID** | **# Skeleton** | **# View** |
|-------------------|:--------:|-----------------------------|:--------:|---------------:|:----------:|
| PAVIS RGBD-ID     |   2012   | Kinect V1                   |    79    |              — |     Ego    |
| BIWI RGBD-ID      |   2013   | Kinect V1                   |    50    |         205.8K |     Ego    |
| IAS-Lab RGBD-ID   |   2013   | Kinect V1                   |    11    |          89.0K |     Ego    |
| KGBD              |   2014   | Kinect V1                   |    164   |         188.7K |     Ego    |
| KinectREID        |   2015   | Kinect V1                   |    71    |           4.8K |      7     |
| UPCV1             |   2015   | Kinect V1                   |    30    |          13.1K |     Ego    |
| UPCV2             |   2016   | Kinect V2                   |    30    |          26.3K |     Ego    |
| Florence 3D Re-ID |   2016   | Kinect V2                   |    16    |          18.0K |     Ego    |
| KS20              |   2017   | Kinect V2                   |    20    |          36.0K |      5     |
| Freestyle Walks   |   2017   | Kinect V2                   |    90    |              — |     Ego    |
| CAISA-B-3D        |   2020   | _Estimated from RGB videos_ |    124   |         706.5K |     11     |
| OUMVLP-Pose-2D    |   2020   | _Estimated from RGB videos_ |   10307  |        6667.0K |     14     |
| PoseTrackReID-2D  |   2020   | _Estimated from RGB videos_ |   5350   |          53.6K |      —     |


## Studies by Different Categories

![image](https://github.com/Kali-Hac/3D-skeleton-based-person-re-ID-review/blob/main/overview/method_overview.jpg)

### Hand-Crafted Methods
- [One-Shot Person Re-identification with a Consumer Depth Camera](https://doi.org/10.1007/978-1-4471-6296-4\_8) (_Person Re-Identification 2014_)

- [3D reconstruction of freely moving persons for re-identification with a depth sensor](https://doi.org/10.24963/ijcai.2020/125) (_ICRA 2014_)

- [A feature-based approach to people re-identification using skeleton keypoints](https://www.researchgate.net/profile/Matteo-Munaro/publication/286624461_A_feature-based_approach_To_people_re-identification_using_skeleton_keypoints/links/566ea2f008ae1a797e406d8a/A-feature-based-approach-To-people-re-identification-using-skeleton-keypoints.pdf) (_ICRA 2014_)

- [People re-identification using 3D descriptor with skeleton information](https://ieeexplore.ieee.org/abstract/document/7333986) (_International Conference on Informatics, Electronics \& Vision 2015_)

- [Multimodal person reidentification using RGB-D cameras](https://ieeexplore.ieee.org/abstract/document/7088601) (_IEEE Transactions on Circuits and Systems for Video Technology 2015_)

- [Person Identification Using Anthropometric and Gait Data from Kinect Sensor](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9680) (_AAAI 2015_)

- [Long term person re-identification from depth cameras using facial and skeleton data](https://www.researchgate.net/profile/Stefano-Berretti/publication/325161671_Long_Term_Person_Re-identification_from_Depth_Cameras_Using_Facial_and_Skeleton_Data/links/5b84ffc892851c1e1236dd11/Long-Term-Person-Re-identification-from-Depth-Cameras-Using-Facial-and-Skeleton-Data.pdf) (_ICPR 2016_)

- [Human identification from freestyle walks using posture-based gait feature](https://ieeexplore.ieee.org/abstract/document/8007293) (_IEEE Transactions on Information Forensics and Security 2017_)

- [Context-aware person re-identification in the wild via fusion of gait and anthropometric features](https://vislab.isr.tecnico.ulisboa.pt/wp-content/uploads/2017/05/anambiar_BWild2017.pdf) (_International Conference on Automatic Face \& Gesture Recognition 2017_)

- [Cross-context analysis for long-term view-point invariant person re-identification via soft-biometrics using depth sensor](https://www.scitepress.org/papers/2018/66206/66206.pdf) (_VISIGRAPP 2018_)

- [Enhanced skeleton and face 3D data for person re-identification from depth cameras](https://doi.org/10.24963/ijcai.2020/125) (_Computers\&Graphics 2019_)

- [Person Re-Identification from Different Views based on Dynamic Linear Combination of Distances](https://lilloa.univ-lille.fr/bitstream/handle/20.500.12210/57071/https:/halshs.archives-ouvertes.fr/halshs-03145152/document?sequence=1) (_Multimedia Tools and Applications 2021_) [[Github](https://github.com/Elaoud/re-id)] ![](https://img.shields.io/github/stars/Elaoud/re-id.svg?style=social)

- [Re-visiting k-Reciprocal Distance Re-ranking for Skeleton-Based Person Re-identification](https://ieeexplore.ieee.org/document/9913633) (_IEEE Signal Processing Letters 2022_)


### Sequence Learning Methods

- [Person identification by walking gesture using skeleton sequences](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_18) (_Advanced Concepts for Intelligent Vision Systems 2020_)

- [Learning 3D spatiotemporal gait feature by convolutional network for person identification](https://www.sciencedirect.com/science/article/abs/pii/S0925231220302381) (_Neurocomputing 2020_)

- [A model-based gait recognition method with body pose and human prior knowledge](http://r.web.umkc.edu/rlyfv/papers/poseGait.pdf) (_Pattern Recognition 2020_) [[Github](https://github.com/RijunLiao/PoseGait)] ![](https://img.shields.io/github/stars/RijunLiao/PoseGait.svg?style=social) (PoseGait is extended for SRID in recent studies from 2021-2023)

- [Self-Supervised Gait Encoding with Locality-Aware Attention for Person Re-Identification](https://doi.org/10.24963/ijcai.2020/125) (_IJCAI 2020_) [[Github](https://github.com/Kali-Hac/SGE-LA)] ![](https://img.shields.io/github/stars/Kali-Hac/SGE-LA.svg?style=social)

- [A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification](https://arxiv.org/abs/2009.03671) (_IEEE Transactions on Pattern Analysis and Machine Intelligence 2021_) [[Github](https://github.com/Kali-Hac/Locality-Awareness-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/Locality-Awareness-SGE.svg?style=social)

- [Human Identification System Using 3D Skeleton-Based Gait Features and LSTM Model](https://www.sciencedirect.com/science/article/abs/pii/S1047320321002807) (_Journal of Visual Communication and Image Representation 2022_)

- [SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2022_) [[Github](https://github.com/Kali-Hac/SimMC)] ![](https://img.shields.io/github/stars/Kali-Hac/SimMC.svg?style=social)
  
- [Hierarchical Skeleton Meta-prototype Contrastive Learning with Hard Skeleton Mining for Unsupervised Person Re-identification](https://arxiv.org/pdf/2307.12917)  (_International Journal of Computer Vision 2023_) [[Github](https://github.com/Kali-Hac/Hi-MPC)] ![](https://img.shields.io/github/stars/Kali-Hac/Hi-MPC.svg?style=social)

### Graph Learning Methods

- [SM-SGE: A Self-Supervised Multi-Scale Skeleton Graph Encoding Framework for Person Re-Identification](https://doi.org/10.1145/3474085.3475330) (_ACM MM 2021_) [[Github](https://github.com/Kali-Hac/SM-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/SM-SGE.svg?style=social)

- [Multi-Level Graph Encoding with Structural-Collaborative Relation Learning for Skeleton-Based Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2021_) [[Github](https://github.com/Kali-Hac/MG-SCR)] ![](https://img.shields.io/github/stars/Kali-Hac/MG-SCR.svg?style=social)

- [TranSG: Transformer-based Skeleton Graph Prototype Contrastive Learning with Structure-Trajectory Prompted Reconstruction for Person Re-identification](http://openaccess.thecvf.com/content/CVPR2023/papers/Rao_TranSG_Transformer-Based_Skeleton_Graph_Prototype_Contrastive_Learning_With_Structure-Trajectory_Prompted_CVPR_2023_paper.pdf) (_CVPR 2023_) [[Github](https://github.com/Kali-Hac/TranSG)] ![](https://img.shields.io/github/stars/Kali-Hac/TranSG.svg?style=social)

- [Skeleton Prototype Contrastive Learning with Multi-level Graph Relation Modeling for Unsupervised Person Re-identification](https://arxiv.org/pdf/2208.11814) (_Arxiv (Preprint) 2022_) [[Github](https://github.com/Kali-Hac/SPC-MGR)] ![](https://img.shields.io/github/stars/Kali-Hac/SPC-MGR.svg?style=social)


## Studies by Different Years
### **2023**
- [TranSG: Transformer-based Skeleton Graph Prototype Contrastive Learning with Structure-Trajectory Prompted Reconstruction for Person Re-identification](http://openaccess.thecvf.com/content/CVPR2023/papers/Rao_TranSG_Transformer-Based_Skeleton_Graph_Prototype_Contrastive_Learning_With_Structure-Trajectory_Prompted_CVPR_2023_paper.pdf) (_CVPR 2023_) [[Github](https://github.com/Kali-Hac/TranSG)] ![](https://img.shields.io/github/stars/Kali-Hac/TranSG.svg?style=social)

- [Hierarchical Skeleton Meta-prototype Contrastive Learning with Hard Skeleton Mining for Unsupervised Person Re-identification](https://arxiv.org/pdf/2307.12917)  (_International Journal of Computer Vision 2023_) [[Github](https://github.com/Kali-Hac/Hi-MPC)] ![](https://img.shields.io/github/stars/Kali-Hac/Hi-MPC.svg?style=social)

### **2022**
- [SimMC: Simple Masked Contrastive Learning of Skeleton Representations for Unsupervised Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2022_) [[Github](https://github.com/Kali-Hac/SimMC)] ![](https://img.shields.io/github/stars/Kali-Hac/SimMC.svg?style=social)

- [Re-visiting k-Reciprocal Distance Re-ranking for Skeleton-Based Person Re-identification](https://ieeexplore.ieee.org/document/9913633) (_IEEE Signal Processing Letters 2022_)

- [Skeleton Prototype Contrastive Learning with Multi-level Graph Relation Modeling for Unsupervised Person Re-identification](https://arxiv.org/pdf/2208.11814) (_Arxiv (Preprint) 2022_) [[Github](https://github.com/Kali-Hac/SPC-MGR)] ![](https://img.shields.io/github/stars/Kali-Hac/SPC-MGR.svg?style=social)

- [Human Identification System Using 3D Skeleton-Based Gait Features and LSTM Model](https://www.sciencedirect.com/science/article/abs/pii/S1047320321002807) (_Journal of Visual Communication and Image Representation 2022_)

### **2021**
- [SM-SGE: A Self-Supervised Multi-Scale Skeleton Graph Encoding Framework for Person Re-Identification](https://doi.org/10.1145/3474085.3475330) (_ACM MM 2021_) [[Github](https://github.com/Kali-Hac/SM-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/SM-SGE.svg?style=social)

- [Multi-Level Graph Encoding with Structural-Collaborative Relation Learning for Skeleton-Based Person Re-Identification](https://doi.org/10.48550/arXiv.2204.09826) (_IJCAI 2021_) [[Github](https://github.com/Kali-Hac/MG-SCR)] ![](https://img.shields.io/github/stars/Kali-Hac/MG-SCR.svg?style=social)

- [A Self-Supervised Gait Encoding Approach with Locality-Awareness for 3D Skeleton Based Person Re-Identification](https://arxiv.org/abs/2009.03671) (_IEEE Transactions on Pattern Analysis and Machine Intelligence 2021_) [[Github](https://github.com/Kali-Hac/Locality-Awareness-SGE)] ![](https://img.shields.io/github/stars/Kali-Hac/Locality-Awareness-SGE.svg?style=social)

- [Person Re-Identification from Different Views based on Dynamic Linear Combination of Distances](https://lilloa.univ-lille.fr/bitstream/handle/20.500.12210/57071/https:/halshs.archives-ouvertes.fr/halshs-03145152/document?sequence=1) (_Multimedia Tools and Applications 2021_) [[Github](https://github.com/Elaoud/re-id)] ![](https://img.shields.io/github/stars/Elaoud/re-id.svg?style=social)

### **2020**
- [Self-Supervised Gait Encoding with Locality-Aware Attention for Person Re-Identification](https://doi.org/10.24963/ijcai.2020/125) (_IJCAI 2020_) [[Github](https://github.com/Kali-Hac/SGE-LA)] ![](https://img.shields.io/github/stars/Kali-Hac/SGE-LA.svg?style=social)

<!--
- [Human skeleton mutual learning for person re-identification](https://doi.org/10.1016/j.neucom.2019.12.120) (_Neurocomputing 2020_)
-->

- [Learning 3D spatiotemporal gait feature by convolutional network for person identification](https://www.sciencedirect.com/science/article/abs/pii/S0925231220302381) (_Neurocomputing 2020_)

- [A model-based gait recognition method with body pose and human prior knowledge](http://r.web.umkc.edu/rlyfv/papers/poseGait.pdf) (_Pattern Recognition 2020_) [[Github](https://github.com/RijunLiao/PoseGait)] ![](https://img.shields.io/github/stars/RijunLiao/PoseGait.svg?style=social) (PoseGait is extended for SRID in recent studies from 2021-2023)

- [Person identification by walking gesture using skeleton sequences](https://link.springer.com/chapter/10.1007/978-3-030-40605-9_18) (_Advanced Concepts for Intelligent Vision Systems 2020_)


### **2019**
<!-- 
- [SKEPRID: Pose and Illumination Change-Resistant Skeleton-Based Person Re-Identification](https://dl.acm.org/doi/pdf/10.1145/3243217) (_ACM Transactions on Multimedia Computing, Communications, and Applications 2019_)
-->

- [Enhanced skeleton and face 3D data for person re-identification from depth cameras](https://doi.org/10.24963/ijcai.2020/125) (_Computers\&Graphics 2019_)

### **2018**
- [Cross-context analysis for long-term view-point invariant person re-identification via soft-biometrics using depth sensor](https://www.scitepress.org/papers/2018/66206/66206.pdf) (_VISIGRAPP 2018_)

### **2017**
- [Human identification from freestyle walks using posture-based gait feature](https://ieeexplore.ieee.org/abstract/document/8007293) (_IEEE Transactions on Information Forensics and Security 2017_)

- [Context-aware person re-identification in the wild via fusion of gait and anthropometric features](https://vislab.isr.tecnico.ulisboa.pt/wp-content/uploads/2017/05/anambiar_BWild2017.pdf) (_International Conference on Automatic Face \& Gesture Recognition 2017_)

### **2016**
- [Long term person re-identification from depth cameras using facial and skeleton data](https://www.researchgate.net/profile/Stefano-Berretti/publication/325161671_Long_Term_Person_Re-identification_from_Depth_Cameras_Using_Facial_and_Skeleton_Data/links/5b84ffc892851c1e1236dd11/Long-Term-Person-Re-identification-from-Depth-Cameras-Using-Facial-and-Skeleton-Data.pdf) (_ICPR 2016_)

### **2015**
- [Person Identification Using Anthropometric and Gait Data from Kinect Sensor](http://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9680) (_AAAI 2015_)

- [People re-identification using 3D descriptor with skeleton information](https://ieeexplore.ieee.org/abstract/document/7333986) (_International Conference on Informatics, Electronics \& Vision 2015_)

- [Multimodal person reidentification using RGB-D cameras](https://ieeexplore.ieee.org/abstract/document/7088601) (_IEEE Transactions on Circuits and Systems for Video Technology 2015_)

### **2014**
- [3D reconstruction of freely moving persons for re-identification with a depth sensor](https://doi.org/10.24963/ijcai.2020/125) (_ICRA 2014_)

- [A feature-based approach to people re-identification using skeleton keypoints](https://www.researchgate.net/profile/Matteo-Munaro/publication/286624461_A_feature-based_approach_To_people_re-identification_using_skeleton_keypoints/links/566ea2f008ae1a797e406d8a/A-feature-based-approach-To-people-re-identification-using-skeleton-keypoints.pdf) (_ICRA 2014_)

- [One-Shot Person Re-identification with a Consumer Depth Camera](https://doi.org/10.1007/978-1-4471-6296-4\_8) (_Person Re-Identification 2014_)

### Before 2014
- [Re-identification with RGB-D Sensors](https://doi.org/10.1007/978-3-642-33863-2\_43) (_ECCV Workshop 2012_)

 - [**Hand-Crafted Methods**](#Hand-Crafted-Methods)
	- [**Sequence Learning Methods**](#Sequence-Learning-Methods)
	- [**Graph Learning Methods**](#Graph-Learning-Methods) 

##  Leaderboards
The results are mainly from the paper of (**CVPR 2023**) [[paper](http://openaccess.thecvf.com/content/CVPR2023/papers/Rao_TranSG_Transformer-Based_Skeleton_Graph_Prototype_Contrastive_Learning_With_Structure-Trajectory_Prompted_CVPR_2023_paper.pdf)] (TranSG: Transformer-Based Skeleton Graph Prototype Contrastive Learning with Structure-Trajectory Prompted Reconstruction for Person Re-Identification). 
| **Methods**                                 | **BIWI-S** |        |        |         | **BIWI-W** |        |        |         | **KS20** |        |        |         |
|---------------------------------------------|:----------:|:------:|:------:|:-------:|:----------:|:------:|:------:|:-------:|:--------:|:------:|:------:|:-------:|
|                                             |        mAP | Rank-1 | Rank-5 | Rank-10 |        mAP | Rank-1 | Rank-5 | Rank-10 |      mAP | Rank-1 | Rank-5 | Rank-10 |
| [**Hand-Crafted Methods**](#Hand-Crafted-Methods)                    |            |        |        |         |            |        |        |         |          |        |        |         |
| ${D_{\text{PG}}}$ (Pattern Recognition 2020)                 |        6.7 |   18.5 |   45.4 |    63.8 |        8.7 |    6.5 |   15.5 |    20.3 |     11.3 |   35.2 |   61.5 |    70.5 |
| ${D_{13}}$ (Person Re-Identification 2014) |       13.1 |   28.3 |   53.1 |    65.9 |       17.2 |   14.2 |   20.6 |    23.7 |     18.9 |   39.4 |   71.7 |    81.7 |
| ${D_{16}}$ (Computers\&Graphics 2019)       |       16.7 |   32.6 |   55.7 |    68.3 |       18.8 |   17.0 |   25.3 |    29.6 |     24.0 |   51.7 |   77.1 |    86.9 |
| [**Sequence Learning Methods**](#Sequence-Learning-Methods)               |            |        |        |         |            |        |        |         |          |        |        |         |
| PoseGait (PR 2020)                          |        9.9 |   14.0 |   40.7 |    56.7 |       11.1 |    8.8 |   23.0 |    31.2 |     23.5 |   49.4 |   80.9 |    90.2 |
| AGE (IJCAI 2020)                             |        8.9 |   25.1 |   43.1 |    61.6 |       12.6 |   11.7 |   21.4 |    27.3 |      8.9 |   43.2 |   70.1 |    80.0 |
| SGELA (TPAMI 2020)                          |       15.1 |   25.8 |   51.8 |    64.4 |       19.0 |   11.7 |   14.0 |    14.7 |     21.2 |   45.0 |   65.0 |    75.1 |
| SimMC (IJCAI 2022)                          |       12.3 |   41.7 |   66.6 |    76.8 |       19.9 |   24.5 |   36.7 |    44.5 |     22.3 |   66.4 |   80.7 |    87.0 |
| Hi-MPC (IJCV 2023)                          |       17.4 |   47.5 |   70.3 |    78.6 |       22.6 |   27.3 |   40.3 |    48.8 |     22.0 |   69.6 |   83.5 |    87.1 |
| [**Graph Learning Methods**](#Graph-Learning-Methods)                   |            |        |        |         |            |        |        |         |          |        |        |         |
| MG-SCR (IJCAI 2021)                         |        7.6 |   20.1 |   46.9 |    64.1 |       11.9 |   10.8 |   20.3 |    29.4 |     10.4 |   46.3 |   75.4 |    84.0 |
| SM-SGE (ACM MM 2021)                        |       10.1 |   31.3 |   56.3 |    69.1 |       15.2 |   13.2 |   25.8 |    33.5 |      9.5 |   45.9 |   71.9 |    81.2 |
| SPC-MGR (Arxiv 2022)                        |       16.0 |   34.1 |   57.3 |    69.8 |       19.4 |   18.9 |   31.5 |    40.5 |     21.7 |   59.0 |   79.0 |    86.2 |
| TranSG (CVPR 2023)                          |       30.1 |   68.7 |   86.5 |    91.8 |       26.9 |   32.7 |   44.9 |    52.2 |     46.2 |   73.6 |   86.3 |    90.2 |



| **Methods**                                 | **IAS-A** |        |        |         | **IAS-B** |        |        |         | **KGBD** |        |        |         |
|---------------------------------------------|:---------:|:------:|:------:|:-------:|:---------:|:------:|:------:|:-------:|:--------:|:------:|:------:|:-------:|
|                                             |       mAP | Rank-1 | Rank-5 | Rank-10 |       mAP | Rank-1 | Rank-5 | Rank-10 |      mAP | Rank-1 | Rank-5 | Rank-10 |
| [**Hand-Crafted Methods**](#Hand-Crafted-Methods)                    |           |        |        |         |           |        |        |         |          |        |        |         |
| ${D_{\text{PG}}}$ (Pattern Recognition 2020)                 |      11.0 |   16.4 |   39.5 |    53.4 |      10.6 |   16.0 |   41.2 |    57.3 |      2.1 |   30.0 |   49.1 |    58.1 |
| ${D_{13}}$ (Person Re-Identification 2014) |      24.5 |   40.0 |   58.7 |    67.6 |      23.7 |   43.7 |   68.6 |    76.7 |      1.9 |   17.0 |   34.4 |    44.2 |
| ${D_{16}}$ (Computers\&Graphics 2019)       |      25.2 |   42.7 |   62.9 |    70.7 |      24.5 |   44.5 |   69.1 |    80.2 |      4.0 |   31.2 |   50.9 |    59.8 |
| [**Sequence Learning Methods**](#Sequence-Learning-Methods)              |           |        |        |         |           |        |        |         |          |        |        |         |
| PoseGait (PR 2020)                          |      17.5 |   28.4 |   55.7 |    69.2 |      20.8 |   28.9 |   51.6 |    62.9 |     13.9 |   50.6 |   67.0 |    72.6 |
| AGE(IJCAI 2020)                             |      13.4 |   31.1 |   54.8 |    67.4 |      12.8 |   31.1 |   52.3 |    64.2 |      0.9 |    2.9 |    5.6 |     7.5 |
| SGELA (TPAMI 2020)                          |      13.2 |   16.7 |   30.2 |    44.0 |      14.0 |   22.2 |   40.8 |    50.2 |      4.5 |   38.1 |   53.5 |    60.0 |
| SimMC (IJCAI 2022)                          |      18.7 |   44.8 |   65.3 |    72.9 |      22.9 |   46.3 |   68.1 |    77.0 |     11.7 |   54.9 |   66.2 |    70.6 |
| Hi-MPC (IJCV 2023)                          |      23.2 |   45.6 |   67.3 |    75.4 |      25.3 |   48.2 |   70.2 |    77.8 |     10.2 |   56.9 |   70.2 |    75.1 |
| [**Graph Learning Methods**](#Graph-Learning-Methods)                  |           |        |        |         |           |        |        |         |          |        |        |         |
| MG-SCR (IJCAI 2021)                         |      14.1 |   36.4 |   59.6 |    69.5 |      12.9 |   32.4 |   56.5 |    69.4 |      6.9 |   44.0 |   58.7 |    64.6 |
| SM-SGE (ACM MM 2021)                        |      13.6 |   34.0 |   60.5 |    71.6 |      13.3 |   38.9 |   64.1 |    75.8 |      4.4 |   38.2 |   54.2 |    60.7 |
| SPC-MGR (Arxiv 2022)                        |      24.2 |   41.9 |   66.3 |    75.6 |      24.1 |   43.3 |   68.4 |    79.4 |      6.9 |   40.8 |   57.5 |    65.0 |
| TranSG (CVPR 2023)                          |      32.8 |   49.2 |   68.5 |    76.2 |      39.4 |   59.1 |   77.0 |    87.0 |     20.2 |   59.0 |   73.1 |    78.2 |
