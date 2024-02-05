# Drilling Fluid Loss

## 简介

Drilling Fluid Loss项目旨在通过数据分析和机器学习方法来预测和分析钻井过程中的液体损失。本项目包含了一系列的数据集、模型训练脚本以及结果分析，旨在为石油钻探领域的研究者和工程师提供有价值的参考和工具。

### 环境设置

**方法：**

为了隔离项目依赖，建议建立新的Conda环境。您可以通过以下命令来创建和激活新的环境（将 `<你的环境名称>` 替换为您的环境名，例如 `drill`）:

```bash
conda env remove -n drill
conda create -n drill python=3.9
conda activate drill
```

接下来，安装所需的依赖：

```bash
pip install -r requirements.txt
```

## 项目结构

本项目包括以下主要文件和目录：

- `data/`：包含原始数据集和预处理后的数据，以及数据分析报告。
- `figure/`：存放训练过程和结果分析中生成的图表和可视化结果。
- `optuna/`：包含使用Optuna进行的参数优化研究的数据库文件。

详细目录结构如下：

```
data/
    data_analysis_report.html
    data_analysis_report.json
    failure_predic.csv
    optuna/
        Complete50/
            optuna_studies.db
        Partial2647/
            optuna_studies.db
        ...
sampling/
    Complete50.csv
    Partial2647.csv
    ...
figure/
    paper/
        BestStudyWithData.pdf
        chordal.pdf
        ...
    train_optuna/
        Complete50/
            AdaBoostClassifier_12cv_20trial_contour.pdf
            ...
        Partial2647/
            ...
```

## 联系方式

- 主要贡献者：Hengfeng Li
- 电子邮件：[mitroe813@gmail.com](mailto:mitroe813@gmail.com)

## 致谢

我们感谢所有参与此项目的贡献者和支持者。您的努力和支持使得这项研究得以进行，并为钻井领域的科学发展做出了贡献。

