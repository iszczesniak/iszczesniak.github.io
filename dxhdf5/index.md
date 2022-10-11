# The dxhdf5 package

During the summers of 2003 and 2002, I was working for Prof. John
R. Cary as a computer programmer at the Center for Integrated Plasma
Studies of the University of Colorado at Boulder, USA.  My task was to
design and develop modules for the OpenDX package.  That was a great
experience.  OpenDX was a great, reliable, fast and well-documented
piece of software.

The package contains two OpenDX modules: ImportHDF5Field and
ImportHDF5Species. The ImportHDF5Field module imports a field or a
slab of a field from an HDF5 file. The field must be described on a
regular grid, and the HDF5 file must have an appropriate
structure. The ImportHDF5Species module imports from an HDF5 file
particles which satisfy the user's conditions. The HDF5 file must be
of a special format.

My contributions to the package included:

* designing and implementing C++ classes,

* implementing the Autoconf/Automake structure of the package,

* designing and implementing the OpenDX interfaces of the two modules,

* writing the documentation.

This article is about the package:

I. Szcześniak, J. R. Cary, "dxhdf5: A Software Package for Importing
HDF5 Physics Data into OpenDX," Computer Physics Communications,
vol. 164, issue 1-3, Elsevier, pp. 365-369, 2004

<http://irkos.org/pubs/dxhdf5.pdf>

<http://irkos.org/pubs/dxhdf5-presentation.pdf>

<http://irkos.org/pubs/dxhdf5-poster.pdf>
