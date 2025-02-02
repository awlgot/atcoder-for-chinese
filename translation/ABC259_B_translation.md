## 题意

在一个 $x$ 轴向右，$y$ 轴向上的坐标平面上，逆时针旋转一个点 $(a,b)$ 绕原点 $d$ 度，得到新点的坐标。

## 数据范围

- $-1000 \leq a,b \leq 1000$

- $1 \leq d \leq 360$

- 所有数都是整数。

## 输入格式

一行三个整数 $a,b,d$

## 输出格式

一行两个实数 $x,y$ 表示旋转后点的坐标为 $(x,y)$。

请注意，当输出的每个数的绝对误差或相对误差不超过 $10^{-6}$ 时，您的输出将认为是正确的。

## 样例

### 样例输入1

```
2 2 180
```

### 样例输出1

```
-2 -2
```

### 样例输入2

```
5 0 120
```

### 样例输出2

```
-2.49999999999999911182 4.33012701892219364908
```

### 样例输入3

```
0 0 11
```

### 样例输出3

```
0.00000000000000000000 0.00000000000000000000
```

### 样例输入4

```
15 5 360
```

### 样例输出4

```
15.00000000000000177636 4.99999999999999555911
```

### 样例输入5

```
-505 191 278
```

### 样例输出5

```
118.85878514480690171240 526.66743699786547949770
```












