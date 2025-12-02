---
title: "CosMx 数据分析与数学原理"
date: 2025-12-02T15:00:00+08:00
draft: false
tags: ["Bioinformatics", "Math", "R"]
categories: ["Study"]
# 开启数学公式支持
math: true
---

## 1. 简介
这是一篇模仿 hin233 风格的测试文章。

## 2. 数学公式测试 (LaTeX)
我们在研究隐函数求导时，经常用到以下公式：

$$
\frac{dy}{dx} = -\frac{F_x}{F_y}
$$

或者行内公式：若 $f(x) = x^2$，则 $f'(x) = 2x$。

## 3. 代码高亮测试 (R语言)
读取 `LiverDataRelease` 数据的代码示例：

```r
# 加载库
library(Seurat)
library(ggplot2)

# 设置路径
data_path <- "/Users/hank/Desktop/数据/LiverDataRelease"

# 这是一个注释
print("Hello, FixIt Theme!")