������Mapreduce��KNNʵ��

��OS:64λUbuntu14.04�������master,slave1��

������Ŀʵ���˻���ŷ�����룬��Ȩŷ�����룬��˹������KNNʵ�֡�


���ļ���ɣ�
	KNN.java			-- KNNʵ�ִ���
	KNN Train			-- ѵ����(���� http://archive.ics.uci.edu/ml/datasets/Iris)
	KNN Test			-- ���Լ�(���� http://archive.ics.uci.edu/ml/datasets/Iris)


������ע�����
	�����г���ʱ��Ҫ���룺ѵ������·�� �� ���Ԥ���ǩ��·����  -- e.g. hadoop@master:~/ReadFileTest$ hadoop jar /home/hadoop/ReadFileTest/KNN.jar KNN /train/iris_train.csv /KNNans3
	ѵ���������ݸ�ʽΪ������ֵA,����ֵB,����ֵC��...,��ǩ       -- ����ֵ֮��Ҫ�ö��Ÿ���
	���Լ������ݸ�ʽΪ������ֵA,����ֵB,����ֵC��...     	    -- ����ֵ֮��Ҫ�ö��Ÿ���



