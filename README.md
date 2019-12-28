# trojan-wiz
一键安装trojan-gfw v2.0
## 安装前必须打开服务器的80和443端口
请参考：[视频教程](https://youtu.be/x-2qX6iqxgA)
- 已经添加自动续期功能，并且客户端无需下载证书。直接复制最后一屏的配置信息，在客户端创建client.json即可，无需再去下载证书。
- 已经将trojan使用简化到极限
- trojan无流量特证，流量完全是https流量，这是翻墙的最终境界
# 环境安装 （注意root环境下运行）
apt-get update -y

apt-get install build-essential devscripts debhelper cmake libboost-system-dev libboost-program-options-dev libssl-dev default-libmysqlclient-dev python3 curl openssl -y

---
# 安装命令：
> wget -N --no-check-certificate https://raw.githubusercontent.com/BlackTouma/trojan-wiz/master/ins.sh && chmod +x ins.sh && bash  ins.sh
---
支持的系统：
- ubuntu 16.04+
- debian 9(理论上应该支持debian 8)
- centos 7+
- RHEL 7+
