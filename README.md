# Automated Workflows for Digital-Twin of Chromatography Resin: Generation of All-atom Structures and Modelling of Peptide Adsorption 
<p align="center">
  <img src="https://github.com/user-attachments/assets/5c8fc319-423b-461e-9fae-daf64e3deb6c" alt="workflow image" width="400" height="auto" />
  <br />
  <small>Binding pose of Octapeptide-2 to TOYOPEARL MX-Trp-650M</small>
</p>

## Overview
This set of workflows as [SimStack Workflow](Simstack%20Workflow/) and [KNIME Workflow](KNIME%20Workflow/) in combination enables high-throughput 
  1. generation of atomistic models of a chromatography resin, based on user selection of building block types and densities
  2. investigates the adsorption against target molecules, a selection of peptides as in the example
_in silico_ experiments to test the chromatographic performance of the designer resin.

The adsorption of the digital-twin of the chromatography resin will be later compared to data from the high-throughput experiments in the lab of [AG Franzreb](https://www.ifg.kit.edu/292.php) in Institute of Functional Interfaces, Karlsruhe Institute of Technology.

Current version of the workflow is an extension of the methodology first validated in [Ballweg et al.](https://doi.org/10.1016/j.chroma.2024.465089) for the adsorption of dye molecules with a designer chromatography resin.

Detailed descriptions are available in respective folders for the workflows. At the moment, the Schrödinger software is required as interface the [SimStack Workflow](Simstack%20Workflow/) and the [KNIME Workflow](KNIME%20Workflow/).
