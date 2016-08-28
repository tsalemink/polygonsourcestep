Polygon Source Step
=======================
MAP Client plugin for reading polygon vertex coordinates and faces from a variety of file formats using VTK.

The supported file formats are: STL, OBJ, PLY, VRML, VTP.

Requires
--------
- VTK (>=5.10, 6) with Python bindins http://www.vtk.org/download/

Inputs
------
- **filename** [str][Optional] : Path of the file to be read.

Outputs
-------
- **pointclouds** [list] : A list of vertex coordinates.
- **faces** [list] : A list of the vertex indices of each face.

Configuration
-------------
- **identifier** : Unique name for the step.
- **File Format** : Format of the file to be read. "Auto" will guess the format from the file suffix.
- **Filename** : Path of the file to be read. If filename is provided via the input port, this value will be ignored.

Usage
-----
