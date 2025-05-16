# Data release for "Symbolic and Hybrid AI for Brain Tissue Segmentation using Spatial Model Checking"

This repository contains the data of the article "Symbolic and Hybrid AI for Brain Tissue Segmentation using Spatial Model Checking" by Gina Belmonte, Vincenzo Ciancia, and Mieke Massink, accepted for publication at the international scientific journal "AI in Medicine", 2025, publisher Elsevier.

### Abstract:

Segmentation of 3D medical images, and brain segmentation in particular, is an important topic in neuroimaging and in radiotherapy.
Overcoming the current, time consuming, practise of manual delineation of brain tumours and providing an accurate, explainable,
and replicable method of segmentation of the tumour area and related tissues is therefore an open research challenge.
In this paper, we first propose a novel symbolic approach to brain segmentation and delineation of brain lesions based on spatial
model checking. This method has its foundations in the theory of closure spaces, a generalisation of topological spaces, and
spatial logics. At its core is a high-level declarative logic language for image analysis, ImgQL, and an efficient spatial model
checker, VoxLogicA, exploiting state-of-the-art image analysis libraries in its model checking algorithm. We then illustrate how
this technique can be combined with Machine Learning techniques leading to a hybrid AI approach that provides accurate and
explainable segmentation results.
We show the results of the application of the symbolic approach on several public datasets with 3D magnetic resonance (MR)
images. Three datasets are provided by the 2017, 2019 and 2020 international MICCAI BraTS Challenges with 210, 259 and 293
MR images, respectively, and the fourth is the BrainWeb dataset with 20 (synthetic) 3D patient images of the normal brain. We then
apply the hybrid AI method to the BraTS 2020 training set. Our segmentation results are shown to be in line with the state-of-the-art
with respect to other recent approaches, both from the accuracy point of view as well as from the view of computational efficiency,
but with the advantage of them being explainable.

# Description of data

### Data for BraTS 2020 (Table 4 of the article):

[full_stats_for_fixed_thresholds.csv](full_stats_for_fixed_thresholds.csv)

### Data for BrainWeb case study (Table 5 of the article):

[brainweb-grey-white.csv](brainweb-grey-white.csv)

### Data for the hybrid case study (Table 6 of the article):

Results:

- [full_stats_for_found_thresholds.csv](full_stats_for_found_thresholds.csv)
- [full_stats_for_optimal_thresholds.csv](full_stats_for_optimal_thresholds.csv)
- [nnUnet_results_2025.csv](nnUnet_results_2025.csv)

### Auxiliary files:

Name mapping BraTS 2020 dataset:

- [BRATS2020_name_mapping.csv](BRATS2020_name_mapping.csv)

Files that were discarded in the referenced TACAS19 publication:

- [discarded_tacas19.csv](discarded_tacas19.csv)

Files used in TACAS19 to manually create the logical specification:

- [manual_calibration_IMGQL_SPEC-BraTS17.csv](manual_calibration_IMGQL_SPEC-BraTS17.csv)

Fifty images used for training nnUNet:

- [50images-nnUNet-Training.csv](50images-nnUNet-Training.csv)
