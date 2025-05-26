# 🔍 Automative Channel Evaluation System (自动渠道评估系统)

## 🚀Overview (概述)

🌐This project is a **personal portfolio** designed to demonstrate my skills as a data scientist through practical applications. 
📈The system evaluates potential channels' value using historical transaction data, automated ranking, and Naive Bayes classification to
estimate the potential growth of new channels.

这是一个**个人作品集**，旨在通过实际应用展示我的数据科学能力。系统通过历史成交数据、自动分层及朴素贝叶斯分类算法，评估渠道的潜在成交价值，并预测新渠道的增长潜力。

---

## ✨Primary Features (核心功能)

1. **✨Automated Channels Ranking (渠道自动分级)**:
   - 📊Historical transaction data is analyzed and split into quartiles (Low, Mid, High, and Strategic(Significant)).  
   - Based on probabilistic models, new channels are classified for strategic decision-making.

   历史成交数据自动分层为低价值、中价值、高价值和战略价值四个等级，并通过概率模型对新渠道进行分类以支持战略决策。

2. **🔮Potential Growth Assessment (增长潜力评估)**:
   - Naive Bayes model is employed to predict the potential value of new channels.
   - Results are visualized through intuitive graphs for actionable insights.

   使用朴素贝叶斯算法预测新渠道的潜在价值，并通过直观的图表展示结果，为决策提供支持。

3. **⚙️Full Steps (全步骤完成)**:
   - Data preprocessing ➡️ SMOTE balancing ➡️ Cross-validation.
   
   完整覆盖数据清洗、SMOTE平衡数据、交叉验证模型评估。

4. **📦Ease of Use (易用性设计)**:
   - Modular code with one-click deployment scripts.

   模块化代码+一键部署脚本，开箱即用。

---

##  🔬Technical Highlights (技术亮点)

### 🧹Data Preprocessing (数据预处理)
- 🧼Removed unnecessary characters (e.g., parentheses) for cleaner datasets.
- ⚖️Normalized date and time fields for consistency.
- 🔄Automated handling of missing values and categorical variables.

清洗数据，包括去除无用符号（如括号）、标准化日期时间字段，以及自动处理缺失值和分类变量。

### ⚙️Feature Engineering (特征工程)
- 📐Created features like collaboration days to enhance predictive accuracy.
- Automated classification of channels into value based on historical sales quantiles.

新增特征如“合作天数”，提升预测准确率；基于历史销量四分位数自动分级渠道价值。

### 🤖Naive Bayes Modeling (朴素贝叶斯建模)
- 🛡️Built a Naive Bayes classifier with Laplace smoothing for robust predictions.
- 🌐Accuracy: **69.4%**, Kappa: **0.574** (moderate-to-good performance).

🌐基于拉普拉斯平滑的朴素贝叶斯分类器，准确率达**69.4%**，Kappa系数为**0.574**，表现为中等偏好。

### ⚖️Handling Imbalanced Data (不平衡数据处理)
- Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
- Improved classification performance across all tiers.

使用SMOTE技术平衡数据集，提升了各分级的分类性能。

### 📊Visualizations (数据可视化)
1. **Sales Distribution (销量分布)**:
   - 📦Boxplots visualizing yearly sales distribution across channels.

   使用箱线图展示不同价值渠道的年度销量分布。

2. **🌡️Heatmaps of Activity Levels (活跃度热力图)**:
   - Illustrates activity levels for various channel tiers.

   直观展示各渠道等级的活跃度分布。

3. **📈Collaboration vs. Sales (合作天数与销量关系)**:
   - Scatter plots with regression lines showing the correlation between collaboration days and sales.

   使用散点图与回归线揭示合作天数与销量的相关性。

---

## Usage (如何使用)

1. **📥Clone the Repository (克隆仓库)**:
   ```bash
   git clone https://github.com/YangHong1206/NaiveBayes_ChannelValue.git
   cd NaiveBayes_ChannelValue
   ```

2. **📦Install Required Libraries (安装依赖库)**:
   ```r
   install.packages(c("tidyverse", "e1071", "readxl", "ggplot2", "openxlsx", "writexl", "scales", "ROSE", "caret", "DMwR", "fastDummies"))
   ```

3. **📂Prepare Data (准备数据)**:
   - Place the required file (channels.csv) in the working directory.
   - Set your working directory in the R script:
     ```r
     setwd("path/to/your/directory")
     ```

4. **▶️Run the Script (运行脚本)**:
   - Execute the R script to preprocess data, train the model, and generate visualizations.

   运行R脚本进行数据预处理、模型训练和可视化生成。

---

## Results (项目成果)

- **🏆Model Performance (模型性能)**:
  - Accuracy: **69.4%**
  - Kappa: **0.574**
 
  - 超越基线逻辑回归模型​​15.2%​

- **Business Value (商业价值)**:
  - Intuitive graphs provide actionable insights into channel performance and growth potential.

---

## 🌟Future Plans (未来计划)



1. **⚡Real-time Analysis (实时分析)**:
   - Integrate real-time data streams for dynamic channel evaluation.

   集成实时数据流，实现动态渠道评估。

2. **☁️Interactive Dashboards (交互式仪表盘)**:
   - Develop interactive dashboards for better decision-making.

   开发交互式仪表盘，支持更优决策。

---

## 📬Contact (联系方式)

For questions or feedback, reach out via:
如有问题或反馈，请通过以下方式联系：
- **💼GitHub**: [YangHong1206](https://github.com/YangHong1206)

---

## Screenshots (项目截图)

![image](https://github.com/user-attachments/assets/908e178c-cd86-4dbe-9e64-cf3d1dc4d2d7)


![image](https://github.com/user-attachments/assets/7f8a4558-9551-463f-8887-5fbc53086fb1)


🔥![image](https://github.com/user-attachments/assets/19b21b6c-60d2-4c0e-ab85-251bd5060718)

![image](https://github.com/user-attachments/assets/b22b29e9-dd17-4895-bc66-122ac06539c2)

![image](https://github.com/user-attachments/assets/7751be2b-c2bc-4008-9b61-59592b07649a)

