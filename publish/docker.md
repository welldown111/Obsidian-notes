



- docker start xxx：启动已停止的容器(重新执行之前的run指令)
- docker stop xxx：停止运行中的容器
- docker rm xxx：可以删掉这个容器（发现运行有问题需要这样做以免之后部署重复）

- docker ps：看运行中的
- docker ps -a：看所有的
- docker logs -f xxx：可以看到容器运行的log，==常用==
- docker logs xxx：应该就是只会输出一次没法持续查看。

- docker images：查看有哪些镜像，有些占空间的话之后可以删掉。- 
