---
ID: 339
post_title: 'Subspace neural physics: fast data-driven interactive simulation'
author: gicomadmin
post_excerpt: >
  Data-driven methods for physical
  simulation are an attractive option for
  interactive applications due to their
  ability to trade precomputation and
  memory footprint in exchange for
  improved runtime performance. Yet,
  existing data-driven methods fall short
  of the extreme memory and performance
  constraints imposed by modern
  interactive applications like AAA games
  and virtual reality. Here, performance
  budgets for physics simulation range
  from tens to hundreds of micro-seconds
  per frame, per object. We present a
  data-driven physical simulation method
  that meets these constraints. Our method
  combines subspace simulation techniques
  with machine learning which, when
  coupled, enables a very efficient
  subspace-only physics simulation that
  supports interactions with external
  objects – a longstanding challenge for
  existing sub-space techniques. We also
  present an interpretation of our method
  as a special case of subspace Verlet
  integration, where we apply machine
  learning to efficiently approximate the
  physical forces of the system directly
  in the subspace. We propose several
  practical solutions required to make
  effective use of such a model, including
  a novel training methodology required
  for prediction stability, and a
  GPU-friendly subspace decompression
  algorithm to accelerate rendering
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/17/subspace-neural-physics-fast-data-driven-interactive-simulation/
published: true
post_date: 2019-11-17 01:27:02
---
<!-- wp:paragraph -->

cloth simulation, collision detection, neural networks, machine learning, model reduction, data-driven simulation 

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:IC7VVIY4}" style="apa" showimage="yes" download="yes" abstract="yes" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->