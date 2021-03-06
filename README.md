FabSim
======

FabSim is a Python-based automation toolkit for scientific simulation and data processing workflows, licensed under the BSD 3-clause license. It aims to enable users to perform remote tasks from a local command-line, and to run applications while curating the environment variables and the input and output data in a systematic manner. To provide that curation, FabSim uses a basic data transfer functionalities such as rsync and ssh. 

FabSim also contains a system for defining machine-specific configurations, including templates to execute jobs through schedulers such as PBSPro, Loadleveller and SGE. These machine-specific configurations are stored in the repository, apply to all applications run on that machine, and can be updated by any contributor who feels that a fix or improvement is required.

FabSim relies strongly on Fabric (http://www.fabfile.org, shown to work with versions 1.5.3 and 1.10.0) and PyYAML. Previous versions of FabSim (most notably FabHemeLB and FabMD) have been used to run simulation workflows on machines such as ARCHER, SuperMUC, BlueJoule, as well as local clusters and desktops.

FabSim is now publicly available (as early-stage software) at: http://www.github.com/djgroen/FabSim

Derivative versions of FabSim include:
* FabHemeLB (previously known as _FabricHemeLB_), which is used to automate workflows involving 
the HemeLB lattice-Boltzmann simulation environment (see http://www.github.com/UCL/hemelb for 
the source code of that).
* FabMD, which is used to semi-automatically coarse-grain polymer systems (part of this repository).
* FabBioMD, which is used to facilitate protein-ligand binding affinity calculations (part of this repository).


## Installation and usage 

For instructions on how to install and test FabSim, please refer to `INSTALL.md`.
