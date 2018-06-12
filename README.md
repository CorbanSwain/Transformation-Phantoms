# Transformation Reference Images
*To be used in comparing rotation and translation operations performed by 
different people or methods. ... because* `Coordinate systems = 🙃`

## Description
### `axis phantom`

<p align="center">
  <img width="256" height="256" src="/demos/demo_1.gif">
</p>

These phantom volumes are cubes containing three orthoganl arrows corresponding to the 
rows (1), columns (2), and pages (3) of the volume representative of MATLAB's indexing style. 
* The arrows point in the direction of increasing index. 
* Each of the arrows are 'annotated' with spherical beads: 
  * the row axis arrow is annotated with 1 bead, 
  * the column axis arrow is annotated with 2 beads, and 
  * the pages axis arrow is annotated with 3 beads.

### `bead phantom`
These phandton volumes are 5 beads randomly scattered. 

## Files
Volumes are stored in both .tif and .mat formats.
1. `.tif` files are 8 bit grayscale images
1. `.mat` files contain a logical matrix named `A`

The number before the file extension corresponds to the side length
of the cubic volume in pixels.
