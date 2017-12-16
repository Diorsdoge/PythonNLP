 | 示例 | 描述 |          
| ------------- | ------------- |         
| cfdist = ConditionFreqDist(pairs) | 从配对链表中创建条件频率分布 |
| cfdist.conditions()| 将条件按字母排序 |
| cfdist[condition] | 此条件下的频率分布 |
| cfdist[condition][sample]| 此条件下给定样本的频率 |
| cfdist.tabulate() | 为条件频率分布制表 |
| cfdist.tabulate(samples, conditions) | 指定样本和条件限制下制表 |
| cfdist.plot()| 为条件频率分布绘图 |
| cfdist.plot(samples, conditions) | 指定样本和条件限制下绘图 |
| cfdist1 < cfdist2 | 测试样本在cfdist1 中出现次数是否小于在cfdist2 中出现次数 |

