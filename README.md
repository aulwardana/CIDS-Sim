# CIDS-Sim

Simulator for Collaborative Intrusion Detection System based on Federated Learning

## Description

Coordinated cyber-attacks can affect multiple networks simultaneously, making detection challenging as signs of suspicious activity are distributed across different network domains. Detection becomes even more difficult when individual intrusion detection systems (IDS) monitor only a small part of the Internet. To effectively identify these attacks, sophisticated systems are required for real-time detection, as they often involve traffic from a common source or target the same destination. Collaborative intrusion detection systems (CIDS) are effective in detecting such attacks by gathering and analyzing data from multiple networks, allowing for early detection before significant damage occurs.

## Setup

This simulator was developed and tested on the Ubuntu operating system. Therefore, we recommend using this operating system for the best results. If you want to used other operating system you can used linux based, Mac OS, o Windows Subsystem for Linux (WSL) on Windows OS.  

We also suggest utilizing a package and environment management system. For this simulator, we recommend using Miniconda.

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

To develop the simulator, a server with specific technical specifications was utilized: a 2.3 GHz 16-Core Intel(R) Xeon(R) CPU E5-2650 v3 processor coupled with 128 GB of RAM.