---
title: Elasticsearch集群关注指标
date: 2019-09-24 15:06:59
tags: Elasticsearch
---

需要持续关注的Elasticsearch集群指标

<!--more-->

## 基础监控(运维监控)
- CPU使用率
- IO
- 内存
- load
- 磁盘空间
- JVM

## 网关监控
- RT
- 状态码
- 当RT > 1s 或者出现5XX的时候

## 日志监控
- ES出现error日志

## 集群指标监控
- 集群级别监控
	1. status，集群健康状态
	2. nodes，节点数
- node级别监控
	1. indices
	2. thread_pool
	3. fielddata_breaker
- index级别监控
  基本上没有意义
