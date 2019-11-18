---
ID: 566
post_title: >
  Extended Morton codes for high
  performance bounding volume hierarchy
  construction
author: gicomadmin
post_excerpt: 'We propose an extension to the Morton codes used for spatial sorting of scene primitives. e extended Morton codes increase the coherency of the clusters resulting from the object sorting and work be er for non-uniform distribution of scene primitives. In particular, our codes are enhanced by encoding the size of the objects, applying adaptive ordering of the code bits, and using variable bit counts for di erent dimensions. We use these codes for constructing Bounding Volume Hierarchies (BVH) and show that the extended Morton code leads to higher quality BVH, particularly for the fastest available BVH build algorithms that heavily rely on spatial coherence of Morton code sorting. In turn, our method allows to achieve up to 54% improvement in the BVH quality especially for scenes with a non-uniform spatial extent and varying object sizes. Our method is easy to implement into any Morton code based build algorithm as it involves only a modi cation of the Morton code computation step.'
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/extended-morton-codes-for-high-performance-bounding-volume-hierarchy-construction/
published: true
post_date: 2019-11-18 10:58:24
---
<!-- wp:paragraph -->

"Increase the coherency of the clusters resulting from the object sorting and work better for non-uniform distribution of scene primitives "  
* constructing Bounding Volume Hierarchies (BVH) 

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

We propose an extension to the Morton codes used for spatial sorting of scene primitives. e extended Morton codes increase the coherency of the clusters resulting from the object sorting and work be er for non-uniform distribution of scene primitives. In particular, our codes are enhanced by encoding the size of the objects, applying adaptive ordering of the code bits, and using variable bit counts for di erent dimensions. We use these codes for constructing Bounding Volume Hierarchies (BVH) and show that the extended Morton code leads to higher quality BVH, particularly for the fastest available BVH build algorithms that heavily rely on spatial coherence of Morton code sorting. In turn, our method allows to achieve up to 54% improvement in the BVH quality especially for scenes with a non-uniform spatial extent and varying object sizes. Our method is easy to implement into any Morton code based build algorithm as it involves only a modi cation of the Morton code computation step.

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:RIT5U4TM}" style="apa" showimage="yes" download="yes" abstract="no" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->