# SPT-4-Vacuum-Window-Prototype
The prototype assembly and creep deflection tests of the Ultra-high molecular weight polyethylene (UHMWPE) vacuum window. I performed the creep deflection modeling and prototyping of this window for a thickness of 3 millimeters, which was chosen to minimize excess optical loading on the focal plane from the small (~1%) level absorption of UHMWPE at millimeter wavelengths. SPT-3G used a 10 millimeter thick High-density Polyethylene (HDPE) window, and we were unsure how the thinner material would behave when subjected to vacuum pressure. I calculated the initial deflection using thin plate theory, which necessitated adding an aluminum stiffening plate below. Further complications came with the creep properties of UHMWPE, which I first modeled as a static pressure offset in FEA. I then built an in-lab prototype of the window subassembly and performed deflection measurements as a function of time. Fitting this data to a creep model allowed me to build an understanding of the time-dependent behavior.

<p align="center">
  <img src="final_CAD_renders/SemiTransparentWindow_SPT4ProposalFigure.JPG" width="600">
</p>


## My Role:
- Led design, collaborating with Optics team on design constraints
- Designed and built prototype subassembly
- Conducted time-dependent deflection measurements using prototype

## Design Constraints:
- 99 millimeters of space between the vacuum window and the first lens
- 10 sheet (3 millimeters thick) Zotefoam stack of infrared filters
- 1 alumina disk (10 millimeters thick) mounted to the 50 Kelvin subassembly
- failure occurs when the vacuum window touches the optics stack (<28 millimeters of deflection)

## Summary of Results:
- deflections are too high and a thicker window is needed
- more IR filtering compensates the higher optical load from the 10 millimeter thick HDPE window

## Files:
