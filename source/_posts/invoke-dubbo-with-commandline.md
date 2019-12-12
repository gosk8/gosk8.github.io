---
title: Dubbo命令行调用
date: 2019-09-24 15:20:23
tags: Dubbo
---

通过命令行方式来调用Dubbo的接口

<!--more-->

```
telnet <service_provider_ip> 20881

Dubbo>
Dubbo>ls
com.gtexpanse.demo.service.xxx
com.gtexpanse.demo.service.yyy

invoke com.xxx.service.xxx
```

