# Liunx命令

## shadowsocks-all.sh
- 自动安装CentOS / Debian / Ubuntu的Shadowsocks服务器（所有版本）
```
wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ss-go.sh
chmod +x ss-go.sh
bash ss-go.sh
```
## Linux-NetSpeed
```
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh"
chmod +x tcp.sh
./tcp.sh
```
## ServerStatus-Hotaru
```
wget https://raw.githubusercontent.com/CokeMine/ServerStatus-Hotaru/master/status.sh
服务端:bash status.sh s
客户端:bash status.sh c
```
## 一键MTProto
```
wget -N --no-check-certificate https://raw.githubusercontent.com/iiiiiii1/doubi/master/mtproxy_go.sh && bash mtproxy_go.sh
```
## 开root权限代码
```
#!/bin/bash
echo root:7758521kkk |sudo chpasswd root
sudo sed -i 's/^#\?PermitRootLogin.*/PermitRootLogin yes/g' /etc/ssh/sshd_config;
sudo sed -i 's/^#\?PasswordAuthentication.*/PasswordAuthentication yes/g' /etc/ssh/sshd_config;
sudo reboot
```
## Oracle开所有端口
```
sudo iptables -P INPUT ACCEPT
sudo iptables -P FORWARD ACCEPT
sudo iptables -P OUTPUT ACCEPT
sudo iptables -F
```
## 常用screen参数
```
screen -S yourname      -> 新建一个叫yourname的session
screen -ls              -> 列出当前所有的session
screen -r yourname      -> 回到yourname这个session
screen -d yourname      -> 远程detach某个session
screen -d -r yourname   -> 结束当前session并回到yourname这个session
```
## 编译Openwrt

[coolsnowwolf-lede-编译自己需要的 OpenWrt 固件](https://github.com/coolsnowwolf/lede "openwrt编译")



