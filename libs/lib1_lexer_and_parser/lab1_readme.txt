Part A: SLP Interpreter and Compiler

Exercise 1:
	根据SLP的语法，第一条语句是赋值语句，讲5+3的值赋给a；第二条语句也是赋值语句，但要先处理右边的括号部分，在括号中先执行左边部分再处理右边，即打印a，和a-1的值，然后将10*a返回。第三条语句打印b的值。
	输出为：8 7 
		80

Exercise 2：
	src/slp/Slp.java中Slp类的设计完全遵照课本中GRAMMAR 1.3: A straight-line programming language.的语法设计。
	src/slp/Samples中prog对象的编码就是课本中Figure 1.4: Tree representation of a straight-line program.这个树形结构的实现。
