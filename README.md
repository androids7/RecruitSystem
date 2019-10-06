#SearchSystem
基于SSM实现的招聘考试系统。试题爬取通过WebCollector爬虫框架网上爬取试题，通过Lucene全文搜索试题，通过遗传算法生成试卷

在研究了传统遗传算法组卷的基础上，提出了基于信息匹配的遗传算法组卷技术。传统的遗传算法组卷对于试题的选择维度无法进行试题题干信息的匹配，而只能做到一些对整道试题的维度如知识点，难度系数，题型等，这样组出来的试卷针对特定的需求会比较差，而基于信息匹配的遗传算法组卷技术能很好的解决这个问题，结合Lucene对试题题干信息匹配度进行打分，以得到符合我们对特定题目口味的试题。
