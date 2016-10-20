---
layout:     post
title:      LVS管理系统实现思路
category:   project
description: LVS管理系统实现思路
---


- 项目适用于LVS+keepalvied架构的服务器
- 项目没有开源， 因为即使开源也不可能100%试用，所以这里只给出了大概思路。

![image](/images/lvsmanage/index.jpg)
![image](/images/lvsmanage/datacenter.jpg)
![image](/images/lvsmanage/globalconfig.jpg)
![image](/images/lvsmanage/globalconfigedit.jpg)
![image](/images/lvsmanage/clustermanager.jpg)
![image](/images/lvsmanage/addcluster.jpg)
![image](/images/lvsmanage/clustrole.jpg)
![image](/images/lvsmanage/remotepush.jpg)
![image](/images/lvsmanage/back.jpg)


会先进行对比，对比无误后推送到远程服务器