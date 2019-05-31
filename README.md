# Quora问题是否真诚分类预测
这次Quora的文本分类题，4000支参赛队伍中个人solo最终只在LB上达到了20%，一方面是因为第一次参加NLP方面的比赛，完全是个小白，另一方面是自己在比赛途中也有不少懈怠，因此想做一些技术上以及客观上的总结警醒自己。

比赛是通过文本训练集来预测Quora上的问题是真诚的还是不真诚的问题，比赛链接https://www.kaggle.com/c/quora-insincere-questions-classification

## 关于技术上的问题：
在比赛中通过学习各路大神的kernel，同时在很多问题一知半解的情况下，查阅各种文献资料，我对NLP的文本分类有了一个大致的了解，分词，语言模型，词向量等有了初步认识。语言模型n-gram，预训练词向量word embedding，以及常用的lstm网络和GRU网络等等。文本预处理的各种方法，以及attention layer等模型方案。

## 客观上存在的问题：
NLP的比赛和普通的数据挖掘比赛有很大的不同，普通的数据挖掘比赛最重要的需要挖掘到好的特征，其次是使用合适的模型；而NLP更注重模型本身，所以现有的模型中，深度学习的模型在NLP里得到广泛应用。我自己在这个比赛途中同时也在进行另外一个数据挖掘的比赛，一心二用导致了自己不够专注。做到一定程度的时候卡在一个地方，就发生了懈怠情绪，这也是需要自己改正的一个地方。

## 感悟与收获：
最重要的收获是感觉自己NLP终于入了门，同时了解了各种前沿的论文对于NLP建模的影响，需要阅读更多的论文，因为基本上好的nlp模型都是从现有论文中衍生的（当然很多大神是通过比赛验证自己的模型然后再发Paper），这和从数据中衍生的数据挖掘出的特征真的是有很大的区别。同时这次比赛借鉴了很多别人的方案，在以后更需要做的是站在巨人的肩膀上做出自己的一些想法。在这次比赛后，发现nlp真是一个巨大无比的坑，还有太多需要学习的地方，继续加油，保持危机感。
[Quora Insincere Questions Classification 总结与心得感想](https://blog.csdn.net/yyhhlancelot/article/details/87262813)

## 我的NLP学习笔记：
[NLP学习笔记(一) : 数据预处理（关键词：词袋，简单）](https://blog.csdn.net/yyhhlancelot/article/details/85162557)
[NLP学习笔记（二）：创建特征及训练（关键词：词袋，TFIDF）](https://blog.csdn.net/yyhhlancelot/article/details/85165248)
[NLP学习笔记（三）：模型训练之深度学习方案详解（关键词：深度学习，词向量，RNN，LSTM）](https://blog.csdn.net/yyhhlancelot/article/details/85229665)
[NLP学习笔记（四）：关于keras的Input层与embedding层全解析](https://blog.csdn.net/yyhhlancelot/article/details/86534793)
