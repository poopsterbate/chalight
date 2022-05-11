# chalight


### 安装/更新方式（Nginx 前置）

支持配置方式

- VLESS + TCP + TLS + Nginx + WebSocket

```
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/poopsterbate/chalight/nginx_forward/install.sh" && chmod +x install.sh && bash install.sh
```

### 安装/更新方式（Xray 前置）

支持配置方式

- VLESS + TCP + XTLS / TLS  + Nginx

- VLESS + TCP + XTLS / TLS  + Nginx 及 VLESS + TCP + TLS + Nginx + WebSocket 回落并存模式

```
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/poopsterbate/chalight/main/install.sh" && chmod +x install.sh && bash install.sh
```


## 中转脚本

* 启动脚本 
```
wget --no-check-certificate -O gost.sh https://raw.githubusercontent.com/poopsterbate/chalight/gost.sh && chmod +x gost.sh && ./gost.sh`  
```
* 再次运行本脚本只需要输入`./gost.sh`回车即可  
