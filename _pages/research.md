---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Performance-driven Constrained Optimal Auto-Tuner for MPC</h4>

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/coat_mpc.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/safeopt_original.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/ucb.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/wml.png" width="170" />
</p>

A key challenge in tuning Model Predictive Control (MPC) cost function parameters is to ensure that the system performance stays consistently above a certain threshold. To address this challenge, we propose a novel method, COAT-MPC, Constrained Optimal Auto-Tuner for MPC. With every tuning iteration, COAT-MPC gathers performance data and learns by updating its posterior belief. It explores the tuning parameters' domain towards optimistic parameters in a goal-directed fashion, which is key to its sample efficiency. We theoretically analyze COAT-MPC, showing that it satisfies performance constraints with arbitrarily high probability at all times and provably converges to the optimum performance within finite time. Through comprehensive simulations and comparative analyses with a hardware platform, we demonstrate the effectiveness of COAT-MPC in comparison to classical Bayesian Optimization (BO) and other state-of-the-art methods. When applied to autonomous racing, our approach outperforms baselines in terms of constraint violations and cumulative regret over time.

<a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a>
<a href="https://ieeexplore.ieee.org/document/10924398" target="_blank"><button class="btn btn-primary btn-sm">IEEE</button></a>
<a href="https://arxiv.org/abs/2503.07127" target="_blank"><button class="btn btn-danger btn-sm">ARXIV</button></a> 
<a href="https://github.com/albertgassol1/coat_mpc" target="_blank"><button class="btn btn-info btn-sm">GITHUB</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/semester_project.pdf" target="_blank"><button class="btn btn-success btn-sm">THESIS</button></a> 



</div>
</div>


<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>VF-NeRF: Learning Neural Vector Fields for Indoor Scene Reconstruction</h4>

<img src="{{ site.url }}{{ site.baseurl }}/images/vf_nerf.png" width="100%" style="max-width:1000px"/>


Implicit surfaces via neural radiance fields (NeRF) have
shown surprising accuracy in surface reconstruction. De-
spite their success in reconstructing richly textured sur-
faces, existing methods struggle with planar regions with
weak textures, which account for the majority of indoor sur-
faces. We propose to solve indoor dense surface
reconstruction by replacing traditional implicit representa-
tions such as the signed distance field (SDF) or surface den-
sity with the recently proposed vector field (VF). VF is de-
fined by the unit vector directed to the nearest surface point.
It therefore flips direction at the surface, and equals the ex-
plicit surface normals. Except for this flip or sign change
around planar surfaces, VF remains constant and provides
a strong inductive bias towards planar surfaces. We develop
a novel density-VF relationship and a training scheme that
allows us to learn VF via volume rendering. By doing this,
VF-NeRF can model large planar surfaces without addi-
tional cues such as segmentations, depth or normals. Addi-
tionally, we show that, when depth cues are available, our
method further improves and achieves state-of-the-art re-
sults in reconstructing indoor scenes.

<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<!-- <a href="https://github.com/albertgassol1/vf_nerf" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a> -->
<a href="https://www.arxiv.org/abs/2408.08766" target="_blank"><button class="btn btn-danger btn-sm">ARXIV</button></a> 
<a href="https://github.com/albertgassol1/vf-nerf" target="_blank"><button class="btn btn-info btn-sm">GITHUB</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/master_thesis.pdf" target="_blank"><button class="btn btn-success btn-sm">THESIS</button></a> 
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<h4>Augmented Reality without Borders: Achieving Precise Localization Without Maps</h4>

<img src="{{ site.url }}{{ site.baseurl }}/images/marloc.png" width="100%" style="max-width:1000px"/>


Visual localization is crucial for Computer Vision and Augmented Reality (AR) applications, where determining the camera or device’s position and orientation is essential to accurately interact with the physical environment. Traditional methods rely on detailed 3D maps constructed using Structure from Motion (SfM) or Simultaneous Localization and Mapping (SLAM), which is computationally expensive and impractical for dynamic or large-scale environments. We introduce MARLoc, a novel localization framework for AR applications that uses known relative transformations within image sequences to perform intra-sequence triangulation, generating 3D-2D correspondences for pose estimation and refinement. MARLoc eliminates the need for pre-built SfM maps, providing accurate and efficient localization suitable for dynamic outdoor environments. Evaluation with benchmark datasets and real-world experiments demonstrates MARLoc’s state-of-the-art performance and robustness. By integrating MARLoc into an AR device, we highlight its capability to achieve precise localization in real-world outdoor scenarios, showcasing its practical effectiveness and potential to enhance visual localization in AR applications.

<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<a href="https://arxiv.org/abs/2408.17373" target="_blank"><button class="btn btn-danger btn-sm">PARXIV</button></a> 

<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/vf_nerf_pre_print.pdf" target="_blank"><button class="btn btn-danger btn-sm">PRE-PRINT</button></a>  -->

</div>
</div>
