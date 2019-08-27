# idea-jdksource
idea中的继承树的配置

看源码的时候,有时候我们只想看jdk中的继承树关系,该仓库就基于idea.
查看继承关系时只显示jdk中的继承关系
基于jdk1.8


## 集成步骤

### 1.初始化idea工程
### 2.将git上下载的scopes文件夹放入工程的.idea目录下
### 3.选中一个类,然后按住 crtl+H 打开 Type Hierarchy(或者 导航栏中  navigate->Type Hierarchy)
  如下图:
  ![image](https://github.com/Finux168/idea-jdksource/tree/master/images/TypeHierarchy.png)
  选中jdksource就能够查看只有jdk的继承树了
