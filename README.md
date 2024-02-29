# Drilling Fluid Loss

## Introduction

该存储库支持`井漏预测模型的超参数优化与解释`中提出的研究，重点是增强钻井作业中循环损失的预测模型。
循环损失给钻井工程带来了重大的运营和成本挑战。通过细致的超参数优化和模型解释，我们的工作旨在提高此类损失的可预测性，从而帮助减轻其对钻井效率和成本的影响。 该存储库包含我们研究中使用的所有基本数据和可视化。

## Project Structure

该项目包括以下主要文件和目录：

- `data/`

  - `raw_data.csv`: 任何处理或分析之前的初始数据集。
  - `optimization/`: 包含各种模型的优化过程的结果。 该目录对于理解不同条件下模型的性能和调整至关重要。
  - `sampling/`: 该目录保存经过分割和平衡后处理的数据集。 确保模型接受平衡数据的训练以避免偏差至关重要。
  - `statistics/`: 该目录致力于统计报告和分析，提供对数据和不同模型有效性的见解。
    - `data_analysis_report.html`: 数据分析的 HTML 报告，提供一种易于理解且直观的方式来了解数据的特征和初步结果。
    - `data_analysis_report.json`:JSON版本的数据分析报告，可用于其他软件中的自动化处理或进一步分析。
- `figure/`

在此目录中，您将找到各种图表，这些图表可视化不同模型和条件的训练过程。 这些可视化可以帮助识别性能最佳的模型并了解它们在各种参数下的行为。

## Contact Information
```
- Main Contributor: Hengfeng Li
- Email: [mitroe813@gmail.com](mailto:mitroe813@gmail.com)
```
