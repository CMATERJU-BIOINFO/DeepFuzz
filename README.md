# DeepFuzz

In this repository, we've implemented the code resulting in the submitted paper "Deep-Fuzz: A synergistic integration of deep learning and
fuzzy water flows for fine-grained nuclei segmentation in digital pathology." in Plos One, by Nirmal Das, Satadal Saha, Mita Nasipuri, Subhadip Basu, Tapabrata Chakraborti. The Deep-Fuzz code repository conssist of two different module: 1) a U-Net based deep learning module  and 2) Qt C++ based fuzz module.

## **Description:**
The work is focused on segmentation of overlapping nuclei from microscopic images. In the first phase we used U-net based deep learning module with ASPP block in the bottleneck for initial coarse segmentation. In the second phase, we used a novel fuzzy waterflow algorithm for instance level segmentation of the overlapping nuclei.

## **How to use the code:**
1) For the deep module, we have adopted the code at: [https://github.com/nauyan/Segmentation](https://github.com/nauyan/Segmentation) with hyper parameters tuning. The installation gudie can also be found at the given site. The installation gudie is given at the site and the required libraries can be found [here](https://github.com/nauyan/Segmentation/blob/master/requirements.txt).\
2) To run the fuzzy waterflow module you need to install [QT](https://www.qt.io/download). The code is written in C++.

## **Dataset:**
We used four public datasets: [NuCLS](https://sites.google.com/view/nucls/single-rater?authuser=0), [MoNuSeg](https://monuseg.grand-challenge.org/Data/), [TNBC](https://zenodo.org/record/1175282#.YMisCTZKgow), and [S-BSST265](https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BSST265).
