# 面试题


## 进程和线程的区别


参考地址：

https://zhuanlan.zhihu.com/p/511095546


特点|进程|线程
-|-|-
资源分配|是系统进行资源分配和调度的基本单位|继承和共享进程的资源，不能单独的分配
调度方式|子进程与父进程等竞争|子线程与父线程平等竞争
通信方式|A.共享内存<br>B.消息队列<br>C.信号量<br>D.有名管道<br>E.无名管道<br>F.信号<br>G.文件<br>H.socket|A.互斥量<br>B.自旋锁<br>C.条件变量<br>D.读写锁<br>E.线程信号<br>G.全局变量


##  12-Factor原则




12-Factor是一个软件开发方法论，提出了一组关于构建现代Web应用程序的12个最佳实践原则，目的是使应用程序易于开发、部署和维护。以下是12-Factor原则的概述：

1. 代码库：将代码与配置分离，并使用版本控制系统来管理代码库。
2. 依赖项：明确地声明和隔离依赖项，确保每个环境都使用相同的依赖项版本。
3. 配置：将应用程序的配置从代码中分离，并使用环境变量来传递配置信息。
4. 后端服务：将后端服务视为附加资源，并将其绑定到应用程序中。
5. 构建、发布、运行：使用持续集成和持续交付来自动化构建、发布和部署过程。
6. 进程：将应用程序视为一组相互协作的进程，每个进程都具有单一的责任。
7. 端口绑定：将应用程序作为一个独立的服务进行绑定，并将其公开在一个端口上。
8. 并发：在应用程序中使用进程模型来实现并发处理。
9. 扩展性：通过水平扩展来提高应用程序的性能，而不是通过垂直扩展。
10. 可替换性：设计应用程序以支持替换和重建，以确保应用程序的可靠性。
11. 日志：将应用程序的日志视为事件流，并将其存储到本地文件或日志聚合服务中。
12. 管理进程：将管理任务与应用程序的代码库分离，并将其视为单独的进程。


这些原则为开发人员提供了一些指导，帮助他们构建可靠、可扩展和易于维护的现代Web应用程序。


## k8s知识体系

https://www.processon.com/view/link/5d7f7d08e4b03461a3a937e2

K8s

1. 部署

- minikube

https://kubernetes.io/docs/tutorials/hello-minikube/

- kubeadm

- kubespray

https://github.com/kubernetes-sigs/kubespray


2. 架构

- master
- node
- addonss


3. workloads


4. 网络


5. 存储


6. 应用


7. 运维


8. 开发

