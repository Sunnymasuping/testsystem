---
title: 仓储管理与文字分析系统
date: 2024-03-012 10:15:09
tags:
  - 数据结构
  - 算法
  - 文字处理
  - 仓储管理
categories:
  - 软件开发
  - 数据处理
---

```md
# 仓储管理系统

## 基本功能

把货品信息表抽象成一个线性表，货品信息（包括 ID、货品名、定价、数量等）作为线性表的一个元素，实现：

- 按 ID、货品名分别查找某货品信息（包括 ID、货品名、定价、数量等）。
- 收录货品（如果货品在帐中已有，则只将总库存量增加。否则插入新增信息）。
- 售出货品（如果帐中还有存货，则只将总库存量减少。如果库存为 0，则提示售出失败）。
- 清除货品（删除该货品信息）、修改货品（ID、货品名和单价）。
- 排序（按定价排序--采用冒泡排序、按数量排序--采用快排）等功能。

## 基本要求

1. 分别采用单链表和顺序表实现相应功能。
2. 编写一个测试主函数，测试所实现的功能。

# 文字分析处理

## 基本功能

要求在输入一段文字后，程序能够对该段文字中的字符进行自动统计，将其中文字符、英文字符、空格以及数字数量分别统计出来。

## 基本要求

1. 采用线性表作为存储结构。
2. 所输入的一段文字能够在屏幕上被显示。
3. 统计结果，按照中文字符、英文字符、数字、空格以及总字数五个方面显示。
4. 给定单词计数，输入一个不含空格的单词，统计输出该单词在文本中的出现次数。
5. 用指定的字符串替换某一子串。
6. 编写一个测试主函数，测试所实现的功能。

## 代码仓库

[GitHub 项目地址](https://github.com/Sunnymasuping/storetextlab)
```
