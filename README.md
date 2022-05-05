<h1 align="center">全新界面，支持ETH，ETC，BTC抽水稳定不掉线，作者抽水千分之三。</h1>
<h4 align="center">最强大的矿池中转，原创GO语言编写，性能强大。支持绝大部分币种的转发、加密、自定义抽水、数据统计、配套隧道工具。</h4>
<h4 align="center">

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-2.1.0_ETHASH-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_05_05-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Language-GoLang-green.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/License-Apache-green.svg" alt="travis">
  </a>
</p>

![1](https://user-images.githubusercontent.com/104977639/166905040-e7f32950-6e15-4c49-bc5d-e2e3e2167361.png)

# 重要提示必看
#### 1.默认端口:16777
#### 2.默认账号:admin 默认密码:admin123
#### 3.首次安装完成请先重启服务器
#### 4.安装完成后，请立即修改默认密码以及后台默认端口

# 矿工交流 TG电报群：https://t.me/JJ_MinerProxy
#### 联系我们：[Telegram 讨论群组(欢迎向我们提出建议)](https://t.me/JJ_MinerProxy)、[GitHub](https://github.com/JJMinerProxy/MinerProxy)
#### 联系我们：QQ群：942989790

# Liunx-一键安装脚本
好处：适合又想要Linux稳定性的，又不懂Linux的小白的学习者<br />
功能：包含自启动和进程守护，重启后可以自动运行，会放开防火墙和连接数限制，一键搞定<br />
要求：Ubuntu 16+ / Debian 8+ / CentOS 7+ 系统<br />
使用 root 用户输入下面命令安装或卸载<br />
```bash
# 一键安装脚本
bash <(curl -s -L https://raw.githubusercontent.com/JJMinerProxy/MinerProxy/main/MinerProxy_install.sh)
# 一键安装脚本 - 备用
bash <(curl -s -L https://cdn.jsdelivr.net/gh/JJMinerProxy/minerProxy@master/MinerProxy_install.sh)
```
### 输入命令回车之后一直卡住不动，换这种办法
ubuntu/debian 系统安装
```bash
wget: apt-get update -y && apt-get install wget -y
```
centos 系统安装
```bash
yum update -y && yum install wget -y
```
安装好 wget 之后 下载脚本并执行
```bash
wget https://raw.githubusercontent.com/JJMinerProxy/MinerProxy/main/MinerProxy_install.sh
bash install.sh
```

### 提示 curl: command not found的先安装curl
ubuntu/debian 系统安装 curl 方法: 
```bash
apt-get update -y && apt-get install curl -y
```
centos 系统安装 curl 方法: 
```bash
yum update -y && yum install curl -y
```
安装好 curl 之后就能安装脚本了
