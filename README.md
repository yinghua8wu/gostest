# gostest

wget https://github.com/yinghua8wu/gostest/raw/master/gost-linux-amd64 && wget https://raw.githubusercontent.com/yinghua8wu/gostest/master/g chmod +x gost-linux-amd64 g

服务端

./gost-linux-amd64 -L=kcp://:8388?tcp=true

客户端

gost -L=:8080 -F=kcp://server_ip:8388?tcp=true
