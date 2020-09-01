## Information about ROIs

Many parameters characterizing ROIs are automatically calculated.

### ROI

Region Of Interest (ROI) posses various characteristics. Among them:

- surface: the number of pixels in the ROI
- external: the number of pixels that touch at least on one side an outside pixel
- perimeter: 
- Diameter of a circle of equal projection area (D<sub>EQPC</sub>):
  <img src="https://tex.cheminfo.org/?tex=D_%7BEQPC%7D%20%3D%202%20%5Csqrt%7B%5Cfrac%7BSurface%7D%7B%5Cpi%7D%7D"/>
- Diameter of a circle of equal perimeter (D<sub>PED</sub>):
  <img src="https://tex.cheminfo.org/?tex=D_%7BPED%7D%20%3D%20%5Cfrac%7BExternal%7D%7B%5Cpi%7D"/>

<img src="roi.svg">

### Minimum bounding rectangle (MBR)

An information that allows to determine the shape of a ROI is the `Minimum Bounding Rectange`(MBR) that represents the smallest rectangle that surround the ROI.

The MBR is characterized by:

- width: length of the longest side of the rectangle
- height: length of the smallest side of the rectangle
- perimeter: perimeter of the rectangle
- surface: surface of the rectangle

<img src="mbr.svg">

### Convex Hull (CH)

The convex hull may be visualized as the shape enclosed by a rubber band stretched around the ROI. It is useful to estimate the compactness of the ROI.

Two parameters are available for the convex hull:

- surface
- perimeter

<img src="hull.svg">

### Feret diameters

The feret diameters of a ROI can be calculated using a virtual caliper. 2 diameters are calculated:

- min: the minimal size of the ROI that could be measured using a caliper
- max: the maximal size of the ROI that could be measured by a caliper
- ψA (Aspect ratio): ratio of the minimum to the maximum Feret diameter (0 < ψA ≤ 1), an indication of the elongation of the particle

<img src="feret.svg">

### Other parameters

#### Sphericity

The sphericity is the ratio of the perimeter of the equivalent circle, P<sub>EQPC</sub>, to the real perimeter, P<sub>real</sub>.
A perfect sphere as a sphericity of 1. The idea is that irregular shape causes an increase in the perimeter and therefore this ratio has a lower value. Knowing that the smallest possible perimeter for a given projection area is a circle, 0 < S ≤ 1.

<img src="https://tex.cheminfo.org/?tex=S%20%3D%20%5Cfrac%7BP_%7BEQPC%7D%7D%7BP_%7Breal%7D%7D"/>

#### Roundness