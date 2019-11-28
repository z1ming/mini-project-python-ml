## 项目2：波士顿房价预测

### 准备工作

这个项目需要安装 **Python3** 和以下的 Python 函数库：

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

需要安装一个软件，以运行和编辑 [.ipynb](http://jupyter.org/) 文件。

推荐安装 [Anaconda](https://www.continuum.io/downloads)，这是一个常用的 Python 集成编译环境，且已包含了本项目中所需的全部函数库。

### 代码

代码在 `boston_housing.ipynb` 文件中给出。

### 运行

在终端或命令行窗口中，选定 `boston_housing/` 的目录下（包含此README文件），运行下方的命令：

```jupyter notebook boston_housing.ipynb```

这样就能够启动 Jupyter notebook 软件，并在浏览器中打开文件。

### 数据

经过编辑的波士顿房价数据集有490个数据点，每个点有三个特征。

**特征**

1. `RM`: 住宅平均房间数量
2. `LSTAT`: 区域中被认为是低收入阶层的比率
3. `PTRATIO`: 镇上学生与教师数量比例

**目标变量**

`MEDV`: 房屋的中值价格