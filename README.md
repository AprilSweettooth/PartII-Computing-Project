# Computer Project for Part II computer projects

## This is the repository for computing project submission
### Any issue please contact the author

- [Installation instruction](#installation)
  - [Install JAX:](#install-jax)
  - [Install torch](#install-torch)
  - [Install Reikna](#install-reikna)
- [Running the code](#running-the-code)
- [Repo structure](#repo-structure)
- [Reference](#references-in-the-notebook)


## Installation

To run the original code and redo experiments as instructed, you will need three not-so-common packages in python:

### install JAX


To install a CPU-only version of JAX, which might be useful for doing local
development on a laptop, you can run

```bash
pip install --upgrade pip
pip install --upgrade "jax[cpu]"
```

### install torch

To install a CPU-only version of JAX, which might be useful for doing local
development on a laptop, you can run

```bash
# Python 3.x
pip3 install torch torchvision
```

Or to install on anaconda

```bash
conda install pytorch torchvision -c pytorch
```

### install Reikna

```bash
conda install -c conda-forge reikna
```

## Running the code

    The report is in the format of jupyter notebook and due to large file limit on github, the notebook is split into two parts. 
    The first notebook, Report_PartI.ipynb covers the first section.
    while the second one, Report_PartI.ipynb, covers the remaining parts. 
    The default notebook has the marking style, which means most of the simulation parts are commented out and original experiment will not be rerun. 
    Instead, generated files are shown. To redo the simulation you need to follow the instruction in the cells.

    There are some, however, simple visualization code that needs rendring, which typically takes about average ~10-20s.

    Some file path incompatibility might occur during running the code. 
    It depends on the platforms that you are using. I developed this on my local vscode.
    If something went wrong, please do check the path.

    Also note the link above 'open in vscode' might redirect you to a previous version.
    There are several broken commits (too large to upload) without LFS.
    So it is best not to use it. use https to clone this repo or just 
    download it !

    Enjoy !

## Repo structure


    .
    ├── assets                   # visualization images in notebook 
    ├── demo                     # videos/image of simulation
    ├── exec_time                # time for lenia updates iteration
    ├── flow lenia               # functions for implementing flow lenia 
    ├── generation data          # array of lenia updates iteration 
    ├── QCA                      # semi-quantum functions
    ├── Qdatafiles               # zoo for semi-quantum creature
    ├── utils                    # main helper functions
    ├── zoo                      # zoos of lenia creatures
    ├── Report_PartI             # first part of report
    ├── Report_PartII            # second part of report
    └── README.md


----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## References in the notebook

[1] Chan, Bert Wang-Chak. "Lenia and expanded universe." arXiv preprint arXiv:2005.03742 (2020).

[2] Chan, Bert Wang-Chak. "Lenia-biology of artificial life." arXiv preprint arXiv:1812.05433 (2018).

[3] Plantec, Erwan, et al. "Flow Lenia: Mass conservation for the study of virtual creatures in continuous cellular automata." arXiv preprint arXiv:2212.07906 (2022).

[4] https://google-research.github.io/self-organising-systems/particle-lenia/

[5] Flitney, Adrian P., and Derek Abbott. "A semi-quantum version of the game of life." Advances in Dynamic Games: Applications to Economics, Finance, Optimization, and Stochastic Control (2005): 667-679.

[6] Kawaguchi, Takako, et al. "Introducing asymptotics to the state-updating rule in Lenia." ALIFE 2022: The 2022 Conference on Artificial Life. MIT Press, 2021.

[7] https://automated-discovery.github.io/

[8] Davis, Q. Tyrell, and Josh Bongard. "Glaberish: generalizing the continuously-valued Lenia framework to arbitrary Life-like cellular automata." arXiv preprint arXiv:2205.10463 (2022).
