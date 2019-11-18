---
ID: 601
post_title: >
  High-quality object-space dynamic
  ambient occlusion for characters using
  Bi-level regression
author: gicomadmin
post_excerpt: >
  The widely used ambient occlusion (AO)
  technique provides an approximation of
  some global illumination effects and is
  efficient enough for use in real-time
  applications. Because it relies on
  computing the visibility from each point
  on a surface, AO computation is
  expensive for dynamically deforming
  objects, such as characters in
  particular. In this paper, we describe
  an algorithm for producing high-quality
  dynamically changing AO for characters.
  Our fundamental idea is to factorize the
  AO computation into a coarse-scale
  component in which visibility is
  determined by approximating spheres, and
  a fine-scale component that leverages a
  skinning-like algorithm for efficiency,
  with both components trained in a
  regression against ground-truth AO
  values. The resulting algorithm
  accommodates interactions with external
  objects and generalizes without
  requiring carefully constructed training
  data. Extensive comparisons illustrate
  the capabilities and advantages of our
  algorithm.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/high-quality-object-space-dynamic-ambient-occlusion-for-characters-using-bi-level-regression/
published: true
post_date: 2019-11-18 14:08:49
---
<!-- wp:paragraph -->

Interactive 3D Graphics and Games / SESSION: Global illumination

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

The widely used ambient occlusion (AO) technique provides an approximation of some global illumination effects and is efficient enough for use in real-time applications. Because it relies on computing the visibility from each point on a surface, AO computation is expensive for dynamically deforming objects, such as characters in particular. In this paper, we describe an algorithm for producing high-quality dynamically changing AO for characters. Our fundamental idea is to factorize the AO computation into a coarse-scale component in which visibility is determined by approximating spheres, and a fine-scale component that leverages a skinning-like algorithm for efficiency, with both components trained in a regression against ground-truth AO values. The resulting algorithm accommodates interactions with external objects and generalizes without requiring carefully constructed training data. Extensive comparisons illustrate the capabilities and advantages of our algorithm.

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:8HNAUBUF}" style="apa" showimage="yes" download="yes" abstract="no" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->