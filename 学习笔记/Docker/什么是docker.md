## 什么是docker?

#### IT软件中，Docker指容器化技术，用于支持创建和使用Linux容器。Docker 在容器的基础上，进行了进一步的封装，从文件系统、网络互联到进程隔离等等，极大的简化了容器的创建和维护。使得 Docker 技术比虚拟机技术更为轻便、快捷。

#### 虚拟机运行另一个操作系统，占用资源多，需要分配内存和硬盘，冗余，启动慢。而Linux 容器不是模拟一个完整的操作系统，而是对进程进行隔离。具有启动快，占用资源少，体积小，便于迁移等优点。

#### Docker 属于 Linux 容器的一种封装，提供简单易用的容器使用接口。 它是目前最流行的 Linux 容器解决方案。

#### Docker 将应用程序与该程序的依赖，打包在一个文件里面。运行这个文件，就会生成一个虚拟容器。程序在这个虚拟容器里运行，就好像在真实的物理机上运行一样。有了 Docker，就不用担心环境问题。

#### 总体来说，Docker 的接口相当简单，用户可以方便地创建和使用容器，把自己的应用放入容器。容器还可以进行版本管理、复制、分享、修改，就像管理普通的代码一样。
![virtual-machines](https://github.com/LzyRapx/Notes/blob/master/Docker/virtual-machines.png)
![docker](https://github.com/LzyRapx/Notes/blob/master/Docker/docker.png)
