# MYTH Assignment

This repository contains an implementation of sketch generation using diffusion models, inspired by ChiroDiff. The project demonstrates how to generate realistic sketch drawings for categories like "cat", "bus", and "rabbit" from the QuickDraw dataset using a hybrid approach combining Bidirectional RNNs and Diffusion Models.

## Overview

The main implementation is provided in the Jupyter notebook [technical_assignment.ipynb](technical_assignment.ipynb), which covers:
- Dataset preparation and visualization
- Bidirectional RNN architecture for capturing temporal dependencies in drawing sequences
- Diffusion model training and inference
- Quantitative evaluation using FID and KID metrics
- Animation generation showing the drawing process

**Note**: This notebook was originally designed to run on Google Colab but can also be executed locally.

## Installation

Installing with UV:

```
uv sync
```

Installing with PIP:

```
pip install .
```

## Generated animations

### Cat

![cat drawing animation](outputs/cat/cat_drawing_animation.gif)

### Bus

![bus drawing animation](outputs/bus/bus_drawing_animation.gif)

### Rabbit

![rabbit drawing animation](outputs/rabbit/rabbit_drawing_animation.gif)

## Generated images

### Cat

![cat 1](outputs/cat/cat_1.png)
![cat 2](outputs/cat/cat_2.png)
![cat 3](outputs/cat/cat_3.png)
![cat 4](outputs/cat/cat_4.png)

### Bus

![bus 1](outputs/bus/bus_1.png)
![bus 2](outputs/bus/bus_2.png)
![bus 3](outputs/bus/bus_3.png)
![bus 4](outputs/bus/bus_4.png)


### Rabbit

![rabbit 1](outputs/rabbit/rabbit_1.png)
![rabbit 2](outputs/rabbit/rabbit_2.png)
![rabbit 3](outputs/rabbit/rabbit_3.png)
![rabbit 4](outputs/rabbit/rabbit_4.png)


## Evaluation

### Cat:

FID: 20.092737197875977

KID: 0.007985197938978672 ± 1.6307721750763449e-07

### Bus:

FID: 13.001677513122559

KID: 0.002443628152832389 ± 1.4258183966830984e-07

### Rabbit:

FID: 20.462812423706055

KID: 0.006181297358125448 ± 1.435505367908263e-07
