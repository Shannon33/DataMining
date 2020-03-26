# Baseline

## 个人比赛流程分享

### 提交一个基础baseline

### 在baseline基础上优化

### 模型融合

## baseline

### Step 1:导入函数工具箱

### Step 2:数据读取

### Step 3:特征与标签构建（特征工程）

- 提取数值类型特征列名
- 构建训练和测试样本
- 统计标签的基本分布信息
- 缺省值用-1填补

### Step 4:模型训练与预测

- 1) 利用xgb进行五折交叉验证查看模型的参数效果
- 2) 定义xgb和lgb模型函数
- 3)切分数据集(Train,Val)进行模型训练，评价和预测

	- train : validation = 7 : 3
	- train : validation = 4 : 1

- 4)进行两模型的结果加权融合
- 5)输出结果

*XMind: ZEN - Trial Version*