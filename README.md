# Greenhouse-Strawberry-Bee Simulation
<p align="center" width="80%">
<img src="fig/logo2.png" style="width: 80%; min-width: 300px; display: block; margin: auto;">
</p>


[![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](https://github.com/HUANGLIZI/ChatDoctor/blob/main/LICENSE) 



## 1. Basic model

This repository in file [Greenhouse_Strawberry_Bee_Simulation](https://github.com/czh16/Greenhouse_Strawberry_Bee_Simulation) contains the code and hyperparameters for the paper:

[Cao, Zhihao, et al. "Effects of bee density and hive distribution on pollination efficiency for greenhouse strawberries: A simulation study." *Agronomy* 13.3 (2023): 731.](https://www.mdpi.com/2073-4395/13/3/731)

The project is based on [GAMA simulation platform](https://github.com/gama-platform) and the version is GAMA1.8.

<p align="center" width="80%">
<img src="fig/interface.png" style="width: 80%; min-width: 300px; display: block; margin: auto;">
</p>

### 1.1 Simulation Experiments

The project provides three experiments:

**Monitor:** This experiment is the fastest in simulation speed as it contains no GUI interface except a result monitor.

**GUI:** This experiment provide a interactive and visual GUI in the simulation process, including the greenhouse, every strawberry plant and every bee.

**Repetition:** This experiment will repeat the simulation for several times, designed for statistical analysis, such as ANOVA analysis and so on.

### 1.1 Simulation Parameters

<p align="left" width="10%">
<img src="fig/parameters.png" style="width: 30%; min-width: 50px; display: block; margin: auto;">
</p>
Documents are here [Simulation documents](documents.pdf).
