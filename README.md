若Cloudflare域名SSL为完全则服务器执行：
```
./xtunnel -l wss://:443
```
若Cloudflare域名SSL为灵活则服务器执行：
```
./xtunnel -l ws://80
```
非标端口Cloudflare回源规则要重写端口。

客户端命令：
```
./xtunnel -l socks5://:1080 -f wss://xtunnel.dynv6.net -ip 162.159.38.255
```
