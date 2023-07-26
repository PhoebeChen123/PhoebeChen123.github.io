---
title: "Self-Constrained Inference Optimization on Structural Groups for Human Pose Estimation"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Human Pose Estimation, Self-Constrained, Structural Inference, Prediction Optimization'
date: 2022-07
venue: 'Journal 1'
paperurl: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136650718.pdf'
citation: 'Kan Z, Chen S, Li Z, et al. Self-Constrained Inference Optimization on Structural Groups for Human Pose Estimation[C]//European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2022: 729-745.'
---
We observe that human poses exhibit strong group-wise structural correlation and spatial coupling between keypoints due to the biological constraints of different body parts. This group-wise structural correlation can be explored to improve the accuracy and robustness of human pose estimation. In this work, we develop a self-constrained prediction-verification network to characterize and learn the structural correlation between keypoints during training. During the inference stage, the feedback information from the verification network allows us to perform further optimization of pose prediction, which significantly improves the performance of human pose estimation. Specifically, we partition the keypoints into groups according to the biological structure of human body. Within each group, the keypoints are further partitioned into two subsets, high-accuracy proximal keypoints and low-accuracy distal keypoints. We develop a self-constrained prediction-verification network to perform forward and backward predictions between these keypoint subsets. One fundamental challenge in pose estimation, as well as in generic prediction tasks, is that there is no mechanism for us to verify if the obtained pose estimation or prediction results are accurate or not, since the ground truth is not available. Once successfully learned, the verification network serves as an accuracy verification module for the forward pose prediction. During the inference stage, it can be used to guide the local optimization of the pose estimation results of low-accuracy keypoints with the self-constrained loss on high-accuracy keypoints as the objective function. Our extensive experimental results on benchmark MS COCO and CrowdPose datasets demonstrate that the proposed method can significantly improve the pose estimation results.

Keywords: Human Pose Estimation, Self-Constrained, Structural Inference, Prediction Optimization.

[Download paper here](http://academicpages.github.io/files/pose_eccv_2022.pdf)

Recommended citation: Kan Z, Chen S, Li Z, et al. Self-Constrained Inference Optimization on Structural Groups for Human Pose Estimation[C]//European Conference on Computer Vision. Cham: Springer Nature Switzerland, 2022: 729-745.
