# MUSANALYSIS DATASETS

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

This repository contains tokenized datasets generated with [Musanalysis]() library to train DL sequence models.

The data is organized as follows:

````
📦musanalysis_datasets
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

- [LMD Clean](lmd_clean/)<br/>

Other datasets that could be included in the future:

- [MetaMIDI](metamidi/)<br/>


## License

This project is licensed under the terms of the [AGPL v3 license](LICENSE).


## Install

To download the data just clone this repository:

````
git clone git@github.com:carlosholivan musanalysis_data.git

cd musanalysis_data
````

To install Musanalysis, follow the instructions here: [musanalysis docs]()

