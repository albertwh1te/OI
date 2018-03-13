# 题目

高橋君正考虑在美国留学，并决定提交一份成绩单。
在美国留学的成绩表中，有必要标明gpa作为衡量学力的指标。
gpa是通过将每个单元的评估（a，b，c，d，f）转换成分数并转换成分数而获得的平均值如下。

- a评估→4分
- b评估→3分
- c评估→2分
- d评估→1分
- f评估→0分

如果全部f，gpa将为0。
根据每个高桥单位的评估找出全球气候变化大会。

## 输入

输入从标准输入中以以下形式输入

>N
>
>r1r2……rN

第一行是表示，总数N（1≦N≦100）。

第二行，给出了表示单位的评价的N个字的字符串。

第i个字ri是A，B，C，D，F中的任何一个。

## 输出

以输入和单位的评价为基础算出学业成绩从标准输出一行。

误差在1e-9以下（1-e9＝10^-9）

另外，输出要换行。

## 例1 输入

>34
>ABABAAABACDDDABADFFABABDABFAAABFAA

### 例1 输出

> 2.79411764705882

各评价的个数如下。

A评价…16个

B评价…8个

C评价…1个

D评价…5个

F评价…4个

因此，分数的总和4×16 + 3×8 + 2×1 + 1×5 + 0×4 = 95%，平均95÷34 = 2.79411764705882。

## 例2 输入

>5
>FFFFF

### 例2 输出

>0

由于评价f有5个，所以gpa为（0×5）÷5 = 0。