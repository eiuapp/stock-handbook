---
date: 2019-01-08T21:07:13+01:00
title: "HQ_Collector_V320"
weight: 11
keywords:
- 学习笔记
- stock
description : "实时行情数据接口HQ_Collector_V320"
---


https://www.55188.com/thread-4154233-1-1.html  

## 下载

保存到了百度云

## 读文档

`帮助.Txt`

## 配置

打开 `HQCollector.ini`

```
[SYSTEM]
HQFILE=MXHQ.TXT
HQFORMAT=1
SOURCE=0

[EXCHANGE]
UPDATE_OFF=25
MATCH_TIME=9:15	9:25
TIME_SEGMENT1=9:30	11:30
TIME_SEGMENT2=13:00	15:00

[TDXW]
PATH=C:\new_tdx
NAME=TdxW.exe
ZXGBAK=1

[DZHW]
PATH=D:\dzh365
NAME=Dzh2.exe

[STOCK]
CODE0=0000530
CODE1=0002052
CODE2=0002088
CODE3=0300010
CODE4=0300011
CODE5=1600301
CODE6=1600302
CODE7=1600303
CODE8=1600305
```

这样，就会生成 `MXHQ.TXT` 文件，然后，对些文件，进行 watch 就可以了。