# Spark-Row-Count
数据集描述：
在这一部分中，你将需要实现一个简单的Spark应用程序。我们在北航云盘中[ https://bhpan.buaa.edu.cn/link/AA3F41728563AA4FF08F016276D15AB229]提供了一个数据文件，包含了一些IOT（物联网）设备收集的样本数据。
任务要求：
1. 要求首先使用Hadoop平台的Shell命令，将上述文件加载到本机的HDFS的某个文件目录中（依赖于课程前面实验环节在本机部署的Hadoop平台）。提示：可参考课程配套指南https://dblab.xmu.edu.cn/blog/2460/中的“一、利用Shell命令与HDFS进行交互”。
2. 要求在本机安装和部署Spark平台。提示：可参考课程配套实验指南https://dblab.xmu.edu.cn/blog/2501/中“一、安装 Spark2.4.0”进行Spark的安装和部署。
3. 要求在Spark Shell中读取HDFS上的上述文件，然后，统计出文件的行数。提示：可参考课程配套实验指南https://dblab.xmu.edu.cn/blog/2501/中“二、使用Spark Shell编写代码”进行Spark Shell代码编写和运行。
4. 要求编写基于Java语言的Spark应用程序，读取HDFS中的上述文件，然后，统计出文件的行数；随后要求使用Maven对Java独立应用程序进行编译打包，并将生成的jar包通过spark-submit提交到Spark中进行运行。提示：可参考课程配套实验指南https://dblab.xmu.edu.cn/blog/2501/中“（二）使用Maven对Java独立应用程序进行编译打包”进行Java应用程序的编写和运行。
