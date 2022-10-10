# Molecular-Generation

This repository contains files from our molecular generation project. 

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

cd to whatever folder your script is in

python gnn.py

