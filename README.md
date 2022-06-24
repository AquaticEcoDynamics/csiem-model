# CSIEM

[![TUFLOW-FV](https://img.shields.io/badge/TUFLOW--FV-2020.008-yellow)](https://tuflow.com/products/tuflow-fv/)
[![AED](https://img.shields.io/badge/AED-2.0.0-brightgreen)](https://aquatic.science.uwa.edu.au/research/models/AED/quickstart.html)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)


## The Cockburn Sound Integrated Ecosystem Model

This repository houses the hydrodynamic-biogeochemical model for [Cockburn Sound](https://en.wikipedia.org/wiki/Cockburn_Sound), located on the coast of Perth, Western Australia. 

The model uses the [TUFLOW-FV](https://www.tuflow.com/products/tuflow-fv/) 3D finite volume hydrodynamic model, and the [AED](https://aquaticecodynamics.github.io/aed-science/) water quality model.

Various generations of the model system exist and are archived; here the latest CSIEM generation is active. 

For a sceintific overview of the model setup, validation and other information, please access the `csiem-science` repo.

## Usage

This repository includes the model files required for a TUFLOW-FV - AED simulation run. Running the setup contained herein requires users to have an active TUFLOW-FV license with the AED [pre-compiled plugin](https://aquatic.science.uwa.edu.au/research/models/AED/quickstart.html). Input files and model output files are able to be processed using the `csiem-marvl` repository that includes the supporting scripts and site data. Please contact the developers for further information.

