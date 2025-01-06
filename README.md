# Curling Trajectory Dataset for Training CasLSTM Algorithm

This repository contains a dataset of curling trajectories, which is used for training the CasLSTM algorithm.

## Dataset Overview

The dataset consists of 5000 individual trajectories, with each trajectory represented as a CSV file. Each file contains 5 columns, which represent the following attributes:

- **x-position**: The position along the x-axis of the trajectory.
- **y-position**: The position along the y-axis of the trajectory.
- **x-velocity**: The velocity along the x-axis.
- **y-velocity**: The velocity along the y-axis.
- **angular velocity**: The angular velocity of the curling stone.

### Coordinate System

All trajectories in this dataset have undergone coordinate transformation to unify the coordinate system. This ensures consistency across all data points for effective algorithm training and evaluation.

## Usage

This dataset is primarily intended for training and evaluating the CasLSTM algorithm, designed to predict curling trajectories based on the provided features.

## Files

Each CSV file in the dataset corresponds to one individual trajectory. The files are named according to the trajectory index, and the contents of each file follow the structure outlined above.
