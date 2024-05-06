## Current Problems:

* AD算多少分？

****

## Add:

* lstm的原理、**示意图**



## Analysis：

* question1：建模捕捉比赛的过程，将其应用于实际比赛
  * 模型可以看出哪个运动员在某一时刻的表现更佳（计算势头）
  * 可视化（加入重点事件：ace、……）
* question2：判断势头是否真的影响到了比赛的走势（比赛的波动与成功是否是随机的）
  * keyword：swing
* question3.1：是否有一些指标可以说明在比赛过程中，优势从一个运动员转移到另一个
  * mysolution：lstm，改变输入的参数，预测势头，通过loss判断哪些因素
* question3.2：基于过去比赛中势头变化的差异，给出选手建议
* question4：
  1. 评价模型
  2. 如果模型预测效果差，能否判断更优的影响因素
  3. 你的模型对其它运动的兼容性如何

****



## Updates

### V1：

* input

> 1. elapsed_time(process)
> 2. p1_score
> 3. p2_score
> 4. p1_double_fault
> 5. p2_double_fault

### V2: experiment

* learning rate
* epochs
* window_size
* hidden_size
* layers

| arguments(l/e/w) |      |      |
| ---------------- | ---- | ---- |
|                  |      |      |
|                  |      |      |
|                  |      |      |

