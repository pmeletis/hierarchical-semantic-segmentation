__Hierarchical Semantic Segmentation__ is a robust and customizable semantic segmentation system. It is based on dense convolutional neural networks and TensorFlow. The system is described in the following paper. If you use our work, _please refer to this paper and GitHub repository._

__Meletis P, Dubbelman G (2018)__ _Training of convolutional networks on multiple heterogeneous datasets for street scene semantic segmentation._ The 29th IEEE Intelligent Vehicles Symposiom (IV 2018), [full paper on arXiv](https://arxiv.org/abs/1803.05675).

# Introduction ###

Hierarchical Semantic Segmentation is based on ResNet50. Its main novelty compared to other semantic segmentation systems, is that a single model can handle a variety of different datasets, with disjunct sets of semantic classes. Our system also runs in real time (15fps and rising). Figures 1-3 below provide sample results, from 3 different datasets.

![Image 1.1](sample_results/1/image_1.png "Image 1.1") | ![Image 1.2](sample_results/1/image_2.png "Image 1.2") | ![Image 1.3](sample_results/1/image_3.png "Image 1.3")
----|----|----
![Predictions 1.1](sample_results/1/predictions_1.png "Predictions 1.1") | ![Predictions 1.2](sample_results/1/predictions_2.png "Predictions 1.2") | ![Predictions 1.3](sample_results/1/predictions_3.png "Predictions 1.3")
![Ground truth 1.1](sample_results/1/ground_truth_1.png "Ground truth 1.1") | ![Ground truth 1.2](sample_results/1/ground_truth_2.png "Ground truth 1.2") | ![Ground truth 1.3](sample_results/1/ground_truth_3.png "Ground truth 1.3")
__Figure 1.__ ADD CAPTION (top: input images, center: predictions, bottom: ground truth).

![Image 2.1](sample_results/2/image_1.jpg "Image 2.1") | ![Image 2.2](sample_results/2/image_2.jpg "Image 2.2") | ![Image 2.3](sample_results/2/image_3.jpg "Image 2.3")
----|----|----
![Predictions 2.1](sample_results/2/predictions_1.png "Predictions 2.1") | ![Predictions 2.2](sample_results/2/predictions_2.png "Predictions 2.2") | ![Predictions 2.3](sample_results/2/predictions_3.png "Predictions 2.3")
![Ground truth 2.1](sample_results/2/ground_truth_1.png "Ground truth 2.1") | ![Ground truth 2.2](sample_results/2/ground_truth_2.png "Ground truth 2.2") | ![Ground truth 2.3](sample_results/2/ground_truth_3.png "Ground truth 2.3")
__Figure 2.__ ADD CAPTION (top: input images, center: predictions, bottom: ground truth).

![Image 3.1](sample_results/3/image_1.png "Image 3.1") | ![Image 3.2](sample_results/3/image_2.png "Image 3.2") | ![Image 3.3](sample_results/3/image_3.png "Image 3.3")
----|----|----
![Predictions 3.1](sample_results/3/predictions_1.png "Predictions 3.1") | ![Predictions 3.2](sample_results/3/predictions_2.png "Predictions 3.2") | ![Predictions 3.3](sample_results/3/predictions_3.png "Predictions 3.3")
![Ground truth 3.1](sample_results/3/ground_truth_1.png "Ground truth 3.1") | ![Ground truth 3.2](sample_results/3/ground_truth_2.png "Ground truth 3.2") | ![Ground truth 3.3](sample_results/3/ground_truth_3.png "Ground truth 3.3")
__Figure 3.__ ADD CAPTION (top: input images, center: predictions, bottom: ground truth).

_Documentation and testing: Joris IJsselmuiden, [Track32](http://track32.nl)_
