test_modules_efficiency
=======================

test original module efficiency

一个长度为1000的list，max函数的结果很明显：
max iteration: 6.85511016846 
max original: 0.713296890259
max iteration: 6.77465510368 
max original: 0.699170827866

长度为100的list，sort函数的结果如下:
sort iteration: 31.4509849548 
sort original: 1.15701317787
果然啊，效率差距惊人。

两种打乱字符串的方法的效率对比：
string shuffle with list: 168.345906019,
string shuffle with sample: 207.21715498
先转化为list的效率更高

具体说明：http://blog.csdn.net/gt11799/article/details/40157239
