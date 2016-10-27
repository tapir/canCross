[![Docker Stars](https://img.shields.io/docker/stars/mrjin/shadowsocks.svg?style=flat-square)](https://hub.docker.com/r/mrjin/shadowsocks/)    [![Docker Pulls](https://img.shields.io/docker/pulls/mrjin/shadowsocks.svg?style=flat-square)](https://hub.docker.com/r/mrjin/shadowsocks/)    [![license](https://img.shields.io/github/license/jinfeijie/Docker.svg?style=flat-square)](https://github.com/jinfeijie/Docker)    [![Docker Automated buil](https://img.shields.io/docker/automated/mrjin/shadowsocks.svg?style=flat-square)](https://hub.docker.com/r/mrjin/shadowsocks/)    [![Libraries.io for GitHub](https://img.shields.io/librariesio/github/jinfeijie/Docker.svg?style=flat-square)](https://github.com/jinfeijie/Docker)

 [![GitHub forks](https://img.shields.io/github/forks/jinfeijie/Docker.svg?style=social&label=Fork&style=plastic)](https://github.com/jinfeijie/Docker)    [![GitHub stars](https://img.shields.io/github/stars/jinfeijie/Docker.svg?style=social&label=Star&style=plastic)](https://github.com/jinfeijie/Docker)    [![Github Releases (by Release)](https://img.shields.io/github/downloads/jinfeijie/Docker/1.0.1/total.svg?style=plastic)](https://github.com/jinfeijie/Docker/releases)
### Docker 飞机与OPENSSH开机启动

设置了3个环境变量 `SSH_PASSWORD` `SS_PASSWORD` `PORT`

* `SSH_PASSWORD`  SSH密码 默认`jin123`
* `SS_PASSWORD`  SS飞机密码  默认`jin123`
* `PORT`  SS飞机端口  默认`8888`

### 云平台（例如：[daocloud云](https://www.daocloud.io/)、[arukas](https://app.arukas.io)的代码构建平台均会直接用默认参数构建）
云平台下的构建无法修改参数，fork后修改如下参数
```
ENV SSH_PASSWORD    jin123
ENV SS_PASSWORD     jin123
ENV PORT            8888
```

如果遇到SS纸飞机无法连接的情况，可以通过ssh登录，`ps -ef`查看服务是否启动。如果服务中没有SS纸飞机服务，可以在命令行输入`CMD`启动。

其他问题[me@jinfeijie.cn](mailto:me@jinfeijie.cn)

欢迎 Star && Fork
