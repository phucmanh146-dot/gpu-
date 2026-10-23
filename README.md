# Hello GPU 学习打卡

Task1、Task2各三条，共六条。每条打卡正文均不超过50字，单独附原教程来源。

## 章节目录

- [Task1：环境、线程与数据](task1/README.md)
- [Task2：计时、Trace与性能判断](task2/README.md)

## Task1

### [Task1 · 打卡一：环境检查](task1/01-environment.md)

理清了环境验证的三道关：识别GPU、运行框架计算、编译并校验HIP程序。

### [Task1 · 打卡二：线程分工](task1/02-threads.md)

理解了线程、线程块和网格的关系，知道索引负责分工，边界检查防止越界。

### [Task1 · 打卡三：数据与执行](task1/03-data.md)

学会区分寄存器、缓存和共享存储，也明白了提交任务不代表GPU已经算完。

## Task2

### [Task2 · 打卡一：可信计时](task2/01-timing.md)

理解了异步执行和计时范围，测速前要预热、校验，并通过重复测量观察波动。

### [Task2 · 打卡二：带宽与轨迹](task2/02-trace.md)

学会计算有效带宽，分析Trace时要筛选目标内核，排除预热和辅助计算记录。

### [Task2 · 打卡三：性能判断](task2/03-roofline.md)

理解了算术强度与Roofline，性能变化需要证据，不能只凭一次测速判断原因。

## 范围与提交说明

- 目前沿用此前学习包范围：Task1为第0—4章，Task2为第5—7章；本期官方Task对照表尚未核实。
- 这里记录理论学习理解，不包含个人设备的实测成绩；不把六条笔记伪装成六天实验。
- 根据课程原通知，每个Task在飞书只提交一次，修改使用历史记录。本仓库发布不等于已提交课程打卡。
- 这些简短正文按个人要求控制在50字以内；若活动严格要求50字或更多，请按实际提交要求补充。

## 资料来源

- [Datawhale Hello GPU 仓库](https://github.com/datawhalechina/hello-gpu)
- [Hello GPU 教程](https://datawhalechina.github.io/hello-gpu/)

资料：Datawhale《Hello GPU》，按 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 通俗改写。
