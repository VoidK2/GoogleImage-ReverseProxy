# GoogleImage-ReverseProxy
- caddy -- http server
- 反向代理了google.com.hk，想要其他功能，自己改脚本吧
## 执行
```bash
wget -qO- https://raw.githubusercontent.com/VoidK2/GoogleImage-ReverseProxy/master/googleimage.sh |bash
```
## 加权
```bash
chmod +x ./Google_images.sh
```
## 关闭防火墙
```bash
systemctl stop firewalld
```
或
```bash
sudo ufw disable
```
