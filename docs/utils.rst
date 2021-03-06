List of Phantom utilities
-------------------------

To compile all of the most commonly used utilities, use:

::

   make utils

A full list is given below:

+-----------------------+-----------------------+-----------------------+
| Binary name           | make command          | Description           |
+=======================+=======================+=======================+
| phantomsetup          | make setup            | General utility for   |
|                       |                       | setting up initial    |
|                       |                       | conditions            |
+-----------------------+-----------------------+-----------------------+
| phantomanalysis       | make analysis         | General analysis      |
|                       |                       | utility               |
+-----------------------+-----------------------+-----------------------+
| phantommoddump        | make moddump          | Utility to            |
|                       |                       | edit/modify contents  |
|                       |                       | of a phantom dump     |
|                       |                       | file                  |
+-----------------------+-----------------------+-----------------------+
| showheader            | make showheader       | Utility to print      |
|                       |                       | contents of dump file |
|                       |                       | headers               |
+-----------------------+-----------------------+-----------------------+
| showarrays            | make showarrays       | Utility to list       |
|                       |                       | arrays written in     |
|                       |                       | dump file             |
+-----------------------+-----------------------+-----------------------+
| diffdumps             | make diffdumps        | Check if two phantom  |
|                       |                       | dump files are        |
|                       |                       | identical             |
+-----------------------+-----------------------+-----------------------+
| phantom2sphNG         | make phantom2sphNG    | Convert a phantom     |
|                       |                       | dump to sphNG format  |
+-----------------------+-----------------------+-----------------------+
| phantom2gadget        | make phantom2gadget   | Convert a phantom     |
|                       | (or make p2g)         | dump to GADGET format |
+-----------------------+-----------------------+-----------------------+
| multirun              | make multirun         | Utility to write a    |
|                       |                       | batch of input files, |
|                       |                       | varying input         |
|                       |                       | parameters            |
+-----------------------+-----------------------+-----------------------+
| ev2mdot               | make ev2mdot          | Compute accretion     |
|                       |                       | rates from the .ev    |
|                       |                       | files                 |
+-----------------------+-----------------------+-----------------------+
| splitpart             | make splitpart        | Split particles       |
|                       |                       | to create a high res  |
|                       |                       | dump file             |
+-----------------------+-----------------------+-----------------------+
| plotkernel            | make plotkernel       | Utility to plot the   |
|                       |                       | kernel functions from |
|                       |                       | the kernel module     |
+-----------------------+-----------------------+-----------------------+
| phantom2pdf-amr       | make phantom2pdf-amr  | Compute               |
|                       |                       | volume-weighted PDFs  |
|                       |                       | via interpolation to  |
|                       |                       | 3D AMR grid           |
+-----------------------+-----------------------+-----------------------+
| grid2pdf              | make grid2pdf         | Compute Probability   |
|                       |                       | Density Function      |
|                       |                       | using output of       |
|                       |                       | splash to grid        |
+-----------------------+-----------------------+-----------------------+
| phantom2divv          | make phantom2divv     | Compute div and curl  |
|                       |                       | of velocity field     |
|                       |                       | from dump file using  |
|                       |                       | post-processing       |
+-----------------------+-----------------------+-----------------------+
| phantom2divb          | make phantom2divb     | Compute div and curl  |
|                       |                       | of magnetic field     |
|                       |                       | from dump file using  |
|                       |                       | post-processing       |
+-----------------------+-----------------------+-----------------------+
| phantom2struct        | make phantom2struct   | Compute structure     |
|                       |                       | functions from        |
|                       |                       | particles (SLOW!)     |
+-----------------------+-----------------------+-----------------------+
| struct2struct         | make struct2struct    | Convert structure     |
|                       | (or make sfutils)     | function files        |
|                       |                       | between various       |
|                       |                       | formats               |
+-----------------------+-----------------------+-----------------------+
| get_struct_slope      | make get_struct_slope | Determine slope of    |
|                       | (or make              | structure functions   |
|                       | get_slope_sf)         | from output files     |
+-----------------------+-----------------------+-----------------------+
