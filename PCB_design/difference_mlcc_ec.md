# 贴片电容与电解电容的区别
- 贴片电容的特性：小体积，中等容值，高电压，高频率，低ESR，损耗小
- 电解电容的特性：大体积，大容值，低电压，低频率，容差值大，漏电流大，损耗大

容值和耐压都符合的情况下，大部分电路中贴片电容可以对电解电容进行替换
以下两种情况除外：
	1. 电源对ESR范围有要求时，要注意ESR补偿问题
    2. 中低频（20Hz～20kHZ）的音频电路中，陶瓷电容会有音频噪音

电解电容替换陶瓷电容情况较为复杂：
	1. 贴片电容无极性，替换时需分辨电路极性
	2. 工作电压和工作频率需符合额定值
	3. 注意温度问题，电解电容不能放到大功率输出的电路中

总结：根据实际电路情况做出判断
