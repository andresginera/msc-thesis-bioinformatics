========
Abstract
========

**GaudiMM** is a modular platform for 3D sketching of molecular systems in situations with initial scarce structural data, employing the NGSA-II multi objective genetic algorithm. It has been proved successful in a variety of scenarios like metal coordination or covalent docking, so it is promising in the molecular modelling field. However, the current version has limitations and there is room for improvement in several ways.

One of the aspects is the optimization of its performance. GaudiMM uses only a unique core for the execution and, as a consequence, there are some processes which require so complex calculations that they cannot be performed, in addition to the problem of large execution time that this entails. In response to this, we have developed an extension for GaudiMM to improve the performance through a parallelization of the process, the **PGaudi** program. This can reduce the execution time without decreasing the output quality.

But the limitations are not only about performance, but also, about the user experience or how the user interacts with the program. In this aspect, we though in improving this interaction by developing new graphical interfaces for the creation of input files for GaudiMM and for the visualization of the output results. In this Master’s Thesis, we have updated the GaudiView graphical interface, creating **GaudiViewX**, a new version of the interface based on Python 3 and UCSF ChimeraX instead of Python 2 and UCSF Chimera.

Keywords
========

Chemical computation, molecular modelling, parallelization, user experience, graphic interface, bioinformatics, Python.

Code availability
=================

All code developed is written in Python and is available in the InsiliChem Github page.

DOI PGaudi: `10.5281/zenodo.3250394 <https://zenodo.org/record/3250394>`_.

DOI GaudiViewX: `10.5281/zenodo.3258020 <https://zenodo.org/record/3258020>`_.
