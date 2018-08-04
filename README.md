# GoogleImage-ReverseProxy
- caddy -- http server
## 执行
```bash
wget -qO- https://raw.githubusercontent.com/coding1618/Google-images-shell/master/Google_images.sh |bash
```
## 加权
```bahs
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
