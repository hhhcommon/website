﻿+++
title = "迭代工作台"
description = "了解如何使用迭代工作台预估冲刺进度，并且及时评估项目存在的风险。"
weight = 6
+++

# 迭代工作台

迭代工作台以冲刺为维度为用户快速展示某冲刺的各种统计信息，有利于项目管理者预估冲刺进度，并且及时评估项目存在的风险。

进入`活跃冲刺`菜单，点击页面上方的`切换至工作台`，进入到`迭代工作台`中。

`迭代工作台`显示当前项目正在进行的冲刺信息，即活跃冲刺，分为冲刺概要图、状态分布图、燃尽图、迭代问题类型分布图、距离冲刺结束图、迭代问题类型分布图、优先级分布图、经办人分布图、冲刺详情图八个部分。

1-4部分，如下图所示：

![iterationboard](/docs/user-guide/agile/imge/iterationboard-sprint.png)

## 1.冲刺概要图
    
展示该冲刺的概要信息，包括：
    
- 冲刺名称

- 该冲刺下的问题可见数量，统计活跃冲刺看板中的可见问题（包括故事、任务、故障）

- 冲刺目标

- 冲刺开始时间与结束时间

## 2.状态分布图

按照状态类别的维度统计`待处理`、`处理中`、`已完成`三类问题数量与所占比例。

## 3.距离冲刺结束图

计算当前时间具体冲刺结束时间的天数。

## 4.燃尽图

用于跟踪记录所有问题的剩余工作工作时间，预估完成冲刺任务的可能性，回顾总结迭代过程中的经验与不足。

详情情查看[燃尽图](../../../report/agile-report/burn-down/)

5-8部分，如下图所示：

![iterationboard](/docs/user-guide/agile/imge/iterationboard-velocity.png)

## 5.迭代问题类型分布图

按照问题类型统计不同状态类别下的问题数量，可快速分析冲刺下问题分布情况。

- 横坐标表示问题类型，包括：故事、故障、任务、子任务

- 纵坐标表示在某个问题类型下，不同状态类别（待处理、处理中、已完成）下的问题数量。

## 6.优先级分布图

按照问题的优先级（高、中、低）为维度，统计冲刺下问题已完成和总计数的数量。

例如： 1/3表示已完成问题数为1，总计数为3。

## 7.经办人分布图

按照问题的经办人为维度， 统计冲刺下各个经办人所经办的问题数量与所占百分比，以饼图的形式展示。

## 8.冲刺详情图

展示冲刺下的问题详情列表。
   
详情模块：

- 已完成的问题：当冲刺中的问题已完成，则此问题将归类于此项。
     
- 未完成的问题：当冲刺中的问题未完成，并且已预估故事点（问题类型为故事）或时间（其他类型的问题），则此问题将归类于此项。

- 未完成的未预估问题：当冲刺中的问题未完成，并且未预估故事点（问题类型为故事）或时间（其他类型的问题），则此问题将归类于此项。

字段描述：

- 关键字：表示问题编号

- 概要：表示问题概要

- 问题类型：表示问题类型，包括史诗、故事、任务、缺陷

- 优先级：表示问题优先级，包括高、中、低
     
- 状态：表示问题关联的状态
    
- 故事点：如果问题类型是故事，将显示该问题的故事点。其他类型不显示该字段

## 更多操作

- [规划冲刺](../../backlog/sprint)
- [报告工作台](../../report/reportboard)
- [如何使用看板](../../sprint/manage-kanban)




