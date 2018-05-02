
##Notes

usage is ./prog06 input output

It parses all inputs correctly, you can control the SDL loop with s and a, it may or may not calculate accumulated force properly (probably not), it handels vertex-based constraints properly, it computes new velocities and adjusts for drag, it updates the geometry for rasterization (whether the rasterization works properly is up in the air), and I provided a cloth simulation using a past obj file.


##References

This directory includes a simple piece of cloth as a Wavefront .obj format as well as some scene files to test the mass-spring system

Models in Wavefront .obj format

* quad.obj a simple triangle mesh of a quad that is triangulated with 289 vertices and 512 triangles

Scenes included are:

* cloth1.txt a cloth drop with the four corners pinned
* cloth2.txt a cloth drop with two of the corners pinned
* cloth3.txt a cloth drop with an entire side pinned
