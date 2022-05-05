<div align="center">

# KENC文档说明-本地加密客户端

</div>

<p id="kenc"></p>

### KENC是本地->远程KENC协议加密隧道，局域网部署在一台设备上即可，可与远程MinerProxy通过KENC协议进行通信。

<a href="https://github.com/JJMinerProxy/MinerProxy/raw/main/KENC/kenc_v_win.exe">点击下载WINDOWS客户端</a>

<a href="https://github.com/JJMinerProxy/MinerProxy/raw/main/KENC/kenc_v_linux">点击下载LINUX客户端</a>

### 使用环境
```
MinerProxy版本>=2.1.0
```

## 使用说明

### 1.远程MinerProxy先配置一个KENC协议的端口

<img width="630" alt="1" src="https://user-images.githubusercontent.com/104977639/166899031-2fd3b570-2527-4d25-8402-0922d3dfc8d0.png">

### 2.本地找一台电脑运行KENC, 运行成功后会提示, 根据提示访问地址去配置自己的KENC客户端

<img width="924" alt="2" src="https://user-images.githubusercontent.com/104977639/166899073-e0f161fa-bf1c-4f5a-b1eb-d6a5b993134d.png">

### 3. 打开网页kenc客户端, 默认密码：admin123

<img width="1437" alt="3" src="https://user-images.githubusercontent.com/104977639/166899118-9dfc08b7-330d-45cc-9a79-f0b19038a73c.png">

### 4. 添加本地端口

<img width="1117" alt="4" src="https://user-images.githubusercontent.com/104977639/166899143-2fee7934-d851-4d86-89c8-460e2db13911.png">

<ul>
    <li>先随便填写个本地端口 小于65535的数字</li>
    <li>本地协议选择TCP或SSL，选择采矿设备支持的协议即可</li>
    <li>目标地址填写远程的KTMinerproxy的连接地址，链接地址为远程ip:端口号</li>
    <li>最大连接数默认无上限</li>
</ul>

### 5. 局域网的所有采矿设备的连接地址填写局域网安装KENC的设备IP地址+本地端口号即可, 通常直接连接图内地址即可

<img width="1825" alt="5" src="https://user-images.githubusercontent.com/104977639/166899164-fd75462d-7395-4d71-b96d-0afc4b0ef2b2.png">
