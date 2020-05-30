# NLP Checklist

## PTM

## Tasks
### Word segmentation
- Word Dictionary Based Method   
先把句子按照字典切分成词，再寻找词的最佳组合方式
    - 最大匹配分词算法  
    *Trie树/字典树* 
    - 最短路径分词算法  
    *Dijkstra, N-最短路径*
    - 基于n-gram model的分词算法  
    *Language Model*
- Character Based Method   
先把句子分成一个个字，再将字组合成词，寻找最优的切分策略，转化为POS
    - N-gram
    - HMM
    - 平均感知机分词算法
    - CRF
    - BiLSTM+CRF
- Others   
    - 有限状态自动机
    - 词图
        - 邻接矩阵
        - 邻接表/单链表


+ Tools
    - [jieba](https://github.com/fxsjy/jieba)
    - [THULAC](http://thulac.thunlp.org/)
    - [pkuseg](https://github.com/lancopku/pkuseg-python)

+ Reference:  
   [1] https://zhuanlan.zhihu.com/p/50444885

### Part-of-speech tagging

### Text Classification

### Sentiment analysis

### Summarization

### Intent Detection

### Natural language inference 

### Question answering

### Machine translation

### Named entity recognition

### Entity linking

### Relationship extraction

## Application

## Tools
### NLTK
