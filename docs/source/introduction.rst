Introduction
============

Overview
--------

PyRDM is a project that focuses on the relationship between data and the
scientific software that has either created that data, or operates on
that data to create new information. Two examples from geoscience are
given for illustrative purposes:

-  Dispersion of saline solution into an estuary from desalination
   plant.

   -  Input data: Bathymetry, atmospheric forcing, etc.

   -  Software: Pre-/post-processing codes; numerical models.

   -  Output data: Provenance; simulated flow fields; diagnostic
      quantities.

-  Characterisation of pores media for carbon sequestration.

   -  Input data: Micro-CT images of rock samples.

   -  Software: Pre-/post-processing of data (e.g. image segmentation,
      mesh generation); numerical models.

   -  Output data: Provenance; computational meshes that could be used
      by other flow solvers; computed flow fields; diagnostics.

From these two examples one can already start to see a great deal of
generality emerging. In order to achieve reproducibility, or indeed
computability, one must be able to capture all of the input data (i.e.
collected/measured data which should also have its associated
provenance). Next the actual software that draws information from that
data must be captured, and care must be taken to ensure that the same
version that created a particular result from the data is used. Finally,
the output data from the software must be captured, including provenance
data that details how the input data and software were used to create
this new data. PyRDM aims to address these needs by facilitating the
automated management and online publication of software and data via
citable repositories hosted by Figshare. This library can be
incorporated into the workflow of scientific software to allow research
output to be curated in a straight-forward manner.

Licensing
---------

PyRDM is released under the GNU General Public License. Further details
can be found in the COPYING file supplied with this software.

