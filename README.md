# DeepFuzz

In this repository, we've implemented the code resulting in the submitted paper "Deep-Fuzz: A synergistic integration of deep learning and
fuzzy water flows for fine-grained nuclei segmentation in digital pathology." in Plos One, by Nirmal Das, Satadal Saha, Mita Nasipuri, Subhadip Basu, Tapabrata Chakraborti. The Deep-Fuzz code repository conssist of two different module: 1) a U-Net based deep learning module  and 2) Qt C++ based fuzz module.

## **Description:**
We tackle the task of nuclei segmentation within histopathology tissue. Many methods have been proposed in the past but relatively few of them try to handle the wide hetereogenity that one can typically encounter with such data. As is the current trend, we apply state of the art algorithm technics based on CNN but also our novel nuclei segmentation framework. We compare each method with two metrics, the first pixel based and the second objected based. We elaborate a benchmark of fully convolutionnal algorithm applied to these datasets. In particular we compare ourselves to [Neeraj et al] and show that our deep regression method outperforms previous state of the art method for separating cluttered objects.
