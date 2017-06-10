# distributedSystem
参考MIT6.824的课程,实现课程要求的所有lab.
因为课程的要求,所以不能把代码公开.
写下这些,记录自己的学习之路,如果可以给需要的同学带来一些帮助就更棒了.


lab1(simple)
    翻译文档(不完整)见:doc/lab1_MapReduce.txt
    part1:实现MR中的两个功能
	1.处理输入文件并将map()输出的key-value,以json格式保存到中间文件中.
	2.收集中间文件,将其传给对于的reduce()并收集reduce()的输出结果一以json的形式保存到结果文件中.

    part2:实现一个单词统计的MapReduce程序

    part3:实现mr中的任务调度,无mater容错,无worker容错

    part4:在part3上的基础上增加容错功能

    part5:实现一个简单倒排索引的MapReduce程序

	    
