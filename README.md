# S3-MonoDETR

Official implementation of the paper 'S^3-MonoDETR: Supervised Shape&Scale-constrained Deformable Transformer for Monocular 3D Object Detection'.

                                                  😄We will release code and checkpoints in the future.

![image](https://github.com/mikasa3lili/S3-MonoDETR/blob/main/intro-m1.png)

Abstract

Recently, transformer-based methods have shown exceptional performance in monocular 3D object detection, which can predict 3D attributes from a single 2D image. These methods typically use visual and depth representations to identify query points on objects, which significantly affect the accuracy of detection. However, current unsupervised attention mechanisms without any geometry appearance awareness in transformers are susceptible to producing noisy features for query points, which limits the detection performance and also makes the model have a poor ability to detect multi-category objects in a single training process. To tackle this problem, this paper proposes a novel "Supervised Shape&Scale-constrained Deformable Attention" (S^3-DA) module for monocular 3D DETR. Specifically, S^3-DA presets several masks with different shapes and scales, then utilizes depth and visual features to generate diverse local features with corresponding matching distribution for the imposing of shape&scale constraint for each query. Benefiting from this, S^3-DA could well predict the accurate receptive fields of any category of object queries to support their robust query features generation. Besides, we propose a Multi-classification-based Shape&Scale Matching (MSM) loss to supervise the above process. Extensive experiments on the KITTI benchmark demonstrate that S^3-DA significantly improves the detection accuracy, yielding state-of-the-art performance of single-category and multi-category 3D object detection in a single training process, as compared to the existing approaches.
