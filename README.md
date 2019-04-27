## 搭建科学上网工具VPN

### 安装 Shadowsocks

##### 特点

一键安装 Shadowsocks-Python， ShadowsocksR， Shadowsocks-Go， Shadowsocks-libev 版（四选一）服务端

##### 安装wget

```shell
yum -y install wget
```

##### 安装服务

```shell
#下载服务
wget --no-check-certificate https://raw.githubusercontent.com/quniu/shadowsocks-all/master/install/shadowsocks-all.sh

#更改权限
chmod +x shadowsocks-all.sh

#运行脚本
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

##### 效果

![1556375225(1)](C:\Users\Administrator\Desktop\1556375225(1).png)

------

### 安装加速器

##### 特点

BBR + BBR魔改 + Lotsever(锐速) ，三款加速器

##### 安装服务

```shell
#下载脚本
wget -N --no-check-certificate "https://raw.githubusercontent.com/dlxg/Linux-NetSpeed/master/tcp.sh"

#更改权限
chmod +x tcp.sh 

#运行脚本
./tcp.sh
```

##### 效果

![1556375588081](C:\Users\ADMINI~1\AppData\Local\Temp\1556375588081.png)