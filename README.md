# Repo for Sixth Sense IEEG Focality Paper
author: **Ryan Gallagher**

### Getting Started
- clone this repo
  - can use VS Code, Github Desktop, or command line
```
git clone https://github.com/rgalls/Weighted_Distance.git [path_to_local]
```
- install [anaconda or miniconda](https://www.anaconda.com/download)

- open terminal at main codebase folder, run:
```
conda env create -n ieegpy -f environment.yml
```
- create ```code/config.json``` file by editing the [example](code/config-example.json)

### Description of repo
- [/code](/code) stores all code
  - [/scripts](/code/scripts) stores python scripts that download/save/format/load raw data, organized in order
  - [/notebooks](/code/notebooks) stores jupyter notebooks used for analysis
    - NormAtlas.ipynb formats the normative atlas data
    - Focality_IO_Data.ipynb analyzes bandpower and networks for patients
    - WeightedStandardDistance.ipynb completes the analysis of the paper
  - [/tools](/code/tools) stores functions used throughout code base (c: Akash Pattnaik), reformatted to separate bandpower and coherence measures
- /ieeg-metadata stores metadata associated with ieeg patients
- /data stores the actual ieeg data and intermediaries used throughout analysis

Please contact the CNT or Ryan Gallagher for access to the data.