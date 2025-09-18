# PyFinder-Dev

## Purpose
PyFinder is a Python wrapper around the [FinDer](https://docs.gempa.de/sed-eew/current/apps/scfinder.html) executable, designed to facilitate the use of FinDer's functionalities in Python environments. The current implementation wraps the FinDer command-line tool, providing easier integration and automation. Future plans include adding direct bindings for the FinDer library to enable more seamless and efficient usage.

## Repositories
- [**pyfinder-docker**](https://github.com/pyfinder-dev/pyfinder-docker): Docker images and configurations for running PyFinder in containerized environments. The base image includes FinDer executable and libraries. This repository is the top level component of the pyFinder workflow.
- [**pyfinder**](https://github.com/pyfinder-dev/pyfinder): The main Python wrapper around the FinDer executable. Pulled by the `pyfinder-docker`
- [**paramws-clients**](https://github.com/pyfinder-dev/paramws-clients): A parametric web service framework supporting PyFinder and related tools. Also pulled from the `pyfinder-docker`.

## History
PyFinder originated as part of the [DT-GEO project](https://dtgeo.eu), which focused on geospatial data processing and analysis. The original DT-GEO DTC-E6 repository can be found [here](https://github.com/DT-Geo-SED-ETHZ/DTC-E6). After the conclusion of DT-GEO, PyFinder has continued as an independent project, evolving to meet the needs of its user community.

## Future Roadmap
- Development of additional parametric web services to extend the capabilities of PyFinder.
- Implementation of direct bindings to the FinDer library to improve performance and usability.
- Continued enhancement of Docker support for easier deployment and scalability.

## License
PyFinder is released under the MIT License, allowing broad usage and modification. However, the underlying FinDer library remains closed source and is not included under the MIT License.
