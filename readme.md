### 简介

这是为了方便大家做各个镜像仓库代理的

### 操作

如果你想要启动所有的镜像仓库直接执行 

`docker-compose up -d`

但是你想要单独代理某一个仓库就直接进入那个文件夹

`cd dockerhub`

`docker-compose up -d`

就好了

每一个镜像仓库对外的端口都是不一样的，当然你也可以使用nginx统一反向代理一下

### 注意

大家可以看下配置文件

默认168h小时之后会清理缓存，也就是你拉取的镜像缓存

喜欢的给个star哦！！！！

### 广告位

我的tg频道 [https://t.me/bboyapp](https://t.me/bboyapp)
