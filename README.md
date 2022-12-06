# MUSICAIZ DATASETS

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

This repository contains tokenized datasets generated with [musicaiz](https://github.com/carlosholivan/musicaiz) library to train DL sequence models.

The data is organized as follows:

````
📦musicaiz-datasets
 ┣ 📂dataset_name
 ┃ ┗ 📂tokenizer
 ┃   ┗ 📂tokenization_type
 ┃     ┗ 📂train
 ┃     ┃ ┗ 📜token-sequences.txt
 ┃     ┗ 📂validation
 ┃     ┃ ┗ 📜token-sequences.txt
 ┃     ┗ 📂test
 ┃     ┃ ┗ 📜token-sequences.txt
 ┃     ┗ 📜vocabulary.txt
 ┃ ...
````

The current tree contains:

	- dataset_name: jsbchorales, maestro
	- tokenizer: mmm
	- tokenization_type: `4_bars` and `all_bars`


The available datasets are:

- [JSB Chorales](jsb_chorales/)<br/>

- [MAESTRO](maestro/)<br/>

Other datasets that could be included in the future:

- [LMD Clean](lmd_clean/)<br/>

- [Pop909](pop909/)<br/>

- [MetaMIDI](metamidi/)<br/>


## License

This project is licensed under the terms of the [AGPL v3 license](LICENSE).


## Install

To download the data just clone this repository:

````
git clone git@github.com:carlosholivan musicaiz-datasets.git

cd musicaiz-datasets
````

To install musicaiz, clone the repository for the latest changes or simply type `pip install musicaiz`.

[musicaiz repository](https://github.com/carlosholivan/musicaiz)

[musicaiz docs](https://carlosholivan.github.io/musicaiz)

## Cite

If you use any of these datasets in your work, please cite the dataset(s) you use and musicaiz software:

````
@misc{hernandezolivan22musicaiz,
  doi = {10.48550/ARXIV.2209.07974},
  url = {https://arxiv.org/abs/2209.07974},
  author = {Hernandez-Olivan, Carlos and Beltran, Jose R.},
  title = {musicaiz: A Python Library for Symbolic Music Generation, Analysis and Visualization},
  publisher = {arXiv},
  year = {2022},
}
````

## Disclaimer

These datasets are Open Source and the original files belong to their corresponding authors.
If you are an author of any of these datasets and you 

This is a repository that hosts processed open Source datasets to train DL models. Each of these datasets have its corresponding license. It the responsability of the users to determine whether they have permission to use the dataset under the dataset's license.

If you're a dataset author or owner and you do not want your dataset to be included in this repository, please open a GitHub issue and we will remove the dataset from this repository.
