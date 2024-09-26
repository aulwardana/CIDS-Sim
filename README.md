# CIDS-Sim

Simulator for Collaborative Intrusion Detection System based on Federated Learning

## Description

Lorem Ipsum

## Setup

This simulator was developed and tested on the Ubuntu operating system. Therefore, we recommend using this operating system for the best results. We also suggest utilizing a package and environment management system. For this simulator, we recommend using Miniconda.

However, if you prefer not to use a package and environment management system, you can skip the "Miniconda installation" and "prepare environment using Miniconda" sections.

### Miniconda Instalation

Create folder to download miniconda installation

```bash
mkdir -p ~/miniconda3
```

Download miniconda installation

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
```

Run miniconda installation

```bash
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
```

Remove miniconda instalation folder

```bash
rm -rf ~/miniconda3/miniconda.sh
```

Load miniconda

```bash
~/miniconda3/bin/conda init bash
```

```bash
~/miniconda3/bin/conda init zsh
```

After that, close the terminal and open again, then you can continue to "Prepare Environment using Miniconda" part.

### Prepare Environment using Miniconda

Create environment with python 3.12 and install libraries

```bash
conda create --name cids_env python=3.10
```

Then activate the environment

```bash
conda activate acm_env
```

After that, install jupyter notebook

```bash
conda install notebook
```

### Install Requirements

Run this command to installs all the packages for simmulator needs.

```bash
pip install -r requirements.txt
```

After all the setup done, you can open "src" folder for the next instruction.

## Development Tool

This simulator is develop using Python programming language with Jupyter Notebook as code editor.