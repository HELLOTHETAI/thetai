---
layout: default
title: NLP Tool
parent: NLP
nav_order: 1
---

# NLP Tool
## Label Tool
1. **Name**: Chinese-Annotator  
   **Github**: https://github.com/deepwel/Chinese-Annotator  
   **Discription**:自然语言处理的大部分任务是监督学习问题。序列标注问题如中文分词、命名实体识别，分类问题如关系识别、情感分析、意图分析等， 均需要标注数据进行模型训练。深度学习大行其道的今天，基于深度学习的 NLP 模型更是数据饥渴。
   最前沿的 NLP 技术往往首先针对英文语料。英文 NLP 的生态很好，针对不同有意思的问题都有不少大规模语料公开供大家研究，如斯坦福的 SQuAD 阅读理解语料。中文方面开源语料就少得多，各种英文 NLP 上的犀利模型和前沿技术都因为中文语料的匮乏很难迁移过来。另一方面，对于一些垂直领域，如医疗、金融、法律、公安等等，专有名词和特有需求甚多，很难将比较 general 的比如在 wikipedia dump 上面训练的模型直接拿过来用。
   传统人工标注数据的过程往往是繁琐和低效率的。刚标了一个“联想”是公司名，又来一个“联想集团”，再标一次又来一个“联想集团有限公司”，如此的例子令标注过程含有大量的重复劳动。另一方面也没有一个易上手的标注 UI，标注工作者往往需要直接按预先定好的格式直接在写字板之类的软件中修改原始数据，格式错误率也较高。能不能构建一个中文文本的标注工具，可以达到以下两个特点：  
   - 标注过程背后含有智能算法，将人工重复劳动降到最低；
   - 标注界面显而易见地友好，让标注操作尽可能简便和符合直觉。 
   
   **Tool**: Mongodb,nodejs,yarn  

2. **Name**: doccano  
   **Github**: https://github.com/doccano/doccano  
   **Discription**: doccano is an open source text annotation tool for humans. It provides annotation features for text classification, sequence labeling and sequence to sequence tasks. So, you can create labeled data for sentiment analysis, named entity recognition, text summarization and so on. Just create a project, upload data and start annotating. You can build a dataset in hours.  
   **Tool**: Docker


