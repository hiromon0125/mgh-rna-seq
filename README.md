# RNA-Sequencing project

This a project under Massachusetts General Hospital developed by Hiroto Takeuchi.

## Setup
Make sure you have the following programs installed:
- fastqc
- trimmomatic
- STAR
- featureCounts

install UV [here](https://docs.astral.sh/uv/getting-started/installation/)
Run `uv sync` to install the dependencies of the project.
Run `uv run --with jupyter jupyter lab`
This should open a jupyter notebook on port 8888.

For more information on using uv with jupyter notebook see [here](https://docs.astral.sh/uv/guides/integration/jupyter/).


## Process/Tools
- FastQC(File format for this dataset)
- Trim(cutadapt)
- Mapping(Star alignment)
- Quantification(featureCounts)

## Setup for tools
- Cutadapt
This is already installed via uv as a dependency of this project.
- Star Alignment
This was needed to be installed manually and compiled from source. 
The repository can be found [here](https://github.com/alexdobin/STAR).

