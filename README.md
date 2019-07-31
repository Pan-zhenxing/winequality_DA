# Winequality_DA
这个notebook分析了红酒的通用数据集。这个数据集有1599个样本，11个红酒的理化性质，以及红酒的品质（评分从0到10）。这里主要目的在于展示进行数据分析的常见python包的调用，以及数据可视化。  
此项项目利用pandas库对原始数据进行处理和计算，并使用matplotlib库的pyplot模块和seaborn库对出具进行可视化操作。通过对数据的计算和对图形的观察，顺利找出影响红酒品质的主要影响因素。但需要说明的是，本项目中进行的分析仅仅是从数据本身展现出来的情况进行的，仅仅能表明数据之间的相关关系。在所有的分析结论中，数据之间的因果关系或者逻辑关系，仅仅是一种合理推测，并非严格的统计论证。 整体而言，红酒的品质主要与酒精浓度，挥发性酸，和柠檬酸有关。对于品质优于7，或者劣于4的酒，直观上是线性可分的。但是品质为5，6的酒很难线性区分。待以后有时间，还可以搭建一些机器学习的模型，通过数据训练，来预测未给出数据的乘客生还情况。
