
[机器学习路线图](https://github.com/clone95/Virgilio)
以下是解读：

作者首先强烈推荐了《Scikit-Learn 与 TensorFlow 机器学习实用指南》一书。之外，他还上传了全球顶尖大学和开源组织的学习资源，并收集了理论和示例，以及对选择最佳资源的建议。

内容主要分为四大部分：

##### 一、先决条件
* Python
* Jupyter Notebook
* 需要掌握的基本数学知识
* 机器学习全貌

##### 二、使如何使用 Scikit-Learn 进行机器学习
* 为什么是 Scikit-Learn？
* 端到端机器学习项目
* 线性回归
* 分类
* 训练模型
* 支持向量机
* 决策树
* 合奏学习和随机森林
* 无监督学习
* 结语和期待

##### 三、通过 TensorFlow 训练的神经网络

* 为何选择 TensorFlow？
* 使用 TensorFlow
* ANN - 人工神经网络
* CNN - 卷积神经网络
* RNN - 递归神经网络
* 训练网络：最佳实践
* 自动编码
* 强化学习

##### 四、工具

* 机器学习项目
* 数据科学工具
* 博客 / YouTube 频道 / 网站

每个标签下，作者都有详细的解释并给出了实战操作的资源，实乃良心之作！下面，就由营长来详细介绍下这个项目里有哪些值得一看的资源（并附上部分教程链接）。
**一、先决条件**
    **Python**
基础知识：https://pythonprogramming.net/introduction-learn-python-3-tutorials/

作者还建议，除了对 Python 熟悉掌握外，还可以了解下 Numpy，它是数学运算的重要模块，可以有助于你在后面 Python 环境中导入 Tensor 数据类型。

Python3 安装地址：https://realpython.com/installing-python/

PyCharm Community Edition（一个用于 Python 开发的完整 IDE，为实验设置一个新的 Python 虚拟环境）

安装地址：https://www.jetbrains.com/pycharm/download/#section=windows

   **Jupyter Notebook**

是一个开源的 Web 应用程序，帮助用户创建和共享文档，包括 live code，方程，可视化，叙述文本。例如，数据清洗、数值模拟、统计建模、数据可视化、机器学习等。

   **需要掌握的基本数学知识**

在作者看来，数学是机器学习背后的重要基础。但重要的是，掌握主要概念并认识到这些数学方法的应用领域和局限性。
他给出了三个课程链接，分别是：

线性代数：https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/

概率基础和统计：https://www.edx.org/course/introduction-to-probability-0

其他数学资源：https://explained.ai/matrix-calculus/index.html#sec4.5

   **机器学习全貌**

最后，还要通过一篇科普读物，了解整个机器学习全貌：https://www.oreilly.com/library/view/hands-on-machine-learning/9781491962282/ch01.html

**二、如何使用 Scikit-Learn 进行机器学习？**

   **安装 Scikit-Learn**

python pip install -U scikit-learn

如果安装时遇到一些问题，可能是你更新到最新版本的 pip，所以在同一个文件夹内运行：

python -m pip install --upgrade pip

   **为什么是 Scikit-Learn？**

Scikit-Learn 是机器学习任务中最完整、最成熟，且记录完整的库之一。它开箱即用，具有强大而先进的模型。

   **端到端机器学习项目**

Kaggle，作为机器学习和通用数据科学项目的首选平台，它提供了大量免费数据集，以及有趣的挑战和 ML 模型实验。

   **线性回归**

线性回归是最简单的机器学习形式，也是模型训练的起点。

可以参看吴恩达的理论课程：https://www.youtube.com/watch?v=W46UTQ_JDPk&list=PLoR5VjrKytrCv-Vxnhp5UyS1UjZsXP0Kj&index=2

  ** 分类**

如果想要从不同的可能性中预测结果，分类则是最重要的机器学习任务之一。最简单的情况是二元分类问题。

   **训练模型**

作者列举了 ML 任务中训练模型的一些技术，在 Google Crash 教程中可以找到：

梯度下降：https://developers.google.com/machine-learning/crash-course/reducing-loss/gradient-descent

学习率：https://developers.google.com/machine-learning/crash-course/reducing-loss/learning-rate

SGD：https://developers.google.com/machine-learning/crash-course/reducing-loss/stochastic-gradient-descent
正则化：https://www.youtube.com/watch?v=Q81RR3yKn30

   **支持向量机**
是创建 ML 模型的另一种经典算法。
除了理论解释外，还有更多实战策略：
https://www.youtube.com/watch?v=g8D5YL6cOSE

   **决策树**

   **集成学习和随机森林** 集成学习（Ensemble Learning）的思路是利用了几款 ML 模型的所有不同特征、优劣势，以期得到最有可能性的预测结果。
集成学习基础知识：
https://www.youtube.com/watch?v=9VmKYwX_U7s
随机森林最经典实践：
https://www.youtube.com/watch?v=3kYujfDgmNk

   **无监督学习** 涵盖了无监督学习的介绍、解释，以及与监督学习、强化学习之间的差别。

关于涉及的两个重要技术：关联规则（Association Rules）和聚类，作者分别提供了示例和教程。

**三、通过 TensorFlow 训练的神经网络**

在本节中，作者主力推荐斯坦福大学深度学习课程以及其他网络教程，帮助学习者快速了解这些内容。其中包括 ANN、CNN、RNN 等不同种类的机器学习模型。实际上，作者花了很长时间去理解神经网络的理论和应用，包括阅读博客、官网论坛、学习路径。

他给出了“三步走”的建议：
   通过斯坦福大学教程了解神经网络的主要概念，不要过多担心一些数学解释，而要关注什么和为什么；
   使用理论 + 教程 + 示例（如 RNN 理论 + RNN 教程 + RNN 示例），每次只深度探讨一个主题；
   每探讨完一个主题，就回溯一遍斯坦福大学的课程。这种方式将帮助你完全理解所有公式，并将课程中提到的 “数学” 相关知识联系起来，触类旁通。

作者表示，以上这种方式可根据需要重复多次，然后在你的头脑中构建一个良好的通用模型。斯坦福大学课程 PPT 地址：http://cs231n.stanford.edu/slides/2018/

**为何选择 TensorFlow？**

目前，TensorFlow 已经企业里实现机器学习算法的事实标准。在安装 TensorFlow 库之前，你只需在 Python 安装文件夹中打开一个终端并运行此命令：
```
pip install tensorflow
```
* ANN - 人工神经网络
* CNN - 卷积神经网络
* RNN - 递归神经网络
* 训练网络：最佳实践
* 自动编码
* 强化学习

以上细节就不一一细讲了。
##### 四、其他资源
除了上述内容之外，作者还收集了大量文章、网络应用程序、最佳实践、项目和存储库。
* 机器学习项目
* 工具
* YouTube 频道
* 博客以及，其他值得一看的网站

作者最后表示，将在接下来的时间里对不同的主题进行扩充，包括：无监督学习、机器学习心态框架（如何像数据科学家一样思考）、使用 Pandas 进行数据处理和准备、特征选择、特色工程、扩展参数优化部分、Keras 库、TensorFlow 2.0、如何在 AWS、Azure 上部署模型等。