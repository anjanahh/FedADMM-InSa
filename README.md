<h1 align="center">FedADMM-InSa: An Inexact and Self-Adaptive ADMM for Federated Learning</h1>

<h4 align="center"><a href="https://sites.google.com/view/ycsong-math">Yongcun Song</a>, <a href="https://iziqi.github.io/">Ziqi Wang</a>, and <a href="https://dcn.nat.fau.eu/enrique-zuazua/">Enrique Zuazua</a></h4>

<p align="center">
  <a href="https://doi.org/10.1016/j.neunet.2024.106772">
    <img src="https://img.shields.io/badge/DOI-10.1016%2Fj.neunet-blue" alt="Read the paper"/>
  </a>
  <a href="https://arxiv.org/abs/2402.13989">
    <img src="https://img.shields.io/badge/arXiv-2402.13989-b31b1b?logo=arxiv" alt="Read on arXiv"/>
  </a>
</p>

## Overview

This repository implements **FedADMM-InSa**, an inexact and self-adaptive ADMM method for federated learning. The training pipeline supports FedADMM-InSa and related federated optimization baselines. 

## Usage

Run a single FedADMM-InSa experiment using the YAML configuration:

```bash
python main.py --cfg utils/config.yaml
```

You can also override configuration values from the command line.

## Citation

If this code is useful for your research, please cite the paper:

```bibtex
@article{swz2025fedadmminsa,
title = {FedADMM-InSa: An inexact and self-adaptive ADMM for federated learning},
journal = {Neural Networks},
volume = {181},
pages = {106772},
year = {2025},
issn = {0893-6080},
author = {Yongcun Song and Ziqi Wang and Enrique Zuazua}
}
```

## Acknowledgments

Alphabetical authorship according to mathematical tradition. Funded by the European Union's Horizon Europe MSCA project [ModConFlex](https://modconflex.uni-wuppertal.de/en/) (grant number 101073558)

<img src="utils/logos/logo_ModConFlex.jpg" alt="ModConFlex" height="63"/> <img src="utils/logos/logo_EU.png" alt="Funded by the EU" height="64"/>
