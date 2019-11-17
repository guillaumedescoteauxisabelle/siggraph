---
ID: 301
post_title: >
  A visual model for quality driven
  refinement of global illumination
author: gicomadmin
post_excerpt: >
  When rendering complex scenes using
  path-tracing methods, long processing
  times are required to calculate a su
  cient number of samples for high quality
  results. In this paper, we propose a new
  method for priority sampling in
  path-tracing that exploits restrictions
  of the human visual system by
  recognizing whether an error is
  perceivable or not. We use the
  stationary wavelet transformation to e
  ciently calculate noise-contrasts in the
  image based on the standard error of the
  mean. We then use the Contrast
  Sensitivity Function and Contrast
  Masking of the Human Visual System to
  detect if an error is perceivable for
  any given pixel in the output image.
  Errors that can not be detected by a
  human observer are then ignored in
  further sampling steps, reducing the
  amount of samples calculated while
  producing the same perceived quality.
  This approach leads to a drastic
  reduction in the total number of samples
  required and therefore in total
  rendering time.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/16/a-visual-model-for-quality-driven-refinement-of-global-illumination/
published: true
post_date: 2019-11-16 21:46:33
---
<!-- wp:paragraph -->

Applied Perception

<!-- /wp:paragraph -->

<!-- wp:block {"ref":302} /-->