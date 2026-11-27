基于表面肌电信号的手势识别研究

项目名称：基于表面肌电信号的手势识别（ Surface EMG-based Hand Gesture Recognition）

一、项目简介
本项目基于公开表面肌电（Surface Electromyography, sEMG）数据集，利用Python开展肌电信号处理与手势识别研究。通过对原始肌电信号进行预处理、特征提取和机器学习建模，实现不同手部动作的自动分类。
项目旨在熟悉生物电信号处理的基本方法，探索机器学习在肌电信号识别及智能仿生手控制领域的应用。

二、数据集
本项目使用 UCI Machine Learning Repository 提供的 EMG Data for Gestures 公开数据集。
该数据集采集了36名受试者在完成不同手部动作时的表面肌电信号，使用MYO肌电臂环记录前臂8个通道的肌电活动，并提供相应的时间戳和动作类别标签，可用于肌电信号处理与手势识别研究。

三、技术路线
本项目计划分为以下几个阶段：
1. 数据集读取
2. 肌电信号预处理与滤波
3. 滑动窗口分段
4. 时域特征提取
5. 训练集、验证集与测试集划分
6. 机器学习模型训练
7. 模型性能评价与结果分析

四、主要技术与工具
- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

五、模型与评价方法
使用以下模型开展对比实验：
- Support Vector Machine (SVM)
- Random Forest

主要评价指标：
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

六、项目目录
```text
EMG-Hand-Gesture-Recognition/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── results/
│   ├── figures/
│   └── models/
├── reports/
├── README.md
└── requirements.txt
```

七、项目状态
目前项目处于开发阶段，正在逐步完成数据处理、特征提取和机器学习分类等工作。
后续将持续更新代码、实验结果及相关分析。

