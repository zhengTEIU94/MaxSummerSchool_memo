## 有馬先生

> 笔记会实时更新 有不理解的部分可以在群里单独提问哈



- Max console  的作用

- New patcher 的建立方法

- Object 

  - max 独特的称呼方式

  - ex：
    - bang 
    - trigger 
    - random
    - ......

- 上方的工具栏的图表点击之后

  - 下方会出现更多对应范畴选项

- 提及到的**Object**
  - **random** 
    - 例如random 100
    - 则根据bang的频率随机出现100以内的乱数  
    - 0 - 99
  - **counter** 
    - 例如counter 0 1 10 
    - 有3个augment 
    - 0 的部分用来决定counter的数序
      - 0 是正序数
      - 1 是反序数
      - 2 是 正序数+反序数
    - 1 ， 10 代表区间 1～ 10
  - **button**
    - 用于触发
  - **print**
    - 用来监测输出的数值
    - 在max console的窗口可以监测
    - 快捷键 command + m

- 每个object上方都有两个input接口
  - 左边的端口是红色 
  - 右边的端口是蓝色

- 左下角有一个lock的图标
  - 点击之后切换lock/unlock状态
  - 用于切换编程的模式与运行的模式 
    - 快捷键  command + E

- **Max 的message的种类**
  - bang
    - max 独特的message
  - 整数（int）
  - 小数（floating）
  - 列表（list）
  - 符号

- 整数和小数
  - 整数 int  number
    - 快捷键 i 
  - 小数 floating  number
    - 快捷键 f 
  - **需注意**
    - 如果小数object连至整数object则小数点之后的数不会被读取
    - 在运算的情况下也是，例如进行除法运算时，若output的object为int object时， 则余数（如果有）部分不会被显示
- list （列表）