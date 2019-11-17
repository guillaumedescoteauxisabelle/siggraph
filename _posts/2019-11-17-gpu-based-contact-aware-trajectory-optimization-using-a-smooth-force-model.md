---
ID: 332
post_title: >
  GPU-based contact-aware trajectory
  optimization using a smooth force model
author: gicomadmin
post_excerpt: >
  We present a new formulation of
  trajectory optimization for articulated
  bodies. Our approach uses a fully
  differentiable dynamic model of the
  articulated body, and a smooth force
  model that approximates all kinds of
  internal/external forces as a smooth
  function of the articulated body’s
  kinematic state. Our formulation is
  contact-aware and its complexity is not
  dependent on the contact positions or
  the number of contacts. Furthermore, we
  exploit the block-tridiagonal structure
  of the Hessian matrix and present a
  highly parallel Newton-type trajectory
  optimizer that maps well to GPU
  architectures. Moreover, we use a
  Markovian regularization term to
  overcome the local minima problems in
  the optimization formulation. We
  highlight the performance of our
  approach using a set of locomotion tasks
  performed by characters with 15 − 35
  DOFs. In practice, our GPU-based
  algorithm running on a NVIDIA TITAN-X
  GPU provides more than 30× speedup over
  a multi-core CPU-based implementation
  running on Intel Xeon E5-1620 CPU. In
  addition, we demonstrate applications of
  our method on various applications such
  as contact-rich motion planning,
  receding-horizon control, and motion
  graph construction.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/17/gpu-based-contact-aware-trajectory-optimization-using-a-smooth-force-model/
published: true
post_date: 2019-11-17 01:17:43
---
<!-- wp:paragraph -->

trajectory optimization, articulated bodies, deformable bodies, position-based dynamics

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:AYXN65YG}" style="apa" showimage="yes" download="yes" abstract="yes" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->