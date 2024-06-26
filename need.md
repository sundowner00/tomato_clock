# 需求分析

## 功能性描述

### 1.番茄钟计时功能

1.用户可以在应用中设置工作时间与休息时间，并开始倒计时。
2.在计时结束时提醒用户。

### 2.任务编辑功能

1.用户可以在应用中添加、删除指定任务，并设置每个任务的番茄钟计时器。

### 3.宠物奖励功能（基础版）

1.在用户完成自己的任务后，可以获得一定的经验，经验可以使宠物升级。

### 4.宠物养成系统

1.可以记录宠物状态，如行为、外貌。
2.宠物等级变化会使得宠物状态变化。

### 5.社区功能

1.用户在社区中可分享专注动态与宠物动态。

### 6.信息存储

1.利用数据库存储用户各项信息，如任务列表、宠物状态、社交动态等。

## 非功能性需求

### 1.性能需求

1.对于用户执行任务的要求，应该在1s内调出番茄钟计时功能，完成任务的计时要求。
2.宠物状态发生变化，应在5s内更新养成系统相关信息。
3.在动态功能中，发布动态花费时间应该不多于5s。
4.在有大量用户发布动态时，系统性能仍然可以维持较高水平。

### 2.安全性需求

1.保护用户信息不被泄漏。
2.能防止恶意攻击，如DDos攻击。

### 3.可用性需求

1.系统正常运行时间应达到99.9%
2.出现故障能在一小时内恢复。

### 4.可维护性

1.系统应做到良好的模块化和文档化，以便于维护升级。

### 5.可扩展性

1.系统应设计为可扩展的架构，便于日后添加新功能，如宠物定制、宠物状态反馈番茄钟状态等功能。

### 6.用户体验

1.用户界面应简洁好用，能够让用户快速了解应用功能。
2.系统应具有反馈功能，便于用户向开发者反馈意见与建议。

 ## 需求优先级

 在开发过程中，可以按照下列优先级划分需求：

 1.高优先级：基本的计时功能、任务编辑功能、完成提醒功能与宠物升级功能。
 2.中优先级：宠物养成系统、社区功能、信息存储功能。
 3.低优先级：其他的扩展功能，如美观界面等。