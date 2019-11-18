---
ID: 620
post_title: >
  RGBD temporal resampling for real-time
  occlusion removal
author: gicomadmin
post_excerpt: >
  Occlusions disrupt the visualization of
  an object of interest, or target, in a
  real world scene. Video inpainting
  removes occlusions from a video stream
  by cutting out occluders and filling in
  with a plausible visualization of the
  object, but the approach is too slow for
  real-time performance. In this paper, we
  present a method for realtime occlusion
  removal in the visualization of a real
  world scene that is captured with an
  RGBD stream. Our pipeline segments the
  current RGBD frame to find the target
  and the occluders, searches for the best
  matching disoccluded view of the target
  in an earlier frame, computes a mapping
  between the target in the current frame
  and the target in the best matching
  frame, inpaints the missing pixels of
  the target in the current frame by
  resampling from the earlier frame, and
  visualizes the disoccluded target in the
  current frame. We demonstrate our method
  in the case of a walking human occluded
  by stationary or walking humans. Our
  method does not rely on a known 2D or 3D
  model of the target or of the occluders,
  and therefore it generalizes to other
  shapes. Our method runs at an
  interactive frame rate of 30fps.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/rgbd-temporal-resampling-for-real-time-occlusion-removal/
published: true
post_date: 2019-11-18 14:36:46
---
<!-- wp:paragraph -->

Interactive 3D Graphics and Games / Projections

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Occlusions disrupt the visualization of an object of interest, or target, in a real world scene. Video inpainting removes occlusions from a video stream by cutting out occluders and filling in with a plausible visualization of the object, but the approach is too slow for real-time performance. In this paper, we present a method for realtime occlusion removal in the visualization of a real world scene that is captured with an RGBD stream. Our pipeline segments the current RGBD frame to find the target and the occluders, searches for the best matching disoccluded view of the target in an earlier frame, computes a mapping between the target in the current frame and the target in the best matching frame, inpaints the missing pixels of the target in the current frame by resampling from the earlier frame, and visualizes the disoccluded target in the current frame. We demonstrate our method in the case of a walking human occluded by stationary or walking humans. Our method does not rely on a known 2D or 3D model of the target or of the occluders, and therefore it generalizes to other shapes. Our method runs at an interactive frame rate of 30fps.

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:E393N5IN}" style="apa" showimage="yes" download="yes" notes="yes" cite="yes" title="yes" abstract="no"] 

<!-- /wp:shortcode -->