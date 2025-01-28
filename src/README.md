# Simulator Description

This simulator supports two types of simulation scenarios. The first scenario operates in a non-IID (Non-Independent and Identically Distributed) data environment, where data is distributed across clients in a heterogeneous manner. The second scenario extends this further by incorporating both non-IID and heterogeneous data settings, where each client is assigned entirely different datasets, ensuring an even greater diversity in data distribution.

In the first scenario, the simulation uses the file `CIDS-Sim_Non-IID.ipynb` in folder `Non-IID`. In the second scenario the simulation is conducted using the file `CIDS-Sim_Non-IID_Heterogeneous.ipynb` in folder `Heterogeneous`. The default dataset setup for the first scenario is using `CoAt_NF-UQ-NIDS-V2`. The default dataset setup for the first scenario is using `CoAt_CIC-BoT-IoT-V2.parquet`, `CoAt_CIC-IDS2017-V2.parquet`, `CoAt_CIC-ToN-IoT-V2.parquet`, `CoAt_CIC-UNSW-NB15_Feeded-V2.parquet`, and `CoAt_CSE-CIC-IDS2018_Feeded.parquet`. Please open each folder of the simulator and dataset to read the details about each simulation scenario.

# Simulator Details

The details about code and explanation about the simulator can be see [here](https://cids-sim-doc.readthedocs.io/)