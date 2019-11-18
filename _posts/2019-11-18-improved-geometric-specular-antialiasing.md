---
ID: 618
post_title: Improved geometric specular antialiasing
author: gicomadmin
post_excerpt: 'Shading filtering proposed by Kaplanyan et al. [2016] is a simple solution for specular aliasing. It filters a distribution of microfacet normals in the domain of microfacet slopes by estimating the filtering kernel using derivatives of a halfway vector between incident and outdoing directions. However, for real-time rendering, this approach can produce noticeable artifacts because of an estimation error of derivatives. For forward rendering, this estimation error is increased significantly at grazing angles and near edges. The present work improves the quality of the original technique, while decreasing the complexity of the code at the same time. To reduce the error, we introduce a more efficient kernel bandwidth that takes the angle of the halfvector into account. In addition, we optimize the calculation of an isotropic filter kernel used for deferred rendering by applying the proposed kernel bandwidth. As our implementation is simpler than the original method, it is easier to integrate in time-sensitive applications, such as game engines, while at the same time improving the filtering quality.'
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/improved-geometric-specular-antialiasing/
published: true
post_date: 2019-11-18 14:39:26
---
<!-- wp:paragraph -->

Interactive 3D Graphics and Games / Projections

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

Shading filtering proposed by Kaplanyan et al. [2016] is a simple solution for specular aliasing. It filters a distribution of microfacet normals in the domain of microfacet slopes by estimating the filtering kernel using derivatives of a halfway vector between incident and outdoing directions. However, for real-time rendering, this approach can produce noticeable artifacts because of an estimation error of derivatives. For forward rendering, this estimation error is increased significantly at grazing angles and near edges. The present work improves the quality of the original technique, while decreasing the complexity of the code at the same time. To reduce the error, we introduce a more efficient kernel bandwidth that takes the angle of the halfvector into account. In addition, we optimize the calculation of an isotropic filter kernel used for deferred rendering by applying the proposed kernel bandwidth. As our implementation is simpler than the original method, it is easier to integrate in time-sensitive applications, such as game engines, while at the same time improving the filtering quality.

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:8KN2IGE2}" style="apa" showimage="yes" download="yes" notes="yes" cite="yes" title="yes" abstract="no"] 

<!-- /wp:shortcode -->