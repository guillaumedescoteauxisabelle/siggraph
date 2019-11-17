---
ID: 336
post_title: >
  EigenFit for consistent elastodynamic
  simulation across mesh resolution
author: gicomadmin
post_excerpt: 'Elastodynamic system simulation is a key procedure in computer graphics and robotics applications. To enable these simulations, the governing differential system is discretized in space (employing FEM) and then in time. For many simulation-based applications keeping the spatial resolution of the computational mesh effectively coarse is crucial for securing acceptable computational efficiency.However, this can introduce numerical stiffening effects that impede visual accuracy.We propose and demonstrate, for both linear and nonlinear force models, a new method called EigenFit that improves the consistency and accuracy of the lower energy, primary deformation modes, as the spatial mesh resolution is coarsened. EigenFit applies a partial  spectral decomposition, solving a generalized eigenvalue problem in the leading mode subspace and then replacing the first several eigen values of the coarse mesh by those of the fine one at rest. EigenFit’s performance relies on a novel subspace model reduction technique which restricts the spectral decomposition to finding just a few of the leading eigenmodes. We demonstrate its efficacyon a number of objects with both homogenous and heterogenous material distribution'
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/17/eigenfit-for-consistent-elastodynamic-simulation-across-mesh-resolution/
published: true
post_date: 2019-11-17 01:23:05
---
<!-- wp:paragraph -->

Elastodynamic simulation, numerical stiffening 

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:S3WAIWKV}" style="apa" showimage="yes" download="yes" abstract="yes" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->