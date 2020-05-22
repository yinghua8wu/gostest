# gostest

wget https://github.com/yinghua8wu/gostest/raw/master/gost-linux-amd64 && chmod +x gost-linux-amd64

服务端
gost -L=kcp://:8388?tcp=true
客户端
gost -L=:8080 -F=kcp://server_ip:8388?tcp=true
