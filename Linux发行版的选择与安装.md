# Linux 发行版的选择与安装
### 


是的，在进行任何后续操作之前，为您的工作站安装一个合适的 Linux 发行版本是至关重要的。
为了向您解释清楚何为发行版本，我需要先解释一些其它概念。让我们先从Linux项目的开源特性开始。  
您可能已经知晓 Linux 是自由软件/开源软件，您或许也听说过“自由软件”这个词、或者已经对它有一定的了解。但为了阐述方便，请让我为您简要说明——什么是自由软件？  
一句话说：
> 自由软件就是您可以自由地安装、使用、修改和再发行的软件。  
  
如果您想要了解自由软件的方方面面，可以仔细阅读由 Debian 撰写的介绍页面——[何谓自由](https://www.debian.org/intro/free.zh-cn.html)
和维基百科页面[自由软件](https://zh.wikipedia.org/wiki/%E8%87%AA%E7%94%B1%E8%BD%AF%E4%BB%B6)  

## 概述  
Linux 发行版的开发就是在自由软件为潮流的背景下流行起来的。因为相较于以往的商业公司主导的软件开发，用户个人有对源代码进行修改的权利，
自由软件许可证允许用户自行完善该软件，也相当于用户可以在作者开发的基础之上进行再开发，把它变成自己的东西——这当然能够为用户省下大量时间。
因此，全世界的 Linux 发行版数量正在越来越多。  
但尽管如此，Linux 操作系统只是生信人的工具而已，
我们没有必要关注太多个发行版，只需要挑选其中某一个适合自己的版本便可。在诸多发行版本的不同当中，影响稍大的就是发行版使用的包管理器。
在诸多 Linux 软件的包管理器中，得到用户认可较多的有三个：apt、yum、pacman+aur。其分别属于Debian系、Redhat系和Arch系发行版。  
但尽管其影响稍大，由于生信人使用的软件大多是成熟且稳定的，因此上述三个包管理器都能基本满足需要。
但Arch系发行版因为滚动更新等问题容易“滚崩”所以不太适合长期安装在服务器上。因此我推荐Ubuntu和Cent OS，其分别属于Debian系和Redhat系。  

## 安装  
安装系统一般需要完成如下流程：  
![github](https://github.com/ChongHui-007/Linux-recipe-for-BMC-learners/blob/master/material/Installations-1.jpg)  
### 安装Ubuntu  
镜像下载：  
[中国科学技术大学](http://mirrors.ustc.edu.cn/ubuntu-releases/)    [清华大学](https://mirrors.tuna.tsinghua.edu.cn/ubuntu-releases/)    [南京大学](http://mirrors.nju.edu.cn/ubuntu-releases/)    [上海交通大学](http://ftp.sjtu.edu.cn/ubuntu-cd/)    [华为云](http://mirrors.huaweicloud.com/repository/ubuntu-releases/)  
安装教程：  
服务器版：[Tutorial-install-ubuntu-server](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-server)  
PC版：[Tutorial-install-ubuntu-desktop](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-desktop)  


### 安装Centos
镜像下载：  
[南京大学](http://mirrors.nju.edu.cn/centos/)    [上海交通大学](http://ftp.sjtu.edu.cn/centos/)    [清华大学](https://mirrors.tuna.tsinghua.edu.cn/centos/)    [阿里云](http://mirrors.aliyun.com/centos/)    [华为云](http://mirrors.huaweicloud.com/centos/)    [网易云](http://mirrors.163.com/centos/)  
安装教程：[Install-guide](https://docs.centos.org/en-US/centos/install-guide/)


若您想要了解更多个 Linux 发行版，可以在[Distrowatch](https://distrowatch.com/)上自行探索。
若您想全面了解 Ubuntu 和 Centos 发行版，可以上[Ubuntu官网](https://ubuntu.com/)和[Centos官网](https://www.centos.org/)自行探索和了解。
