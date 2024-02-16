# Drilling Fluid Loss

## Introduction

This repository supports the research presented in `Hyperparameter optimization and interpretation of circulation loss prediction model in drilling`,focusing on enhancing predictive models for circulation loss in drilling operations.
Circulation loss poses significant operational and cost challenges in drilling engineering.Through meticulous hyperparameter optimization and model interpretation, our work aims to improve the predictability of such losses, thereby aiding in the mitigation of their impacts on drilling efficiency and costs. The repository contains all the essential data and visualizations used in our study.

## Project Structure

This project includes the following main files and directories:

- `data/`

  - `raw_data.csv`: The initial dataset before any processing or analysis.
  - `optuna/`: Contains the results of the optimization process for various models. This directory is crucial for understanding the performance and tuning of models under different conditions.
  - `sampling/`: This directory holds datasets that have been split and balanced post-processing. It's essential for ensuring that the models are trained on balanced data to avoid biases.
  - `statistics/`: This directory is dedicated to statistical reports and analyses, providing insights into the data and the effectiveness of different models.
    - `data_analysis_report.html`: An HTML report of the data analysis, offering an accessible and visual way to understand the data's characteristics and the preliminary findings.
    - `data_analysis_report.json`: A JSON version of the data analysis report, which can be useful for automated processing or further analysis in other software.
- `figure/`

  Within this directory, you'll find various plots that visualize the training process for different models and conditions. These visualizations can help in identifying the best-performing models and understanding their behavior under various parameters.

## Contact Information

- Main Contributor: Hengfeng Li
- Email: [mitroe813@gmail.com](mailto:mitroe813@gmail.com)
