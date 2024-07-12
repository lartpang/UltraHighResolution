# Ultra-High Resolution (UHR)

## Ultra-High Resolution Segmentation

### Datasets

* **Cityscapes** contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5000 frames in addition to a larger set of 20000 weakly annotated frames.
    * [The cityscapes dataset for semantic urban scene understanding](https://arxiv.org/abs/1604.01685), CVPR 2016
    * [Dataset Home](https://www.cityscapes-dataset.com/)
* **Inria Aerial** Challenge dataset contains 180 ultra high resolution images, each with 5000×5000 pixels.
    * [Can Semantic Labeling Methods Generalize to Any City? The Inria Aerial Image Labeling Benchmark](https://ieeexplore.ieee.org/document/8127684), IEEE International Geoscience and Remote Sensing Symposium (IGARSS) 2017
    * [Dataset Home](https://project.inria.fr/aerialimagelabeling/)
* **DeepGlobe** contains 803 ultra-high resolution images (2448×2448 pixels). The dense annotation contains 7 classes of landscape regions, where one class out of seven called “unknown” region is not considered in the challenge.
    * [DeepGlobe 2018: A Challenge to Parse the Earth through Satellite Images](https://arxiv.org/abs/1805.06561), CVPRW 2018
* **ISIC** Lesion Boundary Segmentation Challenge dataset contains 2594 ultra-high resolution images. We randomly split images into training, validation and testing sets with 2074, 260, and 260 images respectively.
    * [The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions](https://arxiv.org/abs/1803.10417), Scientific Data 2018
* **UDD6/UDD5** is a collection of drone image Dataset collected at Peking University, Huludao city, Henan University and Cangzhou city.
    * [Large-Scale Structure from Motion with Semantic Constraints of Aerial Images](https://link.springer.com/chapter/10.1007/978-3-030-03398-9_30), PRCV 2018
    * [Dataset Home](https://github.com/MarcWong/UDD)
* **Gleason** is a medical image dataset with the resolution of 5120×5120 and contains 244 H\&E-stained histopathology images for automatic Gleason grading of prostate cancer.
    * [Deep learning-based gleason grading of prostate cancer from histopathology images—role of multiscale decision aggregation and data augmentation](https://ieeexplore.ieee.org/document/8853320), JBHI 2019
* **UAVid** consists of 30 video sequences capturing 4K high-resolution images in slanted views. In total, 300 images have been densely labeled with 8 classes for the semantic labeling task and each of size 4096 × 2160 or 3840 × 2160.
    * [UAVid: A Semantic Segmentation Dataset for UAV Imagery](https://arxiv.org/abs/1810.10438), ISPRS Journal of Photogrammetry and Remote Sensing 2020
    * [Dataset Home](https://uavid.nl/)
* **HRRSD (High Resolution Remote Sensing Detection)** contains 21,761 images acquired from Google Earth and Baidu Map with the spatial resolution from 0.15m to 1.2m. There are 55,740 object instances in HRRSD. HRRSD contains 13 categories of RSI objects. Moreover, this dataset is divided as several subsets, image numbers in each subset are 5401 for ‘train’, 5417 for ‘val’, and 10943 for ‘test’. And ‘train-val’ subset is a merge of ‘train’ and ‘val’.
    * [Hierarchical and Robust Convolutional Neural Network for Very High-Resolution Remote Sensing Object Detection](https://ieeexplore.ieee.org/document/8676107), TGRS 2019
    * [Dataset Home](https://github.com/CrazyStoneonRoad/TGRS-HRRSD-Dataset)
* **BIG** is a high-resolution semantic segmentation dataset with 50 validation and 100 test objects. Image resolution in BIG ranges from 2048×1600 to 5000×3600. Every image in the dataset has been carefully labeled by a professional while keeping the same guidelines as PASCAL VOC 2012 without the void region.
    * [Cascadepsp: Toward class335 agnostic and very high-resolution segmentation via global and local refinement](https://arxiv.org/abs/2005.02551), CVPR 2020
    * [Dataset Home](https://github.com/hkchengrex/CascadePSP/blob/master/docs/dataset.md)
* **GID (Gaofen Image Dataset)** consists of two parts: a large-scale classification set and a fine land-cover classification set. The large-scale classification set contains 150 pixel-level annotated GF-2 images, and the fine classification set is composed of 30,000 multi-scale image patches coupled with 10 pixel-level annotated GF-2 images. The training and validation data with 15 categories is collected and re-labeled based on the training and validation images with 5 categories, respectively.
    * [Land-Cover Classification with High-Resolution Remote Sensing Images Using Transferable Deep Models](https://arxiv.org/abs/1807.05713), Remote Sensing of Environment 2020
    * [Dataset Home](https://x-ytong.github.io/project/GID.html)
* **Five-Billion-Pixels/FBP**, a dataset extended on **GID**, has a spatial resolution of 4 m, covers areas more than 50,000 square kilometers in China, and contains more than 5 billion labeled pixels of 150 high-resolution Gaofen-2 (4 m) satellite images, annotated in a 24-category system covering artificial-constructed, agricultural, and natural classes.
    * [Enabling Country-Scale Land Cover Mapping with Meter-Resolution Satellite Imagery](https://www.sciencedirect.com/science/article/pii/S0924271622003264), ISPRS Journal of Photogrammetry and Remote Sensing 2023
* **URUR (Ultra-High Resolution dataset with Ultra-Rich Context)** contains amounts of images with high enough resolution (3,008 images of size 5120×5120), a wide range of complex scenes (from 63 cities), rich-enough context (1 million instances with 8 categories) and fine-grained annotations (about 80 billion manually annotated pixels), which is far superior to all the existing UHR datasets including DeepGlobe, Inria Aerial, UDD, etc.
    * [Ultra-High Resolution Segmentation with Ultra-Rich Context: A Novel Benchmark](https://arxiv.org/abs/2305.10899), CVPR 2023
    * [Dataset Home](https://github.com/jankyee/URUR)

### Parallel Global-Local Branch

* (**GLNet**) Collaborative Global-Local Networks for Memory-Efficient Segmentation of Ultra-High Resolution Images, CVPR 2019 Oral | [ArXiv](https://arxiv.org/abs/1905.06368) | [Code](https://github.com/VITA-Group/GLNet)
* (**GRNet/PPN**) Patch Proposal Network for Fast Semantic Segmentation of High-Resolution Images, AAAI 2020 | [AAAI](https://cdn.aaai.org/ojs/6926/6926-13-10155-1-10-20200525.pdf)
* (**WSDNet**) Ultra-High Resolution Segmentation with Ultra-Rich Context: A Novel Benchmark, CVPR 2023 | [ArXiv](https://arxiv.org/abs/2305.10899)
* (**GeoAgent**) Seeing Beyond the Patch: Scale-Adaptive Semantic Segmentation of High-resolution Remote Sensing Imagery based on Reinforcement Learning, ArXiv 2309 | [ArXiv](https://arxiv.org/abs/2309.15372)
* (**GPWFormer**) Guided patch-grouping wavelet transformer with spa366 tial congruence for ultra-high resolution segmentation, IJCAI 2023 | [ArXiv](https://arxiv.org/abs/2307.00711)

### Progressively Multi-Scale Contexts

* (**CascadePSP**) Cascadepsp: Toward class-agnostic and very high-resolution segmentation via global and local refinement, CVPR 2020 | [ArXiv](https://arxiv.org/abs/2005.02551) | [Code](https://github.com/hkchengrex/CascadePSP)
* (**FCtL**) From Contexts to Locality: Ultra-high Resolution Image Segmentation via Locality-aware Contextual Correlation, ICCV 2021 | [ArXiv](https://arxiv.org/pdf/2109.02580v3), [CVF](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_From_Contexts_to_Locality_Ultra-High_Resolution_Image_Segmentation_via_Locality-Aware_ICCV_2021_paper.pdf) | [Code](https://github.com/liqiokkk/FCtL)
* (**MagNet**) Progressive Semantic Segmentation, CVPR 2021 | [ArXiv](https://arxiv.org/abs/2104.03778) | [Code](https://github.com/VinAIResearch/MagNet)
* (**ISDNet**) ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation, CVPR 2022 | [CVF](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_ISDNet_Integrating_Shallow_and_Deep_Networks_for_Efficient_Ultra-High_Resolution_CVPR_2022_paper.pdf) | [Code](https://github.com/cedricgsh/ISDNet)
* (**EHSNet/ElegantSeg**) EHSNet: End-to-End Holistic Learning Network for Large-Size Remote Sensing Image Semantic Segmentation, ArXiv 2211 | [ArXiv](https://arxiv.org/abs/2211.11316)
