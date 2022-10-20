# Molecular-Generation

This repository contains some of the files from a molecular generation project that I am contributing to this semester (Fall 2022). 

# Instructions to run the gnn.py file 
(containing implementation of basic graph neural networks):

Create a conda environment: run

conda create -c conda-forge -n rl_vae rdkit

conda activate rl_vae

conda install pytorch torchvision torchaudio -c pytorch

pip install torch-scatter -f https://data.pyg.org/whl/torch-${TORCH}+${CUDA}.html

pip install torch-sparse -f https://data.pyg.org/whl/torch-${TORCH}+${CUDA}.html

pip install torch-geometric

pip install seaborn

cd ... #path to folder

python gnn.py

