<br/>
<p align="center">
  <h3 align="center">Audio-Classification-PyTorch</h3>

  <p align="center">
    Classification from Raw Audio, Mel spectrogram features, and STFT Images are done in this repo.
    <br/>
    <br/>
    <a href="https://github.com/mustafaAlgun/Audio-Classification-PyTorch"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/mustafaAlgun/Audio-Classification-PyTorch">View Demo</a>
    .
    <a href="https://github.com/mustafaAlgun/Audio-Classification-PyTorch/issues">Report Bug</a>
    .
    <a href="https://github.com/mustafaAlgun/Audio-Classification-PyTorch/issues">Request Feature</a>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/mustafaAlgun/Audio-Classification-PyTorch?color=dark-green) ![Forks](https://img.shields.io/github/forks/mustafaAlgun/Audio-Classification-PyTorch?style=social) ![Stargazers](https://img.shields.io/github/stars/mustafaAlgun/Audio-Classification-PyTorch?style=social) ![License](https://img.shields.io/github/license/mustafaAlgun/Audio-Classification-PyTorch) 

## Table Of Contents

* [About the Repo](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Authors](#authors)

## About The Repo

![Screen Shot](https://github.com/mustafaAlgun/Audio-Classification-PyTorch/blob/main/General%20Pipeline.png)


In this repo, 

* You will find tow Jupyter Notebook files, one you can use as a step-by-step guide and other is for STFT Transformation from Audio waveforms. Every step is explained thoroughly in the notebooks.

In detail, the performance of three different methods
for music genre classification using the FMA small version
dataset is explored. Firstly, the use of raw audio waveforms
as features for classification is investigated. Secondly, mel
spectrogram features, which are commonly used in music
information retrieval tasks, are used for genre classification.
Finally, the performance of classification using Short-Time
Fourier Transform (STFT) images, which provide a compact
representation of audio signals, is evaluated.
The aim of this study is to compare and evaluate the performance of these three methods for music genre classification
and to provide insights into the most suitable approach for
this task.
The main contributions of this project are:
* A comparative study of three different music genre classification methods: raw audio waveform, mel spectrogram
features, and STFT images.
* A thorough evaluation of the three methods on the FMA
small dataset, comparing the results to previous work in
the literature.
* An analysis of the results and demonstration of the
effectiveness of the proposed methods.

## Getting Started

This Jupyter Notebook was written in Python & Pytorch. You can directly download the notebook and run it locally, or you can upload it on Google Collabs and run there (I recommend GPU usage for faster training time). <br />

To get a local copy up and running follow these simple example steps.



### Installation

Clone the repo

```sh
git clone https://github.com/mustafaAlgun/Audio-Classification-PyTorch.git
```
### Dataset

Dataset can be downloaded from [this repo](https://github.com/mdeff/fma).

## Usage

This is a walk-through Jupyter Notebook. Therefore, following the steps and reading comments will be more than enough for you to replicate the results :) Mind you, you may need to change the paths of files according to where they are in your local machine.


## Roadmap

See the [open issues](https://github.com/mustafaAlgun/Audio-Classification-PyTorch/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/mustafaAlgun/Covid-19-Detection-with-Vision-Transformer/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.

## Authors

* **Mustafa Algun** - *Master's Student at University of Padua*

## Dataset Citation

@inproceedings{fma_dataset,
  title = {{FMA}: A Dataset for Music Analysis},
  author = {Defferrard, Micha\"el and Benzi, Kirell and Vandergheynst, Pierre and Bresson, Xavier},
  booktitle = {18th International Society for Music Information Retrieval Conference (ISMIR)},
  year = {2017},
  archiveprefix = {arXiv},
  eprint = {1612.01840},
  url = {https://arxiv.org/abs/1612.01840},
}
