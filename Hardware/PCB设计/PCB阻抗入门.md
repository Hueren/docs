## 什么是阻抗匹配？

**阻抗要求是为确保电路板上高速性号的完整性而提出，它对高速数字系统正常稳定运行起到了关键性因素，在高速系统中，关键信号线不能当成是普通的传输线来看待，必需要考虑其特性阻抗，若关键传输线的阻抗没有达到匹配，可能会导致信号反射、反弹，损耗，原本良好的信号波形变形（上冲、下冲、振铃现象），其将直接影响电路的性能甚至功能。**

## 阻抗线按类型分

#### 单端阻抗

#### 差分阻抗

<img title="" src="https://telegraph-image666.pages.dev/file/7c17b1d1ab247af640829.png" alt="" data-align="left" width="238">

#### 共面单端阻抗

#### 共面差分阻抗

<img title="" src="https://telegraph-image666.pages.dev/file/0514c81efb9df8f8d727a.png" alt="" width="554">

共面差分周围有均匀的铜皮围着，铜皮到阻抗线距离一致，且铜皮上有成排via孔，共面差分阻抗线下面和周边都有地平面。

## 阻抗线按传输媒质分

#### 带状线

信号线位于两层接地面（或电源）之间的介质内的导线（在内层，有两个参考平面）根据传输线与两接地平面的距离相同或不同，又分为对称带状线和非对称带状线。

带状线的特性阻抗由导线的厚度、宽度、介电常数，及接地平面的距离有关。带状线两边都有电源或者底层，因此阻抗容易控制，同时屏蔽较好。

#### 微带线

用电介质将导线与地（电源）平面隔开的传输线（在PCB表层，仅有一个参考平面）分两种微带线，一种是埋入的（在内层），一种是非埋入的。微带线特性阻抗由导线的厚度、宽度、基材厚度及介电常数决定。主要用于双层和多层板。
