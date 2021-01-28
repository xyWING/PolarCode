# PolarCode

## Background

通信系统的基本模型由信源、信道、信宿组成。对于数字通信系统而言，通过信源编码和信道编码的过程，能够提高信息传输的有效性和可靠性。信道编码理论研究的核心工作即是在一些实用信道下，如加性高斯白噪声信道，寻找能够逼近信道容量（也称为香农界）的实用调制编码方案。
2008年，Erdal Arikan在国际信息论ISIT会议上首次提出了信道极化（Channel Polarization）的概念[1]；2009年在IEEE Transaction on Information Theory期刊上发表文章[2]更加详细地阐述了信道极化理论，并基于信道极化给出了一种新的编码方式，名称为极化码（Polar Code）。极化码具有确定的构造方法，并且是已知的唯一一种能够被严格证明达到信道容量的信道编码方法。
Arikan在文献[2]中指出，Polar Code通过“信道联合”和“信道分裂”两个过程，产生了信道极化现象，即各个子信道的可靠性随着信道数目的增加而趋向于两个极端：一部分分裂信道趋近于信道容量接近1的无噪声完美信道，另一部分分裂信道趋近于信道容量接近0的完全噪声信道；前者用于传输信息比特，后者用于传输固定比特（冻结比特）。极化码概念的提出，引起了世界各地广泛的研究兴趣。中国华为（HUAWEI）公司长期以来斥巨资研究并推进极化码的落地。2016年11月18日，在美国内华达州召开的3GPP RAN1 第87次会议，确定Polar Code作为5G eMBB（增强移动宽带）场景下控制信道编码方案。

## Reference
> [1] Arikan, E. “Channel Polarization: A Method for Constructing Capacity-Achieving Codes.” 2008 IEEE International Symposium on Information Theory, 2008, pp. 1173–1177.
> [2] Arikan, E. “Channel Polarization: A Method for Constructing Capacity-Achieving Codes for Symmetric Binary-Input Memoryless Channels.” IEEE Transactions on Information Theory, vol. 55, no. 7, 2009, pp. 3051–3073.
