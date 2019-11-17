---
ID: 320
post_title: Small steps in physics simulation
author: gicomadmin
post_excerpt: >
  In this paper we re-examine the idea
  that implicit integrators with large
  time steps offer the best
  stability/performance trade-off for
  stiff systems. We make the surprising
  observation that performing a single
  large time step with n constraint solver
  iterations is less effective than
  computing n smaller time steps, each
  with a single constraint solver
  iteration. Based on this observation,
  our approach is to split every visual
  time step into n substeps of length
  ∆t/n and to perform a single iteration
  of extended position-based dynamics
  (XPBD) in each such substep. When
  compared to a traditional implicit
  integrator with large time steps we find
  constraint error and damping are
  significantly reduced. When compared to
  an explicit integrator we find that our
  method is more stable and robust for a
  wider range of stiffness parameters.
  This result holds even when compared
  against more sophisticated implicit
  solvers based on Krylov methods. Our
  method is straightforward to implement,
  and is not sensitive to matrix
  conditioning nor is it to
  overconstrained problems.
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/17/small-steps-in-physics-simulation/
published: true
post_date: 2019-11-17 00:47:06
---
<!-- wp:paragraph -->



<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:ZLYYL3LT}" style="apa" showimage="yes" download="yes" abstract="yes" notes="yes" cite="yes" title="yes"] 

<!-- /wp:shortcode -->