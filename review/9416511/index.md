# 标题

## 基本信息

| Paper Title | Alterations in Muscle Networks in the Upper Extremity of Chronic Stroke Survivors |
| :---------- | ------------------------------------------------------------ |
| 年份        | 2021                                                         |
| 作者        | [Ping Zhou](https://ieeexplore.ieee.org/author/37330883000)青岛康复大学 |
| 状态        | 待开始                                                       |
| 期刊        | IEEE Transactions on Neural Systems and Rehabilitation Engineering |

## 摘要

> [!tip|style:flat|label:摘要] 
>
> 肌肉网络描述了通过分解**肌肉间相干性**（IMC）量化的肌肉之间的**功能连接**，以确定某些肌肉**由共同神经输入**共同调节的**共享频率**。已经努力表征健康受试者的肌肉网络，但与中风相关的肌肉网络改变仍未得到探索。在轻度、中度和重度损伤的卒中幸存者产生**等长力**期间，评估了八个关键上肢肌肉的肌肉网络，并与健康对照组进行比较，以确定肌肉连接的卒中特异性改变。**相干矩阵使用非负矩阵分解**。然后**评估阈值的方差**以确定肌肉网络的数量。结果显示，与年龄匹配的健康对照组（健康对照组有四个网络）相比，随着卒中后运动障碍的严重程度增加（轻度卒中组三个，中重度卒中组中两个），卒中幸存者的肌肉网络数量减少。与健康对照组相比，中风患者α带协同三角肌中的IMC有统计学意义降低（p <0.05）。据我们所知，这项研究代表了使用肌肉网络分析评估功能性肌间连接中与中风相关的改变的首次努力。**研究结果揭示了与健康对照组相比，中风幸存者肌肉网络的改变模式**，这是与中风相关的大脑功能丧失的结果。肌肉网络的这些改变反映了潜在的病理生理学。这些发现可以帮助更好地了解中风的运动障碍和运动控制，并可能通过识别频域中多个肌肉之间的神经肌肉协调受损来推进中风的康复工作。

## 创新点

## 思维导图



## 重点内容

### 背景介绍

> ?>核心观点与说明

> [!Note] 
>
> 在美国，脑卒中是导致残疾的主要原因之一[1]，通常会导致患臂(affected arm)肌肉的**运动协调异常**[2]-[4]。先前的研究表明，神经和肌肉骨骼系统通过同时共同激活肌肉群作为**运动构建块**（motor building blocks, 即所谓的肌肉协同作用）来交互工作以简化神经肌肉控制，以降低冗余肌肉骨骼系统的自由度[5]-[11]。传统上，通过**肌肉协同分析**[12]-[17]以及**肌间相干性**(intermuscular coherence, IMC)[18]-[20]来研究脑卒中对肌间协调的影响。
>
> 各种降维工具，包括非负矩阵分解(NNMF)[21]，已被用于识别肌肉协同作用，即肌肉激活的**解剖协调**。例如，与年龄匹配的健康对照组相比，在重度脑卒中患者中应用NNMF可以发现**等长力**产生的肌肉协同模式的组成发生了变化[16]。在卒中患者中观察到前、中、后三角肌纤维的异常共激活，而健康对照组表现出前三角肌和中三角肌在一种协同作用中的共同激活，以及中三角肌和后三角肌在另一种协同作用中的共同激活。此外，将NNMF算法应用于从不同程度运动障碍的脑卒中幸存者收集的肌电图(EMG)数据，发现近端肌肉协同作用的改变在严重程度较轻的脑卒中损伤中也很明显，但在重度脑卒中中仍然最明显[17]。近端肌肉协同作用的改变意味着中风后幸存者可能**缺乏在等长条件下选择性激活三角肌的能力**。然而，虽然肌肉协同作用可以代表神经肌肉控制中的解剖肌间协调模式，但它们**不能量化肌肉之间的功能连接，例如连贯性**[22]。
>
> 相干性(Coherence)是**频域中两个信号之间相关性的度量**，可用于评估肌肉之间的**功能连接**[23]，[24]。Kisiel-Sajewicz等人利用IMC分析发现，与健康对照组相比，严重受损的脑卒中受试者在0-11Hz频率范围内，前三角肌和肱三头肌协同肌对的功能耦合减少[18]。研究中揭示的卒中参与者协同肌肉对的功能连接减少，可能解释了中风中目标到达任务中，运动控制不佳的原因，并且可以进一步解释为，肌肉的公共神经输入的丧失或减少，可能是由于皮质脊髓通路受损。Fisher等人还发现，$\beta $ 带(15-30Hz)第一背侧骨间肌、趾伸肌和趾屈肌浅表肌的IMC与皮质脊髓束的完整性有关[19]。
>
> 还使用IMC或连接分析(connectivity analysis)研究了特定频率范围内**肌肉神经输入的调制(Modulations)**。一项研究涉及手部肌肉的两项不同的捏合任务，发现**振荡神经(oscillatory neural)输入**的调制在相干性为10Hz时增加，在40Hz时降低[25]。双手上臂屈伸中存在体感反馈，也增加了$\alpha$带和$\beta$ 带肌肉之间的神经耦合[26]。在**斜坡力生成**与**力保持期**研究中，还发现了IMC在15-30 Hz范围内的任务相关调制[27]。
>
> 此外，**连贯性分析(coherence analysis)**也被用于研究大脑和肌肉之间的功能连接。皮质-肌肉相干性(Cortico-muscular coherence, CMC)分析已应用于MEG和EMG数据[28]，其报告15-30Hz的CMC与手部运动功能有关。之前一项使用脑电图(EEG)和肌电图记录的CMC研究[20]报道，在上肢运动期间，$\beta$ 频带(15-35Hz)的皮质-肌肉耦合强度最强。$\beta$ 带的CMC和IMC也在神经健康个体的第一骨间背侧肌和拇短展肌的双指夹持任务中同时进行，并发现β带指示肌肉的协同控制，其中相干皮质区域(coherent cortical areas)，功能性地将任务相关运动神经元结合成功能单元[29]。总体而言，以前的研究一致表明$\alpha$，$\beta$ 和$\gamma$频段在神经肌肉控制中很重要，并且具有不同的起源。
>
> **肌肉网络分析(Muscle network analysis)**是最近开发的一种新方法，用于研究肌肉的**功能连接(functional connectivity)**，以进一步解释肌肉协同作用的**神经输入特性(property of neural inputs)**及其**简化运动控制**的能力[30]。肌肉网络是通过 **EMG-EMG 相干性的分解**得出的，以识别某些肌肉由一些共同神经输入共同调节的**共享频率**，而肌肉协同作用是通过 EMG-EMG **振幅的分解**来识别的，以识别在运动任务表现中共同活跃的肌肉集。肌肉协同作用根据力生成过程中**肌电图振幅的协变(co-variation)**将肌肉分组在一起，而肌肉网络根据它们在**不同频谱区域(distinct spectral regions)中的共同神经输入**将肌肉分组在一起，被视为肌电图频率的协同调制(co-modulation of EMG frequencies)，通过**相干性(coherence)的分解**进行评估。先前的研究表明，**肌肉协同作用和连贯性肌肉网络(coherence muscle networks)**是相互补充的，并且对于理解神经肌肉运动控制都是必要的[30]，[31]。在姿势任务期间，已经在健康个体中研究了肌肉网络[30]，[32]以及步态分析[31]，但尚未在运动控制功能受损的个体(如中风)中进行了研究。因此，中风如何改变肌肉网络仍然未知，即使科学发现可以支持更好地理解随着中风后损伤严重程度的增加而肌肉间协调的变化。

### 数据分析

> ?>核心观点与说明

> [!Note] 
>
> 个体无法进行力目标匹配的试验从分析中被丢弃。提取了每个成功试验的稳定力生成阶段。肌电图数据被进一步**贬低(demeaned)**，使用希尔伯特变换进行校正，并**归一化为单位方差**，以防止后续分析被高方差的肌肉(muscles with high variance)偏向(biased)[35]，[36]。然后将来自所有成功试验的信号**连接起来**，以便为相干性分析提供更多样本。
>
> 幅度平方相干性，通过计算两个信号之间的交叉频谱并将其归一化为信号的自动频谱Eq.(1)，然后是平方模 [23]、[24] 得出的。IMC 是通过八块上臂肌肉中所有 28 对肌肉的量级平方相干性计算的。应用长度为500毫秒和50%窗口重叠的汉宁窗口，并在0–50 Hz的频率范围内计算相干性，频谱分辨率为2 Hz [37]。
> $$
> \begin{equation*} C_{xy}=\frac {\left \vert{ P_{xy} }\right \vert ^{2}}{P_{xx}{}^\ast P_{yy}}\tag{1}\end{equation*}
> 
> $$
> 将非负矩阵分解(NNMF)应用于相干矩阵(coherence matrices)，以识别肌肉共享的(shared by the muscles)独特频谱模式(unique spectral patterns)[30]-[32]。从 NNMF 获得了具有权重系数(肌肉对贡献强度)和激活模式(一致性识别模式)的 IMC 的较低近似值。结果，相干矩阵被建模为$k$ -排序重建矩阵，$M$ ，具有残差重建误差矩阵$E$ 使用 NNMF。重建矩阵$M$具有以下维度：$f$ （离散频率评估），$m$ （肌肉对的总数），以及$k$ （矩阵排名）。这导致了两个矩阵，$W$ 和$H$  Eq.(2).W 和H 分别是网络的相干模式和边权重。





### 内容标题

> ?>核心观点与说明

> [!Note] 
> 

### 内容标题

> ?>核心观点与说明

> [!Note] 
> 

### 内容标题

> ?>核心观点与说明

> [!Note] 
> 

### 内容标题

> ?>核心观点与说明

> [!Note] 
> 

### 内容标题

> ?>核心观点与说明

> [!Note] 

## 参考文献
