# 一键安装shadowsocks的脚本

## 执行以下命令一键安装：

```
chmod +x install-shadowsocks.sh
./install-shadowsocks.sh
```

## 成功案例

```
Congratulations! Shadowsocks has been installed on your system.
You shadowsocks connection info:
--------------------------------
server:      0.0.0.0
server_port: 8388
password:    RaskAAcW0IQrVcA7n0QLCEphhng7K4Yc
method:      aes-256-cfb
--------------------------------
```


### 启动Shadowsocks

```
ssserver -c /etc/shadowsocks.json -d start
```

### 关闭Shadowsocks

```
ssserver -c /etc/shadowsocks.json -d stop
```
