---
ID: 621
post_title: 'RLFC: random access light field compression using key views and bounded integer sequence encoding'
author: gicomadmin
post_excerpt: >
  We present a new hierarchical
  compression scheme for encoding light
  field images (LFI) that is suitable for
  interactive rendering.Our method (RLFC)
  exploits redundancies in the light field
  images by constructing a tree structure.
  The top level (root) of the tree
  captures the common high-level details
  across the LFI, and other levels
  (children) of the tree capture specific
  low-level details of the LFI. Our
  decompressing algorithm corresponds to
  tree traversal operations and gathers
  the values stored at different levels of
  the tree.Furthermore, we use bounded
  integer sequence encoding which provides
  random access and fast hardware decoding
  for compress-ing the blocks of children
  of the tree. We have evaluated our
  method for 4D two-plane parameterized
  light fields. The compression rates vary
  from 0.08−2.5bits per pixel (bpp),
  resulting in compression ratios of
  around 200:1 to 20:1 for a PSNR quality
  of 40 to 50 dB. The decompression times
  for decoding the blocks of LFI are 1−3
  microseconds per channel on an NVIDIA
  GTX-960 and we can render new views with
  a resolution of 512×512 at 200fps. Our
  overall scheme is simple to implement
  and involves only bit manipulations and
  integer arithmetic operation
layout: post
permalink: >
  http://guillaumeisabelle.com/siggraph/2019/11/18/rlfc-random-access-light-field-compression-using-key-views-and-bounded-integer-sequence-encoding/
published: true
post_date: 2019-11-18 14:35:27
---
<!-- wp:paragraph -->

Interactive 3D Graphics and Games / Projections

<!-- /wp:paragraph -->

<!-- wp:paragraph -->

We present a new hierarchical compression scheme for encoding light field images (LFI) that is suitable for interactive rendering.Our method (RLFC) exploits redundancies in the light field images by constructing a tree structure. The top level (root) of the tree captures the common high-level details across the LFI, and other levels (children) of the tree capture specific low-level details of the LFI. Our decompressing algorithm corresponds to tree traversal operations and gathers the values stored at different levels of the tree.Furthermore, we use bounded integer sequence encoding which provides random access and fast hardware decoding for compress-ing the blocks of children of the tree. We have evaluated our method for 4D two-plane parameterized light fields. The compression rates vary from 0.08−2.5bits per pixel (bpp), resulting in compression ratios of around 200:1 to 20:1 for a PSNR quality of 40 to 50 dB. The decompression times for decoding the blocks of LFI are 1−3 microseconds per channel on an NVIDIA GTX-960 and we can render new views with a resolution of 512×512 at 200fps. Our overall scheme is simple to implement and involves only bit manipulations and integer arithmetic operation

<!-- /wp:paragraph -->

<!-- wp:shortcode --> [zotpress items="{180474:FVP37ECX}" style="apa" showimage="yes" download="yes" notes="yes" cite="yes" title="yes" abstract="no"] 

<!-- /wp:shortcode -->