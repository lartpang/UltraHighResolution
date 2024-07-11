# Ultra-High Resolution (UHR)

## Ultra-High Resolution Segmentation

### Datasets

* **DeepGlobe** contains 803 ultra-high resolution images (2448×2448 pixels). The dense annotation contains 7 classes of landscape regions, where one class out of seven called “unknown” region is not considered in the challenge.
    * [DeepGlobe 2018: A Challenge to Parse the Earth through Satellite Images](https://arxiv.org/abs/1805.06561), CVPRW 2018
* **ISIC** Lesion Boundary Segmentation Challenge dataset contains 2594 ultra-high resolution images. We randomly split images into training, validation and testing sets with 2074, 260, and 260 images respectively.
    * [The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions](https://arxiv.org/abs/1803.10417), Scientific Data 2018
* **UDD6/UDD5** is a collection of drone image Dataset collected at Peking University, Huludao city, Henan University and Cangzhou city.
    * [Large-Scale Structure from Motion with Semantic Constraints of Aerial Images](https://link.springer.com/chapter/10.1007/978-3-030-03398-9_30), PRCV 2018
    * [Dataset Home](https://github.com/MarcWong/UDD)
* **UAVid** consists of 30 video sequences capturing 4K high-resolution images in slanted views. In total, 300 images have been densely labeled with 8 classes for the semantic labeling task and each of size 4096 × 2160 or 3840 × 2160.
    * [UAVid: A Semantic Segmentation Dataset for UAV Imagery](https://arxiv.org/abs/1810.10438), ISPRS Journal of Photogrammetry and Remote Sensing 2020
    * [Dataset Home](https://uavid.nl/)
* **Inria Aerial** Challenge dataset contains 180 ultra high resolution images, each with 5000×5000 pixels.
    * [Can Semantic Labeling Methods Generalize to Any City? The Inria Aerial Image Labeling Benchmark](https://ieeexplore.ieee.org/document/8127684), IEEE International Geoscience and Remote Sensing Symposium (IGARSS) 2017
    * [Dataset Home](https://project.inria.fr/aerialimagelabeling/)
* **HRRSD (High Resolution Remote Sensing Detection)** contains 21,761 images acquired from Google Earth and Baidu Map with the spatial resolution from 0.15m to 1.2m. There are 55,740 object instances in HRRSD. HRRSD contains 13 categories of RSI objects. Moreover, this dataset is divided as several subsets, image numbers in each subset are 5401 for ‘train’, 5417 for ‘val’, and 10943 for ‘test’. And ‘train-val’ subset is a merge of ‘train’ and ‘val’.
    * [Hierarchical and Robust Convolutional Neural Network for Very High-Resolution Remote Sensing Object Detection](https://ieeexplore.ieee.org/document/8676107), TGRS 2019
    * [Dataset Project](https://github.com/CrazyStoneonRoad/TGRS-HRRSD-Dataset)
* **URUR (Ultra-High Resolution dataset with Ultra-Rich Context)** contains amounts of images with high enough resolution (3,008 images of size 5120×5120), a wide range of complex scenes (from 63 cities), rich-enough context (1 million instances with 8 categories) and fine-grained annotations (about 80 billion manually annotated pixels), which is far superior to all the existing UHR datasets including DeepGlobe, Inria Aerial, UDD, etc.
    * [Ultra-High Resolution Segmentation with Ultra-Rich Context: A Novel Benchmark](https://arxiv.org/abs/2305.10899), CVPR 2023
    * [Dataset Project](https://github.com/jankyee/URUR)

### Parallel Global-Local Branch

* (**GLNet**) Collaborative Global-Local Networks for Memory-Efficient Segmentation of Ultra-High Resolution Images, CVPR 2019 Oral | [ArXiv](https://arxiv.org/abs/1905.06368) | [Code](https://github.com/VITA-Group/GLNet)
* (**WSDNet**) Ultra-High Resolution Segmentation with Ultra-Rich Context: A Novel Benchmark, CVPR 2023 | [ArXiv](https://arxiv.org/abs/2305.10899)

### Progressively Multi-Scale Contexts

* (**FCtL**) From Contexts to Locality: Ultra-high Resolution Image Segmentation via Locality-aware Contextual Correlation, ICCV 2021 | [CVF](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_From_Contexts_to_Locality_Ultra-High_Resolution_Image_Segmentation_via_Locality-Aware_ICCV_2021_paper.pdf) | [Code](https://github.com/liqiokkk/FCtL)
