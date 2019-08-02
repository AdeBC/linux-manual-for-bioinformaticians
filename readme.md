# 给生信人的linux食用手册
### Linux recipe for BMC learners  

**适用于正在学习生物信息学的研究人员和学生，包括但不限于账户的登录与权限管理、软件的安装与启动、编程语言的快速入门、脚本的编写与调用和分析项目中跨语言的脚本组织与应用，本手册将系统地回答您以下问题——以索引到知识点的方式：**

---
**基础问题**
1. 如何为项目组员新建账户？
```
  useradd [username] # 根据需要替换[username]，默认不提供root授权
```
2. 如何为组员的账户添加或去除root授权？  
请查看->[用户管理](https://github.com/ChongHui-007/Linux-recipe-for-BMC-learners/blob/master/%E7%94%A8%E6%88%B7%E7%AE%A1%E7%90%86.md)  
3. 什么是[软件源](https://www.baidu.com/)？    
4. 如何更改操作系统默认的软件源？  
请查看->[中国科学技术大学镜像站点](http://mirrors.ustc.edu.cn/help/)  
4. 如何安装软件？  
请查看->[软件管理](https://github.com/ChongHui-007/Linux-recipe-for-BMC-learners/blob/master/%E8%BD%AF%E4%BB%B6%E7%AE%A1%E7%90%86.md)最后一部分  
10. 如何将一台服务器/个人电脑配置成生物信息学计算工作站？  
11. 什么是[发行版](https://www.baidu.com/)，我应该使用哪个 Linux 发行版？  
请查看->[发行版的选择与安装](https://github.com/ChongHui-007/Linux-recipe-for-BMC-learners/blob/master/%E5%8F%91%E8%A1%8C%E7%89%88%E7%9A%84%E9%80%89%E6%8B%A9%E4%B8%8E%E5%AE%89%E8%A3%85.md)  
---
**关于Python**
1. 网络上下载的代码编译出错
2. 如何更改默认的 Python 版本？
3. 如何合理配置 Python2 和 Python3 双版本共存？
4. 如何合理配置 conda2 和 conda3 双版本共存？
5. 已经安装了 Python 的 package，但仍显示 “no module named ...”  
请查看->[软件管理](https://github.com/ChongHui-007/Linux-recipe-for-BMC-learners/blob/master/%E8%BD%AF%E4%BB%B6%E7%AE%A1%E7%90%86.md)末尾的问题2  
5. 使用 pip 找不到要安装的包
6. 使用 conda 找不到要安装的包
7. 如何为 conda 添加软件源？
```
  conda config --add channels [channelname] # 根据需要替换[channelname]
```
---
**关于其它编程语言**
1. 为什么我需要学习如此多种编程语言？
2. 如何在服务器上启动 Rstudio？
2. 如何针对一门新的编程语言快速入门？我应当从哪些地方开始学起？
8. 我应该学习哪一门编程语言？
9. 对于学习 Python 等易读易写的语言来说，C++/C 等编程语言的基础是必须的吗？
---
**关于脚本组织**
1. 为什么我需要脚本组织？
2. 如何将各种语言编写的脚本粘在一起？
---
**关于解决问题**
1. 何为自顶向下和自底向上？
2. 为什么我需要利用自顶向下和自底向上来解决问题？
3. 如何利用它来解决问题？

---
**其它优秀学习资源推荐**

---
**参考内容**
