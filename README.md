# Stochastic Process Modeling and Prediction with WaveNet

## Introduction

This project explores the simulation and prediction of stochastic processes using WaveNet, a convolutional neural network originally designed for audio generation. Traditional methods for modeling these processes, such as parametric statistical models (e.g., ARIMA, GARCH) or Monte Carlo methods, often require detailed assumptions about the system's structure and distribution. These constraints limit their ability to capture complex dynamics, especially in nonlinear systems or those influenced by unknown factors.

WaveNet, as a non-parametric model, offers the capability to identify patterns and fluctuations in time-series data, simplifying modeling while expanding its potential applications. Unlike the original paper that focuses on both simulation and prediction, this study emphasizes prediction performance. Specifically, we test WaveNet's ability to handle stochastic processes with higher randomness, such as the Geometric Brownian Motion (GBM) and Mean-Reverting Process.

## Objectives

- Evaluate WaveNet's predictive performance on high-randomness stochastic processes.
- Compare its efficiency and accuracy against traditional parametric methods.
- Test the model's ability to overcome the limitations of conventional stochastic modeling.

## Methods

1. **Process Selection**: Focus on Geometric Brownian Motion and Mean-Reverting Process to evaluate WaveNet under challenging conditions.
2. **Model Architecture**: Leverage WaveNet to capture non-linear and complex dynamics in time-series data.
3. **Evaluation Metrics**: Use predictive accuracy and error analysis to assess model performance.

## Results

The results section showcases WaveNet's predictive capabilities and its advantages over traditional methods. Specific metrics and visualizations are included in the notebook to demonstrate its performance.

## Repository Contents

- `Tabajo_Final_Estocasticos_2.ipynb`: The main notebook containing the implementation, analysis, and results.
- **Data**: Simulated datasets for the selected stochastic processes (included in the notebook).
- **Models**: WaveNet architecture and training scripts.
- **Visualization**: Plots and analysis of predictive performance.
