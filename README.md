# EE1009 - 数字电子技术基础

![Static Badge](https://img.shields.io/badge/%E8%80%83%E8%AF%95%E8%AF%BE-red)
![Static Badge](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-3.5-moccasin)

![Static Badge](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![Static Badge](https://img.shields.io/badge/平时成绩-20%25-wheat)
![Static Badge](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-80%25-wheat)

注意，数字电子技术实验（[EE1010](https://hoa.moe/docs/sophomore-spring/ee1010)）是独立设课。

## 教材与参考书

教材：(清华大学) 阎石，王红主编，数字电子技术基础（第6版），高等教育出版社。

参考书：(清华大学) 阎石，王红主编，数字电子技术基础 学习辅导与习题解答，高等教育出版社。

**请注意，习题指导从出书开始就几乎没有修订过，所以有不少错误，不要照抄习题指导的答案。**

注：王红在课上说过，她会修订教材里发现的错误，但不会去修订习题指导里面的错误（乐）

## 授课教师

共同特点：**上课会有小测。以考勤为主，到场即有60分。**
- 喻锦程
  - 授课风格：年轻小姐姐，人美心善，上课讲解细致（有时甚至达到啰嗦的程度）
  期末考前会录制复习视频，也会鼓励大家，发在群里的消息很有意思！
  - 听课建议：认真听讲。她所负责的前半部分（包括数制与码制、逻辑代数基础、门电路、组合逻辑电路）难度不大，考查方式也比较固定，但是小题可以出得比较细。
- 梁亮
  - 授课风格：上课讲解比较清晰。但是课后答疑态度较差（<i>"这个来上课的同学都知道的"</i>），而且很喜欢在考试中出计算量极大、重复劳动很多的题目。
  往年许多同学考试成绩很差。（请将老师的授课水平和出卷风格分开评价，不要因为其出卷风格而全盘否定其授课水平）
  - 听课建议：认真听讲。梁老师所讲的部分主要是触发器、时序逻辑电路、振荡电路和A/D D/A等较难的内容，是考试的重难点，光靠课上听不明白，一定要在课下多加整理！！

>  文 / [Oliver Wu](https://github.com/OliverWu515) 

## 主要内容

**Yu老师常常会担心大家听不明白门电路的内容，而花大量时间在讲解TTL反相器等电路的内部结构中。在这段时间内，大家可以预习后面内容，或是多花时间学模电（模电的入门难，数电学到后面难）**

| **序号** | **内容**       | **学习建议**      |
| -------- | --------------------------------- | ----------------------------|
| 1        | 绪论，数制和码制  |  相对比较容易。 几种数制和码制的转换要很熟练。尤其注意掌握补码的概念（不仅是计算方法！）。   |
| 2        | 逻辑运算，逻辑代数的基本定理和基本规则，逻辑函数的代数化简法 | 公式法化简技巧性强，如果不能熟练掌握也没关系，考试以下一次课讲的卡诺图化简法为主。   |
| 3        | 最小项和最大项的概念，逻辑函数的卡诺图化简法，具有无关项的逻辑函数化简 |   卡诺图化简需要重点、熟练掌握。最大项属于自学内容。无关项属于考试范围。  |
| 4        | 门电路基本概念，半导体二极管门电路，MOS管的开关特性 |  门电路符号要清楚，**国标和国际标准（特定外形符号）都要看得懂。** 半导体二极管门电路了解即可。注意理解MOS管开关特性（截止和饱和时分别有什么特点？可以等效成什么？）|
| 5/6       | CMOS反相器、传输门、OD门的工作原理、参数特点及应用、若干常用集成门电路。 |  CMOS反相器的电压传输特性、输入输出特性需要熟练掌握。（比如：阈值电压是多少？）三态门、传输门需要掌握功能、了解内部结构。对于OD门，要知道它的作用（如“线与”等），还有一类必考题型：**上拉电阻的计算题。** 常用集成门（如异或门等）只需要了解即可。 |
| 7        | 双极型晶体管(BJT)的开关特性，TTL门电路，标准TTL与非门的工作原理   | BJT的开关特性需要理解（截止和饱和时分别有什么特点？）熟练掌握标准TTL与非门工作特性（需要细致到输入某个电压时，电路中某个点的电压是多少）， 属于重要内容。**小题基本必考。**   |
| 8/9        | 标准TTL与非门的特性曲线和主要参数、其它TTL逻辑门 | 掌握TTL与非门的输入输出特性、电压传输特性等。注意体会TTL门电路和CMOS门的区别。（例如TTL由于是流控型，有输入负载特性；输入级采用多发射级晶体管的TTL门电路，计算低电平、高电平输入电流时需要特殊处理）。其他TTL逻辑门以三态门、传输门的工作原理及应用为主。对于OC（集电极开路）门，需要知道它的作用，还有一类必考题型：**上拉电阻的计算题。** 异或门等了解即可。  |
| 10        | 半加器和全加器。集成4位加法器74LS283、二进制编码器的原理和集成优先编码器的应用。 |   难度不大。考试较少出现，遇到随机应变即可。    |
| 11       | 译码器74LS138及应用，显示器件及显示译码器74LS47、48的原理及应用 | 74LS138经常用于生成逻辑函数，属于必考内容。显示译码器属于了解部分，考试很少涉及。  |
| 12       | 数据选择器及应用，比较器，竞争和冒险    | 数据选择器属于常考内容，经常用它生成逻辑函数。比较器难度较低，有可能会出现在一些使巧劲的题目里，较少出现。**竞争冒险不考，但是以后若要自己设计数字电路，则是非常重要的概念。**   |
| 13/14       | 组合逻辑电路的分析，逻辑函数的变换，组合逻辑电路的设计、习题课    |   需熟练掌握。逻辑函数的化简基本功要扎实，而且要耐心、细心。可能不会有专门的习题课，但是确实会有很多题，可能穿插着讲解。需要认真理解每道题！！！       |
| (不设课)  | Verilog语言的结构及描述方式，组合逻辑电路的Verilog语言实现   | 此部分教学大纲上列出，但是放到了数字电子技术实验（[EE1010](https://hoa.moe/docs/sophomore-spring/ee1010)）来讲。由于课上能学习Verilog的时间很少（基本都要用来完成任务）、讲解的Verilog语法也很有限，大家在上数字电子技术实验有关Verilog的内容前，**务必认真预习！**   |
| 15/16       | 基本RS、时钟RS触发器的结构功能、电平触发、脉冲触发、边沿触发的触发器 |   非常重要！注意理顺从 基本RS触发器 到 边沿触发的触发器的演变流程与思路（例如，为了解决多次翻转的问题，由同步RS触发器变成了脉冲触发的RS触发器；由于禁态的限制，又通过引入反馈线，构成了主从JK触发器；为了提高抗干扰能力，又演变出了边沿触发的触发器）！注意主从触发器和边沿触发器的区别（整个时钟有效周期都接收信号 VS 只取决于上升沿到来时信号）！给出时钟信号和输入信号的波形，要求画出输出波形，是必考的题目，也很能锻炼大家的逻辑思维能力！ |
| 17       | D触发器；JK触发器；T触发器；T'触发器。 |   同上，非常重要！需要掌握每种触发器的输出方程和状态方程，设计时序逻辑电路时需要用到！ |
| 18       | 集成同步加法计数器74LS160/161/162/163，集成异步加法计数器74LS90/290/93/293 | 需要熟练掌握。对于含计数器的时序逻辑电路的状态转化分析，特别重要，也是必考的！！     |
| 19       | 集成加/减计数器74LS190/191/192/193，移位寄存器型计数器，顺序脉冲发生器，序列脉冲发生器 |  加减计数器了解即可，如果考试有用到需要随机应变。自己设计编码器计数电路等可能会用到。移位寄存器型计数器以分析为主，设计不作为重点，也比较难。最后两者，理解并掌握，作业会涉及。  |
| 20-22       | **同步、异步时序逻辑电路的分析与设计**   | 对于分析，正确判别次态是关键。特别注意异步置位、复位端等不在时序控制范围的变化！注意上升沿还是下降沿触发！注意不同触发器类型！对于设计，流程比较固定：1. 根据任务要求列出电路的状态转换表或转换图；2. 状态化简；3. 根据电路的状态表确定触发器的数目n；4. 根据状态转换表画出电路**次态卡诺图**；5 .由卡诺图求出电路的**状态方程和输出方程**。6. 由状态方程写出电路的驱动方程。7.由驱动方程和输出方程画出逻辑图。**计数器的分析和设计又有其特别的方法，而且特别重要。十六进制、十进制计数器能玩的花样很多。**        |
| (不设课)     | 状态机的基本概念和用Verilog语言实现状态机及仿真研究。        | 放到了实验课中讲解。同样，由于课上能学习Verilog的时间很少（基本都要用来完成任务），大家上课前**务必认真预习！**   |
| 23       | 寄存器，半导体存储器ROM的工作原理和应用，RAM的工作原理  | 寄存器以分析为主。ROM常用来生成逻辑函数（通过在对应的地址线上），RAM的电路只需了解即可，但是需要掌握半导体存储器容量的扩展（位扩展和字扩展方式）。     |
| 24       | 施密特触发电路，微分型、积分型单稳态电路、多谐振荡器            |   需要认真理解各类触发电路上升、下降阶段等效电路的画法及时间常数的计算。（TTL和CMOS还有区别）     |
| 25       | 555定时器结构原理、555定时器构成的单稳态电路、多谐振荡器、施密特触发电路和压控振荡器的工作原理和参数计算  |很重要，需要熟练掌握！考试一定会涉及利用555定时器来生成振荡波形或实现单稳态电路！ |
| 26       | 数模和模数转换器的基本概念，倒T型电阻D/A转换器网络，集成D/A转换器AD7524，权电流型D/A转换器 | 需要熟练掌握。 |
| 27       | AD转换的基本原理，并行比较型A/D转换器，逐次逼近型A/D转换器  | 重点掌握A/D转换基本概念。要会计算转换时间。    |
| 28       | 双积分型A/D转换器、模拟开关、期末复习  |   双积分型转换器的转换时间计算比较重要。期末复习基本是复习了个寂寞（<i>“平时都讲过了”</i>，不过也确实如此，平时及时复习就好）      |

> 文 / [Oliver Wu](https://github.com/OliverWu515) ，2023.12

## 关于考试

由于梁老师经常在考试中加入大量计算量极大、重复劳动很多的题目（此类题不算难题，但是很容易拉低学生成绩），并且考卷上还有**真正的难题**（最后一题，思维上难度大），
所以大家的分数普遍不高。21级自动化6-8、电气1-3大班共180人左右，总分90分及以上仅有5人。

大家一定要分清“重复劳动很多的题目”和“难题”，考试中细心一些，把看似繁复实则思维难度较低的题目都拿下，这样就能获得比较高的分数了。

> 文 / [Oliver Wu](https://github.com/OliverWu515)  

- 24 年春自动化数电考试相比去年的考试 题量 --，难度 --，重复劳动 --
- 复习时可将今年的回忆题目当做基础回顾，再去攻克 23 年的题目，特别是多去体会 23 年的最后一道设计题目的设计思路和设计理念
- 考试时试卷上最后一页印上附录，包括 555 定时器的电路结构图和第七章的众多公式（各种电路的周期、占空比等），这部分可以不用死记硬背

> 文 / [psp_dada](https://github.com/pspdada), 2024.7

## Tips

- 数字电子技术课程其实不算难，因为其中很多东西都是离散的，因此抗干扰能力好，可以理想化地去看待。不像模电，由于其连续性，噪声抑制很难，对信号质量要求特别高，差几十毫伏可能就会有很大影响。
- 模拟电子技术课程以分立元件为主，数字电子技术课程以中规模集成电路芯片为主。对于芯片，将其看成黑箱子，关注外部的01特性即可。
- 虽然8位电脑与中规模集成芯片的时代早已过去，但是在低成本的嵌入式应用中，74系列基本芯片仍大有用武之地。当然，大家也不要满足于这些上古芯片，可以多去TI（德州仪器）官网等网站上学习最新的数字电路发展成果。

> 文 / [Oliver Wu](https://github.com/OliverWu515) ，2023.12.3
