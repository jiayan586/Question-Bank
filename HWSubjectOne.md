# 20210319专业级科目一（java）题一
## 题目描述
<p>假设X-UTF是一种新的变长字节编码方式，每一个不同的字符，都拥有不同的编码，为n个字节（n的范围为[1,6]）</p>
当n = 1时，第一位为0，后面为有效值;
当n > 1时，第一个字节的前n位为1，第n+1位为0，后面的所有字节的前2位为10其它为有效值;

样例：
n = 1:  0xxxxxxx
n = 2:  110xxxxx  10xxxxxx
n = 3:  1110xxxx  10xxxxxx  10xxxxxx
n = 4:  11110xxx  10xxxxxx  10xxxxxx  10xxxxxx

所有有效值拼接到一起，形成的十进制值为字符的编号。
比如：
假设n=2时,110<font color = 'red'>xxxxx</font>  10<font color = 'blue'>xxxxxx</font>  -->  <font color = 'red'>xxxxx</font><font color = 'blue'>xxxxxx</font>  -->  转十进制输出

## 解答要求
未知

## 输入
<p>十六进制数</p>

## 输出
<p>判断是否满足X-UTF编码方式，若不满足输出 -1，若满足输出十进制编码值</p>

## 样例
### 输入样例 1:
```
A84F
```
### 输出样例 1:
```
-1

```
## 提示
