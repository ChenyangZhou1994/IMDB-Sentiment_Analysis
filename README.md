# IMDB-Sentiment_Analysis #
## 项目名称：IMDB电影评论的情感分析 ##
## 项目描述： ##
首先下载IMDB数据集,数据集共有25000项,正负面评价各为12500项,本项目使用keras(with TensorFlow)处理,建立token字典,字典大小2000词,使用token将“影评文字”转换为“数字列表”,截长补短让所有“数字列表”长度都是200,用Embedding层将“数字列表”转换为“向量列表”,再将“向量列表”送到MLP,RNN,LSTM中,都经过10轮的训练后,准确率分别为为81.36%,81.13%,85.97%,LSTM对于情感分析的准确率较高于RNN。


## 运行环境 ##
Ubuntu 16.04,Keras(with TensorFlow)

Keras=2.2.2

TensooFlow=1.10.0

numpy=1.14.5


本项目是在Jupyter Notebook上完成,运行Keras_Imdb.ipynb 下载数据集，然后就可以分别运行另外三个文件了。

