---
title: 结构化约束模型输出
description: AI 写作技巧
---

## 结构化
1. [介绍解决方案的结构](./writing-struct-solution.md)
2. [推广类结构](./writing-struct-marketing.md)

## 正文
直接让模型写文章，常遇到输出的内容结构**不稳定**的情况。运气好的时候，内容妙不可言；运气不好的时候，内容就是一坨💩。

如何让模型**稳定**地输出令人满意的内容结构呢？答案就蕴藏在问题里：**定义**令人满意的**内容结构**， 让模型按这个结构输出。

## 例子
写介绍 **解决方案** 的文章时，我会用这样的结构: [介绍解决方案的结构](./writing-struct-solution.md)。

模型能稳定的输出[效果](./writing-struct-solution.md#效果)。

效果还不错吧～ 可以测试更多的解决方案:  
1. 番茄工作法
2. 非暴力沟通法
3. 卡片写作法
4. 麦肯锡SCQA模型
5. 金字塔模型
6. 5W2H模型

## 能用微调吗？
微调是一种提升模型执行特定任务能力的方式。是不是可以通过微调来让模型输出稳定结构的内容呢？ 

用微调的性价比很低： 
1. 微调的费用很贵。模型参数越大越贵，百亿参数大模型微调所需成本在十万元往上。
2. 微调依赖高质量标注数据集。少说也要 1 万条以上的标注数据。

效果怎么样，也难说。

## 最后
用结构化约束模型输出，是一种不错的提升模型输出质量的方式。难点在于，如何找到合适的内容结构。
