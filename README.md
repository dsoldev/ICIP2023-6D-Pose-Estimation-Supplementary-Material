# ICIP2023-6D-Pose-Estimation-Supplementary-Material

This page supports the article "Modeling and Interpreting 6-D Object Pose Estimation" submitted for ICIP 2023 with the follwing:
* Iteractive version of Figure 3
* R<sub>x</sub> plot that was removed from Figure 3 because of spcae restriction
* The Pose_network results that was removed from the article
* Figure 3 colored by $cos(r1)$ and $cos(r2)$

# Abstract

This work aims to estimate the 6-Degrees of Freedom Pose of an object using simple convolutional neural networks. The problem is that most methods require previous knowledge of the 3D model of the object of interest, which could be unobtainable. We mitigate the problem by simplifying the object’s 3D model to a single and generic primitive solid to create a model that could estimate the pose of unknown objects. Besides that, we study the interpretability of the neural network by using visualization techniques to understand how the network is splitting the high-dimension feature space to reach a Pose estimation.

# Rotation Feature Plot
* Color mapped by Type: [type](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/rot_networks/moved_tetrahedron_ResNet50/type.html)
* Color mapped by R<sub>x</sub>: [rx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/rot_networks/moved_tetrahedron_ResNet50/r2.html)
* Color mapped by R<sub>z</sub>: [rz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/rot_networks/moved_tetrahedron_ResNet50/r1.html)
* Color mapped by cos(R<sub>x</sub>): [crx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/rot_networks/moved_tetrahedron_ResNet50/cos_r2.html)
* Color mapped by cos(R<sub>z</sub>): [crz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/rot_networks/moved_tetrahedron_ResNet50/cos_r1.html)

# Pose Feature Plot
## Feature Layer
* Color mapped by Object: [feature_object](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/object.html)
* Color mapped by R<sub>x</sub>: [feature_rx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/roll.html)
* Color mapped by R<sub>y</sub>: [feature_ry](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/pitch.html)
* Color mapped by R<sub>z</sub>: [feature_rz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/yaw.html)
* Color mapped by t<sub>x</sub>: [feature_tx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/tx.html)
* Color mapped by t<sub>y</sub>: [feature_ty](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/ty.html)
* Color mapped by t<sub>z</sub>: [feature_tz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/feature_layer/tz.html)

## Rotation Branch Layer 1
* Color mapped by Object: [rot_dense1_object](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense1/object.html)
* Color mapped by R<sub>x</sub>: [rot_dense1_rx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense1/roll.html)
* Color mapped by R<sub>y</sub>: [rot_dense1_ry](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense1/pitch.html)
* Color mapped by R<sub>z</sub>: [rot_dense1_rz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense1/yaw.html)

## Rotation Branch Layer 2
* Color mapped by Object: [rot_dense2_object](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense2/object.html)
* Color mapped by R<sub>x</sub>: [rot_dense2_rx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense2/roll.html)
* Color mapped by R<sub>y</sub>: [rot_dense2_ry](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense2/pitch.html)
* Color mapped by R<sub>z</sub>: [rot_dense2_rz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/rot_dense2/yaw.html)

## Translation Branch Layer 1
* Color mapped by Object: [t_dense1_object](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense1/object.html)
* Color mapped by t<sub>x</sub>: [t_dense1_tx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense1/tx.html)
* Color mapped by t<sub>y</sub>: [t_dense1_ty](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense1/ty.html)
* Color mapped by t<sub>z</sub>: [t_dense1_tz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense1/tz.html)

## Translation Branch Layer 2
* Color mapped by Object: [t_dense2_object](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense2/object.html)
* Color mapped by t<sub>x</sub>: [t_dense2_tx](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense2/tx.html)
* Color mapped by t<sub>y</sub>: [t_dense2_ty](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense2/ty.html)
* Color mapped by t<sub>z</sub>: [t_dense2_tz](https://dsoldev.github.io/ICIP2023-6D-Pose-Estimation-Supplementary-Material/pose_networks/resnet50_combined_loss/t_dense2/tz.html)

# Citation
To cite this work use the following bibtex:

```
@article{SOLER2023,
  title={Modeling and Interpreting 6-D Object Pose Estimation},
  author={},
  journal={},
  year={2023}
}
```
# Acknowledgments
This study was financed in part by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior – Brasil (CAPES) – Finance Code 001.

Acknowledges to CNPq 465446/2014-0, FAPESP 14/50937-1, 15/22308-2 and the MCTI (law 8.248, PPI-Softex - TIC 13 - 01245.010222/2022-44).


![alt text](docs/logos.jpg)

# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


