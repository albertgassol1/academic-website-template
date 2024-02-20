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

This work has been submitted to a top-tier computer vision conference. Code will be released soon.

<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<!-- <a href="https://github.com/albertgassol1/vf_nerf" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a> -->
<a href="{{ site.url }}{{ site.baseurl }}/papers/vf_nerf_pre_print.pdf" target="_blank"><button class="btn btn-danger btn-sm">PRE-PRINT</button></a> 
<a href="{{ site.url }}{{ site.baseurl }}/papers/master_thesis.pdf" target="_blank"><button class="btn btn-success btn-sm">THESIS</button></a> 
</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">



<h4>Coat-MPC: Performance-driven Constrained Optimal Auto-Tuner for MPC</h4>

<p align="center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/coat_mpc.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/safeopt_original.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/ucb.png" width="170" />
  <img src="{{ site.url }}{{ site.baseurl }}/images/wml.png" width="170" />
</p>

One of the significant challenges in Model Predic-
tive Control (MPC) is the safe tuning of its cost function param-
eters. In safe tuning for MPC, the goal is to find the cost func-
tion parameters that maximize the system’s performance while
ensuring that the performance stays consistently above a given
threshold. In this context, we propose the Constrained Optimal
Auto-Tuner for MPC algorithm (COAT-MPC), a method that
safely explores the cost function parameters domain to reach the
most performant parameters. COAT-MPC makes use of Upper
Confidence Bounds (UCB) on the entire parameters’ domain
as the goal for each optimization iteration, and sequentially
explores the parameter space towards this goal. We present
an in-depth theoretical analysis of our proposed method,
establishing its safety with high probability and demonstrating
provable finite-time convergence. We perform comprehensive
simulations and comparative analyses with a hardware platform
against classical Bayesian Optimization (BO) and state-of-the-
art methods. With these experiments, we demonstrate that our
approach outperforms these competitive baselines in terms of
fewer constraint violations and improved cumulative regret over
time in the autonomous racing scenario. 

Work in progress to be submitted at a top-tier robotics conference.

<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<a href="{{ site.url }}{{ site.baseurl }}/papers/coat_mpc_pre_print.pdf" target="_blank"><button class="btn btn-danger btn-sm">PRE-PRINT</button></a> 
<a href="https://github.com/albertgassol1/coat_mpc" target="_blank"><button class="btn btn-info btn-sm">GITHUB</button></a>
<a href="{{ site.url }}{{ site.baseurl }}/papers/semester_project.pdf" target="_blank"><button class="btn btn-success btn-sm">THESIS</button></a> 

<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/vf_nerf_pre_print.pdf" target="_blank"><button class="btn btn-danger btn-sm">PRE-PRINT</button></a>  -->

</div>
</div>
