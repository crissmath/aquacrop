# Tutorial AquaCrop-OSPy

## What is Aquacrop (Explained by Rossana P.()).

## What is the purpouse of use this:
 * Improving Irrigations water efficiency.
 * Agriculture uses more freshwater globally than any other sector.
 * Increse demans on water resourses from all sectors.
 * Need to imprtove irrigation watrer efficience. 

## Introduction to crop-growth models.
 * Crop-growth models are powerful tools which simulate
 * crop growth in response to climate and management practises.
 * Many experiments are too impractical to do in an actual field.
 * Some are designed for usability and others for flexibility
 * Applications include:
 * Prediction of climate change impacts on agricultural yields and crop-water demands,
 * Evaluating irrigation management strategies.

## Introducing AquaCrop-OSPy
    ![AquaCrop-OSPy](figures/aquacrop.png)
 * AquaCrop-OSPy is an open-source python implementation of the FAO AquaCrop model.
 * AquaCrop aims to accurately simulate crop response to water stress
 * ACOSP builds on existing implementations of AquaCrop
 * in Matlab (Foster et al, 2017) and R (Rodriguez and Ober, 2019).
 * Peer reviewed article in Agricultrual Water Management.

## What does this version have over the other:
 * Only basic Python experience required.
 * Flexible adjust model inputs and integrate with other Python modules.
 * Jupyter Notebooks Tutorials.
 * You can use Web browser without the need to localy install.

## Example of use cases: 
 * How to run first Simulation.
 * Optimization of Irrigation sheduling.
    
## First simulation:
### Source code on GitHub: https://github.com/crissmath/aquacrop
* Tutorial 1: Notebook 1.
  * Daily climate measurements (Tmin, Tmax, Precip, ETo).
  * Soil type and profile.
  * Crop type and calendar.
  * Initial water content.
  * Management practices (e.g. irrigation).
  * Run the model for chosen time period.
				
* Tutorial 2: Notebook 2 
  * Optimization of irrigation scheduling.
  * Example of Maize production in Nebraska,USA.
  * Increasingly common to use soil-moisture sensors
  * Determine optimal set of thresholds to maximise profits/yields Subject to maximum seasonal irrigation.

## Install

```bash
pip install aquacrop
```

## Quickstart

The developers of AquaCrop provide a series of tutorials that serve as a starting point to begin with the first simulation:

1.  <a href=https://colab.research.google.com/github/aquacropos/aquacrop/blob/master/docs/notebooks/AquaCrop_OSPy_Notebook_1.ipynb>Running an AquaCrop-OSPy model</a>
2.  <a href=https://colab.research.google.com/github/aquacropos/aquacrop/blob/master/docs/notebooks/AquaCrop_OSPy_Notebook_2.ipynb>Estimation of irrigation water demands</a>
3.  <a href=https://colab.research.google.com/github/aquacropos/aquacrop/blob/master/docs/notebooks/AquaCrop_OSPy_Notebook_3.ipynb>Optimisation of irrigation management strategies</a>
4.  <a href=https://colab.research.google.com/github/aquacropos/aquacrop/blob/master/docs/notebooks/AquaCrop_OSPy_Notebook_4.ipynb>Projection of climate change impacts</a>



# Inspiration and references for this tutorial

- Repository: https://github.com/aquacropos/aquacrop
- Model: https://www.fao.org/aquacrop/resources/tutorials/en/
- pip: https://pypi.org/project/aquacrop/
- Forum: https://github.com/aquacropos/aquacrop/discussions
- Tutorials: https://aquacropos.github.io/aquacrop/
- Video: Intelligent irrigation management using crop models, optimization and machine learning | SciPy 2021

