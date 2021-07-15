---
title: "3D Object Shape Reconstruction from RGB images"
collection: talks
type: "Research Assistant"
permalink: /talks/pointcloud
venue: "<br/> Mentor: &emsp; Yaoqing Yang, UC Berkeley; <br/> Supervisor: &emsp;Prof. Luxi Yang, Information Science and Engineering Lab,  Southeast University"
date: 2019-09-05
location: "Nanjing, China"
---

Recent works have shown that deep neural networks tend to perform recognition instead of 3D reconstruction. In this work, we show that the bias towards recognition is due to the intrinstic properties of dataset: when the training set of 3D shapes has a more clustered structure, the deep neural networks trained on this dataset become more likely to perform recognition than reconstruction.
* Leveraged NumPy and PyTorch in Python to build a deep neural network model for 3D object shape (represented by point cloud) reconstruction from a single RGB image; trained the model on ShapeNet.
* Proposed and proved the correlation between clustering tendency of training dataset and performance bias of neural network.
* Leveraged Shrink Wrap modifier and OpenGL renderer in Blender to build an interpolation-based 3D model synthetic dataset.
* Defined a metric to measure the clustering tendency of 3D model dataset based on silhouette score and affinity propagation.
  
  
<!--[[PDF]](http://YefanZhou.github.io/files/reconstruction_or_recognition_justifying_single_view_3d_reconstruction_networks.pdf)-->
  
  
  
  
  
<p float="left">
<img src="http://YefanZhou.github.io/images/eccv_2020_matrix_vis.png" width="350" height="2000" class="center"/>
<img src="http://YefanZhou.github.io/images/eccv_2020_pointcloud_vis.png" width="350" height="2000" class="center"/> 
</p>