# 数据科学研讨会记录（信息系统组）

### 2018-9-28
| Title                                    | Detail                                   | Author    | link |
| ---------------------------------------- | ---------------------------------------- | --------- | --------- |
| Question Difficulty Prediction for READING Problems in Standard Tests | 构造了TACNN框架来评估英语阅读问题难度，将文章、问题、选项作为特征输入，预测每个问题的难度系数 | Zhurenyu | [ppt](https://github.com/ECNUdase/Seminar-Materials/blob/master/2018-2019/Learning%20from%20Semi-Supervised%20Weak-Label%20Data.pptx?raw=true) |

### 2018-9-21
| Title                                    | Detail                                   | Author    | link |
| ---------------------------------------- | ---------------------------------------- | --------- | --------- |
| Learning from Semi-Supervised Weak-Label Data                   | 半监督弱标签下的多标签分类算法(数据集只有少部分标注，大部分未标注；数据标注的准确性无法保证)  | Fuyingnan | [ppt](https://github.com/ECNUdase/Seminar-Materials/blob/master/2018-2019/Learning%20from%20Semi-Supervised%20Weak-Label%20Data.pptx?raw=true) |

### 2018-3-16
| Title                                    | Detail                                   | Author    |
| ---------------------------------------- | ---------------------------------------- | --------- |
| Why should I trust you                   | 提出了开源工具"Lime"，能够解释样本的预测结果，并且增加模型本身的可解释性  | Fuyingnan |
| Deep Residual Learning for Image Recognition | 提出了更深层次的卷积网络架构——残差网络，解决了传统模型中网络难以训练的问题   | Zhurenyu  |
| A Unified Probabilistic Framework for Name Disambiguation in Digital Library | 将姓名消歧问题formalize成一个隐马尔科夫随机场，并提出了参数估计的两阶段算法；提出了自动确定重名人数的auto K算法 | Lina      |
| JointExtractionofEntitiesandRelations    | 将实体识别和关系提取统一为序列标注问题，使用同一个模型同时进行实体识别和关系提取 | Kuangjun  |

### 2018-3-23
| Title                                    | Detail                     | Author      |
| ---------------------------------------- | -------------------------- | ----------- |
| Mask R-CNN                               | 提出了Mask R-CNN用于图像的实例分割     | yuruonan    |
| Deep Reinforcement Learning for Mention-Ranking | 采用神经网络和强化学习技术增加共指消解的准确率    | chenyuanzhe |
| Question Answering with Subgraph Embeddings | 采用基于子图嵌入的方法，进行问答系统的训练和答案预测 | tanglumin   |
| RNN学习心得                                  | 介绍了RNN相关概念，讲解了梯度消失和权重冲突问题  | yangkang    |

### 2018-3-30
| Title                                    | Detail                                   | Author     |
| ---------------------------------------- | ---------------------------------------- | ---------- |
| Reinforcement Learning for Relation Classification from Noisy Data | 提出一个新的关系分类模型，由实体选择器和关系分类器构成，能够在“Sentence Level”提取关系。将实体选择问题转换成强化学习问题。 | GuHang     |
| Pix2code: Generating Code from a Graphical User Interface Screenshot | 使用CNN和RNN的联合模型，将网页的UI图转化为对应的HTML代码       | E Shen     |
| JAVA GC机制                                | 讲解了java的内存分配机制和垃圾回收机制                    | YinJiaLing |

### 2018-4-13
| Title                                    | Detail                                   | Author     |
| ---------------------------------------- | ---------------------------------------- | ---------- |
| Convolutional Sequence to Sequence Learning | An architecture based entirely on convolutional neural networks for sequence to sequence learning(such as NMT) | CuiYiFeng  |
| DeepFM：A Factorization-Machine based Neural Network for CTR Predicti | 回顾了过去的CTR模型，以及介绍了一系列基于深度学习的CTR模型（FNN,PNN,WDL） | ChenLeiHui |
| Aspect Level Sentiment Classification with Deep Memory Network | 介绍了Memory Network，用于情感分析问题               | Void-Yu    |

### 2018-4-20
| Title                                    | Detail                                   | Author    |
| ---------------------------------------- | ---------------------------------------- | --------- |
| Learning Structured Representation for Text Classification via Reinforcement Learning | 使用ID-LSTM + HS-LSTM学习文本结构，并用策略梯度法进行强化学习  | JinLiJiao |
| Human Action Adverb Recognition: ADHA Dataset And A Three-stream Hybrid Model | 贡献了一个数据集：x为人类动作的视频流序列，y为动作对应的副词。   例如识别接吻的视频是“甜蜜地”，"激动地"，“绅士地” ... | SunChen   |

### 2018-5-4

| Title                                    | Detail                                  | Author    |
| ---------------------------------------- | --------------------------------------- | --------- |
| Deep Forest: Towards An Alternative to Deep Neural Network | 周志华提出的gcForest多粒度级联森林                   | FuYingNan |
| Structure Regularized Neural Network  for Entity Relation Classification for Chinese Literature Text | 利用结构正则化简化句法结构，进行关系提取                    | KuangJun  |
| Ranking-Based Name Matching for Author Disambiguation in Bibliographic Data | KDD Cup 2013第二名，使用基于字符串和元路径的相似度进行作者姓名消歧 | LiNa      |

### 2018-5-18

| Title                                    | Detail                                   | Author      |
| ---------------------------------------- | ---------------------------------------- | ----------- |
| Modeling Mention, Context and Entity with Neural Networks for Entity Disambiguation | 2015年实体消岐的最优模型，采用神经网络，使用了Embedding，卷积，神经张量网络等结构。 | ChenYuanZhe |
| 解析HashTable，HashMap，ConcurrentHashMap    | 讨论了java中该三种结构的特点，主要从多线程安全性、性能等方面考虑       | YinJiaLing  |

###  2018-6-8
| Title                                    | Detail                                   | Author     |
| ---------------------------------------- | ---------------------------------------- | ---------- |
| Study about word embedding on sentiment subspace | 研究词向量中用于表达情感的向量子空间，目的是提高情感分类任务效果	| Void-Yu    |

###  2018-6-15
| Title                                    | Detail                                   | Author     |
| ---------------------------------------- | ---------------------------------------- | ---------- |
| R-FCN: Object Detection via Region-based Fully Convolutional Networks | 目标检测网络。效果不比之前的RCNN，Fast-RCNN差，但是速度更快了。   | God E      |
| BiNE: Bipartite Network Embedding        | 在二分图中采用了表示学习的方法，将节点embedding成向量，通过向量距离来度量节点的相似性。 训练过程类似Word2vec，使用了负采样，负样本的采样分布使用了LSH来代替频率 | ChenLeiHui |


