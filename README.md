# 2021290242-
云计算代码及结果
主代码环境：
Requirements: Ubuntu 16.0.4;
Python 3.6;
Pytorch 1.0.0;
mxnet 1.2.1;
scikit-learn 0.20.1;

Eur-Lex数据集处理代码说明：
Eurlex_data_analysis.ipynb实现了对Eurlex数据集的预处理，统计了所有共同出现过的二元组，以及其频次。最后以.csv文件输出。  
Eurlex_Label2Glove_Embedding.ipynb实现了将Eurlex数据集的每个标签划分为多个单词，继而通过glove embedding提取其语义信息。最后输出每个标签对应的glove embedding。 
