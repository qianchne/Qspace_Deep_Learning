# Qspace Deep Learning

This repository provides implementation codes for "Jointly estimating parametric maps of multiple diffusion models from nndersampled q-space data: A comparison of three deep learning approaches."



https://user-images.githubusercontent.com/1512443/147379103-f3d80ff6-dcac-440b-b829-2111cfb685ae.mov


## Setting up Python env and installing required packages

To run Python codes provided in this repository, create a Python environment:
```
$ conda create -p /path_to_env/env_name python=3.x
```
and install the follwoing packages
```
$ conda install -p /path_to_env/env_name/ -c anaconda numpy
$ conda install -p /path_to_env/env_name/ -c conda-forge matplotlib
$ conda install -p /path_to_env/env_name/ -c conda-forge nibabel
$ conda install -p /path_to_env/env_name/ -c anaconda h5py
$ conda install -p /path_to_env/env_name/ -c conda-forge tqdm
$ conda install -p /path_to_env/env_name/ -c conda-forge argparse
$ conda install -p /path_to_env/env_name/ pytorch torchvision torchaudio cudatoolkit=x.x -c pytorch 
```
where ``` cudatoolkit=x.x``` in the last command depends on the installed cude version, e. g. 10.2 or 11.3. After these activate your environment using:
```
$ conda activate /path_to_env/env_name
```
## Training and Testing the 1D-qDL network
