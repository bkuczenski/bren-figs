==========
Wed Nov 21 23:28:05 PST 2012

TeX code and data for producing figures for projects at Bren (or by people
at Bren).

CONTENTS:

dor-exec (2011-06-08)

  Comparison of UCSB and MSU impact assessment results from the production
  of 1 kg PET polymer.  MSU used ecoinvent-US (US powergrid substituted for
  default); UCSB used US LCI.  Global Warming Potential is within 20%; many
  others are off by an order of magnitude.

  TeX requirements: pstricks, plus barfigs.sty and arraydata.sty (provided)
  arraydata is a customization of arrayjobx; barfigs is quite elaborate but
  is barely used here.  A minimal reimplementation would be
  straightforward. 

  3 related figures provided.  Each column is scaled separately:

  dor-compare  : normalize to largest
  dor-compare2 : normalize to UCSB
  dor-compare3 : normalize to MSU

  build [dor-exec-figs.tex] using latex => dvips => ps2pdf

calcium (2010-02-10)

  (Not Bren-related) some post-thesis work I did for my PhD advisors that
  never got published, but which nonetheless came out looking really nice.

  Requires pstricks-add but nothing else exotic.  

  Build [calcium-figs.tex] via latex => dvips => ps2pdf.

