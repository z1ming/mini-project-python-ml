## 项目1：学生成绩预测
反向传播（Backpropagation）是深度学习的基础。TensorFlow 或者其它框架会替你把它做好，但是本项目完成了对神经网络的训练过程的实现。具体包括：
- 正向传播算法
- 反向传播算法
- 更新权重

### 准备工作

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [NumPy](http://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)

你还需要安装一个软件[Pycharm](https://www.jetbrains.com/pycharm/)，以运行和编辑`.py`文件。

### 代码

代码已经在 `backprop.py` 文件中给出，还会用到 `data_prep.py` 和名为 `binary.csv` 的数据文件来完成这个项目。

### 运行

在pycharm中，选定 `backpropagation-students-grades/` 的目录下（包含此README文件），打开`backprop.py`文件，点击“运行”即可。

### 数据

经过编辑的学生成绩数据集有400个数据点，每个点有三个特征。

**特征**

1. `gre`: 学生的gre成绩
2. `gpa`: 学生的gpa成绩
3. `rank`: 学生排名

**目标变量**

`admit`: 是否录取，0代表不录取，1代表录取