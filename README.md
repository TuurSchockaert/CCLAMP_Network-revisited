# CCLAMP_Network-revisited
These are updated scripts to conduct social network analysis (SNA) on the authors in C-CLAMP.

## Create the network
Use `CCLAMP_Directed_Network_Notebook_update.ipynb`to create a list of all authors from `C-CLAMP_metadata_gender.txt` (see `Input`), and extract all mentions and co-authorships from the corpus data.

The network is stored as `CCLAMP_Directed_Network_update.txt` (see `Output`).

## Run and analyse community detection
Use `C-CLAMP_networks revisited.ipynb` to reload the network created in the previous step and apply both the Louvain and the Leiden community detection algorithms.

For more information on the network and additional scripts, see also `julienijs/Network_CCLAMP` (https://github.com/julienijs/Network_CCLAMP).
