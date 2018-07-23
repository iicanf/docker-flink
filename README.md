docker-flink
============

fork from [docker-flink](https://github.com/docker-flink/docker-flink) ,and i will keep all the feature, and now i focus on this variant [scala_2.11-debian](https://github.com/iicanf/docker-flink/tree/master/1.5/scala_2.11-debian) 

make changes:

* add vim to debian
* change the apt source form `ded.debian.org` to `mirrors.tuna.tsinghua.edu.cn`

roadmap 

* react the [docker-entrypoint.sh](https://github.com/iicanf/docker-flink/blob/master/1.5/scala_2.11-debian/docker-entrypoint.sh) for [zookeeper HA](https://github.com/31z4/zookeeper-docker) 


docker-flink （中文）
========================

克隆自[docker-flink](https://github.com/docker-flink/docker-flink)，保留所有的功能，主要精力集中在[scala_2.11-debian](https://github.com/iicanf/docker-flink/tree/master/1.5/scala_2.11-debian) 变种

修改列表：

* 添加vim，方便到容器查看日志
* 修改debian的apt源为清华源

待做列表：
* 修改 [docker-entrypoint.sh](https://github.com/iicanf/docker-flink/blob/master/1.5/scala_2.11-debian/docker-entrypoint.sh)，配合[zookeeper](https://github.com/31z4/zookeeper-docker) 实现flink jobmanager的高可用


License
-------

Licensed under the Apache License, Version 2.0: https://www.apache.org/licenses/LICENSE-2.0

Apache Flink, Flink®, Apache®, the squirrel logo, and the Apache feather logo are either
registered trademarks or trademarks of The Apache Software Foundation.
