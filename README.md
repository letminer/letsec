
<h1 align="center">
  <br>
  <img src="https://github.com/letminer/letsec/blob/main/images/logo.png" width="400"/>
</h1>

<h4 align="center">letsec 加密隧道
<br />Go语言原生开发，letminer专用加密客户端。
<br />私有加密协议，安全性更高、更稳定，防嗅探、防扫描，矿厂必备。
<h4 align="center"><a style="color:red" href="https://github.com/letminer/MinerProxy">配合 letminer 矿机代理使用 >></a></h4>
<div align="center" style="font-weight:bold">要求 letminer 版本 >= v2.0.0</div>

# · Liunx安装 / 一键脚本

推荐系统：Ubuntu 16+ / Debian 8+ / CentOS 7+，使用 root 用户输入下面命令安装或卸载<br />
```bash
# 一键脚本
bash <(curl -s -L https://raw.githubusercontent.com/letminer/letsec/main/install.sh)

# 备用  一键脚本 - 如无法访问github，使用如下备用脚本
bash <(curl -s -L https://cdn.jsdelivr.net/gh/letminer/letsec@main/install.sh)
```
### 如果一键脚本卡住不动，按照以下两步走
#### 1、安装 wget 下载工具
ubuntu/debian 安装
```bash
apt-get update -y && apt-get install wget -y
```
centos 安装
```bash
yum update -y && yum install wget -y
```

#### 2、利用 wget 下载一件脚本并执行
```bash
wget https://raw.githubusercontent.com/letminer/letsec/main/install.sh
bash install.sh
```

# · Windows安装 / 直接下载双击
      1、点击项目右侧 Code，直接选择 Download ZIP 下载zip压缩包，
      2、解压下载的压缩包，双击 windows_run.bat 即可。

# ·  重要提示
##### 1、Linux系统第一次安装完成后请重启服务器，连接限制修改方可生效！
##### 2、安装完成后，请立即修改默认密码！
##### 3、如需更换内置SSL证书，请将证书文件命名为 server.key 与 server.pem ,并放置于程序安装目录下！

# ·  版本更新日志

    2022/06/23 v1.0.0  发布第一个版本；
                       letminer（版本>=2.0.0）专用本地加密客户端。

# · 联系我们：
##### Telegram技术交流群：https://t.me/letminers
##### 欢迎建议、使用反馈、定制需求，电报群直接私聊群主
<div align="left">
<img title="开发者Telegram" src="https://cdn.jsdelivr.net/gh/letminer/MinerProxy@main/images/letminers.jpg" width="200"/>

<img title="技术交流Telegram群" src="https://cdn.jsdelivr.net/gh/letminer/MinerProxy@main/images/letminer.jpg" width="200"/>
</div>
