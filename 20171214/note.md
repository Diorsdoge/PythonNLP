## 简单的统计

#### 频率分布
- 使用FreqDist寻找xxx中最常见的50个词
> fdist1 = FreqDist(text1)
vocabulary1 = fdist1.keys()
vocabulary1[:50]

- 使用fdist1.hapaxes()查看低频词

#### 细粒度选择词

- 长度大于XXX，频率出现大于XXX次的词

#### 词语搭配和双连词（bigrams）

- 使用bigrams提取文本词汇中双连词
- 使用collocations()函数提取文章中更频繁出现的双连词

#### 计数其他东西

- 词长的分布

### NLTK频率不分类中定义的函数

 | 例子 | 描述 |          
| ------------- | ------------- |         
| fdist = FreqDist(samples) | 创建包含给定样本的频率分布 |
| fdist.inc(sample) | 增加样本 |
| fdist['monstrous'] | 计数器给定样本出现的次数 |
| fdist.freq('monstrous') | 给定样本的频率 |
| fdist.N() | 样本总数 |
| fdist.keys() | 以频率递减顺序排序的样本链表 |
| for sample in fdist | 以频率递减的顺序遍历样本 |
| fdist.max() | 数值最大的样本 |
| fdist.tabulate() | 绘制频率分布表 |
| fdist.plot() | 绘制频率分布图 |
| fdist.plot(cummulative=True | 绘制累积频率分布图 |
| fdist1 < fdist2 | 测试样本在fdist1中出现的频率是否小于fdist2 |









