# TBRIC-Public-main
 Tampa Bay Regional Inundation Coordination Project

[![Python_package Status](https://github.com/?/?/?/Python_package/?.svg)](https://github.com/?/?/?)

* Testing sharepoint Excel file links [Test1](https://tampabayplanning.sharepoint.com/:x:/s/Public/ETjIPnRwOa9DhSBTukSsKvABZblRCkTrdakUq_BWdvquVA?e=3SodSp)
* 
* Testing sharepoint Zip file links [Test2](https://tampabayplanning.sharepoint.com/:u:/s/Public/ETC3EvxA92VNg5m9T_qp2Y0BLLdReOJR8yG8xexcF4zNoQ?e=DzQHQg)

# Tampa Bay Regional Inundation Coordination (TBRIC) Tool Suite

## Description:
The TBRIC Tool Suite enables 

## Installation and Usage:
The TBRIC Tool Suite is a Python based tool.

The TBRIC Analysis Tool is an ESRI ArcGIS Pro based tool.

Detailed installation and usage instructions are explained in the TBRIC User Guide documentation here: [https://github.com/?/?/blob/main/documentation/?.pdf](https://github.com/?/?/blob/main/documentation/?_UserGuide_final.pdf)
* Download the latest release on the [Releases page](https://github.com/?/?/releases).
* Install the required dependencies (including ESRI ArcGIS Pro if using the TBRIC Analysis Tool).
* The documentation and quick start scenario files are included with the code release.

### Using this code
The Python dependencies are detailed in [`environment.yml`](https://github.com/?/?/blob/main/environment.yml). This assumes you have an installation of Python 3.7 and conda. These steps follow [this reference](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file). There are R components as well, which will be installed by conda in the R package library within the user's RDR conda environment.

From your Anaconda Prompt terminal, navigate to the location where you cloned this repository and run the following:

```
conda env create -f environment.yml
conda info --envs
```

You should see `?env` show up as an available environment.

## Contributing:
Add bugs and feature requests to the Issues tab in the [?](https://github.com/?/?/issues) for the TBRIC Development Team to triage.

## Credits:
* Ashley Mott (TBRPC) <ashley@tbrpc.org>
* Sam A. (Halff Associates Inc.)
* Sam S. (Halff Associates Inc.)


## Project Sponsors:
The development of the TBRIC Tool Suite was funded by the Florida Department of Environmental Protection (FDEP) Resilient Florida grant.

## Acknowledgements:
The TBRIC team thanks UF GeoPlan Centre and regional stakeholders. 

## License:
This project is licensed under the terms of the [?](https://github.com/?/?/blob/main/LICENSE). Please read it carefully.
