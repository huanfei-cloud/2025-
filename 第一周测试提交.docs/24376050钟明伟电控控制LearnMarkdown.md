# 这是一级标题 (H1)
## 这是二级标题 (H2)
### 这是三级标题 (H3)
#### 这是四级标题 (H4)
**这是加粗的文字**
*这是斜体的文字*
~~这是带删除线的文字~~
***这是又斜又粗的文字***\
无序列表 使用 -、+ 或 * 开头
- 任务一
- 任务二
  - 子任务 A
  - 子任务 B\

有序列表 使用数字加 . 开头。
1. 第一步：打开冰箱
2. 第二步：把大象放进去
3. 第三步：关上冰箱
> 这是一段引用。
>
> > 这是嵌套的引用。


[点击这里访问 GitHub](https://github.com/)\
![Markdown 图标](https://markdown.com.cn/assets/img/ico.png)\
用三个或更多-、* 或 _ 来创建一条水平分割线。
---
***
___
我正在学习如何用 C++ 控制电机，下面是一段伪代码示例：
```cpp
#include <iostream>

void setMotorSpeed(int motorId, int speed) {
    // 假设这是一个控制电机速度的函数
    std::cout << "Motor " << motorId << " speed set to " << speed << std::endl;
}

int main() {
    // 设置1号电机速度为 90%
    setMotorSpeed(1, 90);
    return 0;
}