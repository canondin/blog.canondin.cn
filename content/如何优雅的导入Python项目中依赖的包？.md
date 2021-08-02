---
title: "如何优雅的导入Python项目中依赖的包？"
date: 2021-08-03T00:17:09+08:00
draft: true
---

> [官方文档](https://docs.python.org/zh-cn/3/tutorial/venv.html)

## 创建虚拟环境

```bash
python3 -m venv test_venv
```

## 激活虚拟环境(**Mac 环境**)

```bash
source test_venv/bin/activate
```

## 一顿安装，（设置了阿里云的镜像，速度飞快）

```bash
python3 -m pip install -r requirements.txt
```