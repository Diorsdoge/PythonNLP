| 语言处理任务 | NLTK模块 | 功能描述 |      
| ------------- | ------------- | ----- |       
| 获取和处理语料库 | nltk.corpus | 语料库和词典的标准化接口 |
| 字符串处理 | nltk.tokenize, nltk.stem | 分词，句子分解提取主干 |
| 搭配发现 | nltk.collocations | t-检验，卡方，点互信息PMI |
| 词性标识符 | nltk.tag | n-gram, backoff, Brill, HMM, TnT |
| 分类 | nltk.classify, nltk.cluster | 决策树，最大熵，贝叶斯，EM，k-means |
| 分块 | nltk.chunk | 正则表达式，n-gram，命名实体|
| 解析 | nltk.parse | 图表，基于特征，一致性，概率，依赖 |
| 语义解释 | nltk.sem, nltk.inference | λ演算，一阶逻辑，模型检验 |
| 指标评测 | nltk.metrics | 精度，召回率，协议系数 |
| 概率与估计 | nltk.probability | 频率分布，平滑概率分布 |
| 应用 | nltk.app nltk.chat | 图形化的关键词排序，分析器，WordNet查看器，聊天机器人 |
| 语言学领域的工作 | nltk.toolbox | 处理SIL工具箱格式的数据 |

- 一个**标识符**是表示一个我们想要放在一组对待的字符序列，len(text)
- 一个**词类型**是指一个词在一个文本中独一无二的出现形式或者拼写，len(set(text))
- **词汇多样性**就是平均每个词在文中出现的次数，len(text)/ len(set(text))