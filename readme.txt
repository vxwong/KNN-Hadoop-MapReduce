·基于Mapreduce的KNN实现

·OS:64位Ubuntu14.04虚拟机（master,slave1）

·该项目实现了基于欧拉距离，加权欧拉距离，高斯函数的KNN实现。


·文件组成：
	KNN.java			-- KNN实现代码
	KNN Train			-- 训练集(来自 http://archive.ics.uci.edu/ml/datasets/Iris)
	KNN Test			-- 测试集(来自 http://archive.ics.uci.edu/ml/datasets/Iris)


·运行注意事项：
	在运行程序时需要输入：训练集的路径 和 输出预测标签的路径。  -- e.g. hadoop@master:~/ReadFileTest$ hadoop jar /home/hadoop/ReadFileTest/KNN.jar KNN /train/iris_train.csv /KNNans3
	训练集的数据格式为：属性值A,属性值B,属性值C，...,标签       -- 属性值之间要用逗号隔开
	测试集的数据格式为：属性值A,属性值B,属性值C，...     	    -- 属性值之间要用逗号隔开



