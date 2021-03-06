<p align="center"><img src="https://github.com/GIS4WRF/gis4wrf-docs/blob/master/images/gis4wrf.png"></p>

# GIS4WRF
GIS4WRF is a free and open source [QGIS](https://qgis.org/) plug-in to help researchers and practitioners with their [Advanced Research Weather Research and Forecasting](https://www.mmm.ucar.edu/weather-research-and-forecasting-model) modelling workflows. GIS4WRF can be used to pre-process input data, run simulations, and visualize or post-process results (Fig. 1). We currently support GIS4WRF for Windows (7, 8, 10), macOS (Sierra, High Sierra), and Ubuntu (17.x, 18.x). 

*Did you know? We provide pre-built WPS and WRF binaries for Windows. After [installing](#installation-overview) GIS4WRF go ahead and explore all its features from the included [documentation](#documentation-overview).*

<p align="center"><img src="https://github.com/GIS4WRF/gis4wrf-docs/blob/master/images/gis4wrf-demo.gif"></p>
<p align="center">Fig 1. Configure, run and visualize a WRF simulation in GIS4WRF</p>

*Tip: if you would like us to support other Linux distributions, fix a bug, or simply add a new feature, do let us know by [opening an issue](https://github.com/GIS4WRF/gis4wrf/issues).*

## Table of Contents
- [GIS4WRF](#gis4wrf)
    - [Table of Contents](#table-of-contents)
    - [Installation Overview](#installation-overview)
    - [Documentation Overview](#documentation-overview)
    - [How to reference GIS4WRF](#how-to-reference-gis4wrf)
    - [Contributing](#contributing)
    - [Versioning](#versioning)
    - [Copyright and Licence](#copyright-and-licence)

## Installation Overview
If you are already familiar with QGIS and have already installed the latest version of **QGIS 3** on your system, you can find GIS4WRF ready to be downloaded and installed from the `Plugins` > `Manage and Install Plugins...` menu (Fig 2). If you are not familiar with QGIS, or are encountering issues with the installation, please refer to the [installation guide](INSTALL.md).

<p align="center"><img src="https://github.com/GIS4WRF/gis4wrf-docs/blob/master/images/gis4wrf-installation.gif"></p>
<p align="center">Fig 2. GIS4WRF — Installation</p>

After installation, you can configure GIS4WRF directly in QGIS from the `Settings` > `Options...` > `GIS4WRF` menu (Fig. 3). To learn more about features and how to use GIS4WRF please refer to the GIS4WRF [documentation](#documentation-overview). 

<p align="center"><img src="https://github.com/GIS4WRF/gis4wrf-docs/blob/master/images/gis4wrf-configuration.gif"></p>
<p align="center">Fig 3. GIS4WRF — Configuration</p>

## Documentation Overview
Documentation on how to use GIS4WRF can be found directly in GIS4WRF under the `Home` tab. At each release of GIS4WRF, we bundle the most up-to-date documentation found in the [GIS4WRF documentation repository](https://github.com/GIS4WRF/gis4wrf-docs). If you find a mistake in the documentation, would like to contribute or you would like to simply browse the documentation outside of QGIS, please refer to the [GIS4WRF documentation repository](https://github.com/GIS4WRF/gis4wrf-docs#gis4wrf-documentation).


## How to reference GIS4WRF
We ask to please acknowledge our work by citing and referencing both, the GIS4WRF paper and the GIS4WRF software in the following way:

- For in-text citations, please cite both the paper and the software.

    E.g.: *"We used GIS4WRF (Meyer and Riechert, 2018a, 2018b) for ..."*

- For the full citation in the reference list, adapt using your chosen style from the example below.

    E.g. — reference list using the American Meteorological Society (AMS) style:

    ```
    Meyer, D., and M. Riechert 2018a. GIS4WRF: an integrated open source QGIS toolkit
        for the Advanced Research WRF Framework. Manuscript submitted for publication.

    Meyer, D., and M. Riechert, 2018b. GIS4WRF.
        doi:10.5281/zenodo.1288569.
    ```

## Contributing
If you would like to contribute to the GIS4WRF project, clone this repository, make your changes, and create a pull request with a **clear description** of your changes. If your changes are merged, you will appear as one of our [Contributors](https://github.com/GIS4WRF/gis4wrf/graphs/contributors).

## Versioning
This project uses [semantic versioning](https://semver.org/).

## Copyright and Licence
Copyright 2018 D. Meyer and M. Riechert. Released under [MIT License](LICENSE.txt).