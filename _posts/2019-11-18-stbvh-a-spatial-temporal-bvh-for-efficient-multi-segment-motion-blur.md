---
ID: 632
post_title: 'STBVH: a spatial-temporal BVH for efficient multi-segment motion blur'
author: gicomadmin
post_excerpt: >
  We present the STBVH, a new approach for
  rendering multi-segment motion blur
  using a bounding volume hierarchy (BVH)
  that stores both spatial linearly
  interpolated bounds and temporal bounds.
  The approach is designed for different
  number of time steps per mesh or object.
  While separating the individual meshes
  using standard partitioning techniques,
  it performs temporal splits for
  locations with large or curved motion
  inside the meshes. Our approach uses a
  modified motion blur surface area
  heuristic (MBSAH) that calculates
  probabilities in the presence of
  spatial-temporal bounds and works on
  linear motion segments of primitives
  rather than on full motion curves. We
  show that our approach is able to handle
  challenging scenes with varying degrees
  of motion blur per mesh, using
  significantly less memory and having
  competitive rendering performance
  compared to building separate linear
  motion blur BVHs per global time
  segment.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/stbvh-a-spatial-temporal-bvh-for-efficient-multi-segment-motion-blur/
published: true
post_date: 2019-11-18 15:25:06
---
<!-- wp:paragraph -->

We present the STBVH, a new approach for rendering multi-segment motion blur using a bounding volume hierarchy (BVH) that stores both spatial linearly interpolated bounds and temporal bounds. The approach is designed for different number of time steps per mesh or object. While separating the individual meshes using standard partitioning techniques, it performs temporal splits for locations with large or curved motion inside the meshes. Our approach uses a modified motion blur surface area heuristic (MBSAH) that calculates probabilities in the presence of spatial-temporal bounds and works on linear motion segments of primitives rather than on full motion curves. We show that our approach is able to handle challenging scenes with varying degrees of motion blur per mesh, using significantly less memory and having competitive rendering performance compared to building separate linear motion blur BVHs per global time segment.

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:W96M5PEM}" style="apa" showimage="yes" download="yes" abstract="no" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->