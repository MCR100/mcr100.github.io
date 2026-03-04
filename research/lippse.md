---
layout: project
title: LiPPSe
permalink: /research/lippse/

project_short_title: "LiPPSe: LiDAR based Probe Pose Seeding for Teleoperated Echocardiography"
paper_title: "Finding an Initial Probe Pose in Teleoperated Robotic Echocardiography via 2D LiDAR Based 3D Reconstruction"
venue: "ICRA (accepted)"

authors: "Mariadas Capsran Roshan, Edgar M Hidalgo, Mats Isakssson, Michelle Dunn, Jagannatha Charjee Pyaraka"

paper_url: "https://arxiv.org/abs/2509.24867"
code_url: "https://github.com/MCR100/LiPPSe-ICRA2026"
video_url: "https://github.com/MCR100/LiPPSe-ICRA2026/blob/main/assets/LiPPSe-demo.mp4"
video_mp4: "https://raw.githubusercontent.com/MCR100/LiPPSe-ICRA2026/main/assets/LiPPSe-demo.mp4"


abstract: "Echocardiography is a key imaging modality for cardiac assessment but remains highly operator-dependent, and access to trained sonographers is limited in underserved settings. Teleoperated robotic echocardiography has been proposed as a solution; however, clinical studies report longer examination times than manual procedures, increasing diagnostic delays and operator workload. Automating non-expert tasks, such as automatically moving the probe to an ideal starting pose, offers a pathway to reduce this burden. Prior vision- and depth-based approaches to estimate an initial probe pose are sensitive to lighting, texture, and anatomical variability. We propose a robot-mounted 2D LiDAR-based approach that reconstructs the chest surface in 3D and estimates the initial probe pose automatically. To the best of our knowledge, this is the first demonstration of robot-mounted 2D LiDAR used for 3D reconstruction of a human body surface. Through plane-based extrinsic calibration, the transformation between the LiDAR and robot base frames was estimated with an overall root mean square (RMS) residual of 1.8 mm and rotational uncertainty below 0.2°. The chest front surface, reconstructed from two linear LiDAR sweeps, was aligned with non-rigid templates to identify an initial probe pose. A mannequin-based study assessing reconstruction accuracy showed mean surface errors of 2.78 +/- 0.21 mm. Human trials (N=5) evaluating the proposed approach found probe initial points typically 20-30 mm from the clinically defined initial point, while the variation across repeated trials on the same subject was less than 4 mm."

bibtex: |
  @article{roshan2025finding,
  title={Finding an Initial Probe Pose in Teleoperated Robotic Echocardiography via 2D LiDAR-Based 3D Reconstruction},
  author={Roshan, Mariadas Capsran and Hidalgo, Edgar M and Isaksson, Mats and Dunn, Michelle and Pyaraka, Jagannatha Charjee},
  journal={ICRA},
  year={2025}
}
---