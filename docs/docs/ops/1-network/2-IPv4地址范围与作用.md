# IPv4地址范围与作用

| 类别 | 地址范围                   | 网络位数 | 主机位数 | 用途/描述 |
|------|---------------------------|----------|----------|-----------|
| A类  | 1.0.0.0 - 126.0.0.0       | 8位      | 24位     | 特大型网络，全球性网络使用 |
| B类  | 128.0.0.0 - 191.255.0.0   | 16位     | 16位     | 大中型网络，地区性网络使用 |
| C类  | 192.0.0.0 - 223.255.255.0 | 24位      | 8位      | 小型网络，局域网使用 |
| D类  | 224.0.0.0 - 239.255.255.255 | -        | -        | 多播地址，用于组播通信 |
| E类  | 240.0.0.0 - 255.255.255.255 | -        | -        | 研究用地址，未用于Internet |
| 私有A类 | 10.0.0.0 - 10.255.255.255 | -        | -        | 局域网内部使用，不能在互联网上路由 |
| 私有B类 | 172.16.0.0 - 172.31.255.255 | -        | -        | 同上 |
| 私有C类 | 192.168.0.0 - 192.168.255.255 | -        | -        | 同上 |
| 自动私有IP | 169.254.0.0 - 169.254.255.255 | -        | -        | DHCP失败时Windows自动分配 |
| 回环地址 | 127.0.0.0 - 127.255.255.255 | -        | -        | 用于本地回环测试，不能用作网络地址 |