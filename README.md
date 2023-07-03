# ICIP2023-6D-Pose-Estimation-Supplementary-Material

This page supports the article "Modeling and Interpreting 6-D Object Pose Estimation" submitted for ICIP 2023 with the follwing:
* Iteractive version of Figure 3
* $R_x$ plot that was removed from Figure 3 because of spcae restriction
* The Pose_network results that was removed from the article
* Figure 3 colored by $cos(r1)$ and $cos(r2)$

# Abstract

This work aims to estimate the 6-Degrees of Freedom Pose of an object using simple convolutional neural networks. The problem is that most methods require previous knowledge of the 3D model of the object of interest, which could be unobtainable. We mitigate the problem by simplifying the object’s 3D model to a single and generic primitive solid to create a model that could estimate the pose of unknown objects. Besides that, we study the interpretability of the neural network by using visualization techniques to understand how the network is splitting the high-dimension feature space to reach a Pose estimation.

# Rotation Feature Plot
* Cored by Type: [type](rot_networks/moved_tetrahedron_ResNet50/type.html)
* Cored by $R_x$: [rx](rot_networks/moved_tetrahedron_ResNet50/r1.html)
* Cored by $R_z$: [rz](rot_networks/moved_tetrahedron_ResNet50/r2.html)
* Cored by $cos(R_x)$: [crx](rot_networks/moved_tetrahedron_ResNet50/cos_r1.html)
* Cored by $cos(R_z)$: [crz](rot_networks/moved_tetrahedron_ResNet50/cos_r2.html)

# Pose Feature Plot
## Feature Layer
* Cored by Object: [feature_object](pose_networks/resnet50_combined_loss/feature_layer/object.html)
* Cored by $R_x$: [feature_rx](pose_networks/resnet50_combined_loss/feature_layer/roll.html)
* Cored by $R_y$: [feature_ry](pose_networks/resnet50_combined_loss/feature_layer/pitch.html)
* Cored by $R_z$: [feature_rz](pose_networks/resnet50_combined_loss/feature_layer/yaw.html)
* Cored by $t_x$: [feature_tx](pose_networks/resnet50_combined_loss/feature_layer/tx.html)
* Cored by $t_y$: [feature_ty](pose_networks/resnet50_combined_loss/feature_layer/ty.html)
* Cored by $t_z$: [feature_tz](pose_networks/resnet50_combined_loss/feature_layer/tz.html)

## Rotation Branch Layer 1
* Cored by Object: [rot_dense1_object](pose_networks/resnet50_combined_loss/rot_dense1/object.html)
* Cored by $R_x$: [rot_dense1_rx](pose_networks/resnet50_combined_loss/rot_dense1/roll.html)
* Cored by $R_y$: [rot_dense1_ry](pose_networks/resnet50_combined_loss/rot_dense1/pitch.html)
* Cored by $R_z$: [rot_dense1_rz](pose_networks/resnet50_combined_loss/rot_dense1/yaw.html)

## Rotation Branch Layer 2
* Cored by Object: [rot_dense2_object](pose_networks/resnet50_combined_loss/rot_dense2/object.html)
* Cored by $R_x$: [rot_dense2_rx](pose_networks/resnet50_combined_loss/rot_dense2/roll.html)
* Cored by $R_y$: [rot_dense2_ry](pose_networks/resnet50_combined_loss/rot_dense2/pitch.html)
* Cored by $R_z$: [rot_dense2_rz](pose_networks/resnet50_combined_loss/rot_dense2/yaw.html)

## Translation Branch Layer 1
* Cored by Object: [t_dense1_object](pose_networks/resnet50_combined_loss/t_dense1/object.html)
* Cored by $t_x$: [t_dense1_tx](pose_networks/resnet50_combined_loss/t_dense1/tx.html)
* Cored by $t_y$: [t_dense1_ty](pose_networks/resnet50_combined_loss/t_dense1/ty.html)
* Cored by $t_z$: [t_dense1_tz](pose_networks/resnet50_combined_loss/t_dense1/tz.html)

## Translation Branch Layer 2
* Cored by Object: [t_dense2_object](pose_networks/resnet50_combined_loss/t_dense2/object.html)
* Cored by $t_x$: [t_dense2_tx](pose_networks/resnet50_combined_loss/t_dense2/tx.html)
* Cored by $t_y$: [t_dense2_ty](pose_networks/resnet50_combined_loss/t_dense2/ty.html)
* Cored by $t_z$: [t_dense2_tz](pose_networks/resnet50_combined_loss/t_dense2/tz.html)

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


# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


