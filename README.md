Welcome to the Calculator wiki!

一、概述
=
该项目可以解析算术表达式得到运算结果，例如：new Calculator.calculate("|5-10|")返回double类型的5('|'为绝对值符号）。本项目支持20+个运算符，基本上在计算器中能看到的运算符都包含了，如果大家有什么新的运算符想要加入，欢迎提出建议～

除基本的算术表达式解析功能外，本Calculator还支持变量功能，具体的含义及用法见下面的详细介绍（本功能可以很方便的输出一系列的点集

二、使用方法
=
1. 基本功能的使用：
-----

本Calculator目前支持的运算符有(a、b、c均为实数)：

- 1、'+'(加)使用示例：a+b 代表a加b,
- 2、'-'(减)使用示例：a-b 代表a减b,
- 3、'*'(乘)使用示例：a*b 代表a乘b,
- 4、'/'(除以)使用示例：a/b 代表a除以b(b!=0),
- 5、'%'(取余)使用示例：a%b 代表a对b取余（我应该没有读错吧...),
- 6、'-'(取负)使用示例：-a 代表对a取负,
- 7、'^'(幂运算)使用示例：a^b 代表a的b次幂, 
- 8、'sin'(正弦)使用示例：sin(pi/2) 代表求pi/2的正弦，其中pi为内置Calculator的常量π, 
- 9、'cos'(余弦)使用示例：cos(pi/3) 代表求pi/3的余弦, 
- 10、'tan'(正切)使用示例：tan(pi/4) 代表求pi/4的正切,
- 11、'asin'(反正弦)使用示例：asin(1) 代表求1的反正弦, 
- 12、'acos'(反余弦)使用示例：acos(1) 代表求1的反余弦, 
- 13、'atan'(反正切)使用示例：atan(1) 代表求1的反正切, 
- 14、'log...\~...'(对数运算)使用示例：log(a)\~(b) 代表以a为底b的对数，a > 0 && a != 1 && b > 0, 
- 15、'lg'(以10为底的对数运算)使用示例：lg(a) 代表以10为底a的对数，a > 0, 
- 16、'ln'(以e为底的对数运算)使用示例：ln(e) 代表以e为底e的对数，其中e为自然对数是Calculator的内置常量, 
- 17、'sqrt'(求平方根)使用示例：sqrt(a) 代表求a的平方根，a >= 0, 
- 18、'!'(阶乘)使用示例：a! 代表求a的阶乘，a为非负整数, 
- 19、'('(左括号)使用示例：2*(1+4), 
- 20、')'(右括号)使用示例：如例19, 
- 21、'|'(绝对值符号)使用示例：|-10| 代表负10的绝对值