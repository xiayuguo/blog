---
title: Python中字符串格式化符号和转义字符含义
date: 2017-04-12 15:36:26
tags: 
- Python
---
> 这篇文档整理自[鱼C论坛](http://bbs.fishc.com/forum.php?mod=viewthread&tid=39140&extra=page%3D1%26filter%3Dtypeid%26typeid%3D403), 感谢作者输出,我只是一枚搬运工...

<!--more-->
### 字符串格式化符号含义

|符号|说明|
|:---|:---|
|%c|格式化字符及其ASCII码|
|%s|格式化字符串|
|%d|格式化整数|
|%o|格式化无符号八进制数|
|%x|格式化字符号十六进制数|
|%X|格式化字符号十六进制数(大写)|
|%f|格式化定点数,可指定小数点后的精度|
|%e|用科学计数法格式化定点数|
|%E|作用同%e, 用科学计数法格式化定点数|
|%g|根据值的大小决定使用%f或%e|
|%G|作用同%g, 根据值的大小决定使用%f或者%E|

### 格式化操作符辅助指令

|符号|说明|
|:---|:---|
|m.n|m是显示的最小总宽度,n是小数点后的位数|
|-|用于左对齐|
|+|在正数前面显示加好(+)|
|#|在八进制数前面显示'0o', 在十六进制数前面显示'0x'或'0X'|
|0|显示的数字前面填充'0'取代空格|

### 字符串转义字符含义

|符号|说明|
|:---|:---|
|\'|单引号|
|\"|双引号|
|\a|发出系统响铃声|
|\b|退格符|
|\n|换行符|
|\t|横向制表符(TAB)|
|\v|纵向制表符|
|\r|回车符|
|\f|换页符|
|\o|八进制数代表的字符|
|\x|十六进制数代表的字符|
|\0|表示一个空字符|
|\\|反斜杠|