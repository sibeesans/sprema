- Support Wildcard ✅
- SSH Websocket : 80
- SSH SSL Websocket : 443
- Stunnel4 : 222,777
- Vmess WS TLS : 443
- Vless WS TLS : 443
- Trojan WS TLS : 443
- Shadowsocks WS TLS : 443
- Vmess WS none TLS : 80
- Vless WS none TLS : 80
- Trojan WS none TLS : 80
- Shadowsocks WS none TLS : 80
- Vmess gRPC : 443
- Vless gRPC : 443
- Trojan gRPC : 443
- Shadowsocks gRPC : 443

![Dropbear](https://shields.io/badge/Service-Dropbear-orange?logo=jamboard&style=for-the-badge) 
![Stunnel](https://shields.io/badge/Service-Stunnel-orange?logo=keepassxc&style=for-the-badge) 
![Squid](https://shields.io/badge/Service-Squid-orange?logo=testinglibrary&style=for-the-badge) 
![BadVPN UDPGw](https://shields.io/badge/Service-BadVPN%20UDPGw-orange?logo=ublockorigin&style=for-the-badge) 
![Xray](https://shields.io/badge/Service-Xray-orange?logo=xstate&style=for-the-badge) 
![V2ray](https://shields.io/badge/Service-V2ray-orange?logo=v&style=for-the-badge)
![Nginx](https://shields.io/badge/Service-Nginx-orange?logo=onnx&style=for-the-badge)

# INSTALL 
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && reboot
```

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/Citraloka/mp2/aio/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
```

