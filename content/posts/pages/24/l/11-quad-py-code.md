+++
title = 'quad py code'
date = '2024-12-22T17:55:52+07:00'
type = 'xpage2'
draft = false
categories = ['pages']
tags = ['slide-lib']
authors = ['viridi']
url = '24l11'
+++

<!--more-->
```py
x = []
y = []
a = 1
x1 = 3
x2 = 7
for xi in range(1, 9):
  yi = a * (xi - x1) * (xi - x2)
  x.append(xi)
  y.append(yi)
print(x)
print(y)
```