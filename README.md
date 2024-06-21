# Private Billings: Data Generation
This repository contains the [notebook](generation.ipynb) used to generate the production and consumption data used in the [experimentation](https://github.com/3MI-Labs/private-billings-experiment) of the [Private Billings](https://github.com/3MI-Labs/private-billings) project.

## Structure
This repository contains several Jupyter notebooks used to generate this data.
- **[wind.ipynb](wind/wind.ipynb)**. Generate wind power production data.
- **[pv.ipynb](pv/pv.ipynb)**. Generate photo voltaic production data.
- **[consumption.ipynb](consumption/consumption.ipynb)**. Generate user electricity consumption data.
- **[generation.ipynb](generation.ipynb)**. Combine the data generated by the other notebooks into a usable dataset.

## Setup
The [`requirements.txt`](requirements.txt) file lists all the python packages and their versions used when generating data.
The file specifies which versions are fixed and which are potentially flexible.
For the packages labelled 'potentially flexible' other versions might work too, but no guarantees are provided.

## Acknowledgements
The notebooks contained in this repository used notebooks in other repositories drew inspiration for several other repositories:
- [wind.ipynb](wind/wind.ipynb) and [pv.ipynb](pv/pv.ipynb) are based on [WindpowerlibTurbine-model](https://github.com/PeijieZ/WindpowerlibTurbine-model) by PeijieZ.
- [consumption.ipynb](consumption/consumption.ipynb) is based on [Load-profile-generation](https://github.com/PeijieZ/Load-profile-generation), written by PeijieZ.
- [generation.ipynb](generation.ipynb) is inspired by [Billing-Models-for-Electricity-Trading-Markets](https://github.com/PeijieZ/Billing-Models-for-Electricity-Trading-Markets), written by PeijieZ.