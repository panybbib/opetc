# opetc
openwrt etc  sync

# 添加监听地址（将192.168.1.1修改为本地lan网关ip）
listen-address=192.168.1.1,127.0.0.1

# 并发查询所有上游DNS
all-servers

# 添加上游DNS服务器
resolv-file=/etc/dnsmasq/resolv.conf

# 添加额外hosts规则路径
addn-hosts=/etc/dnsmasq/noad.conf

# 添加DNS解析文件
conf-file=/etc/dnsmasq.d/fqad.conf

# 添加DNS解析文件夹
conf-dir=/etc/dnsmasq.d

# 设置的本地缓存大小
cache-size=1024

# IP反查域名
bogus-priv

# 设置在缓存中的条目的最小TTL
min-cache-ttl=3600

# 设置在缓存中的条目的最大TTL
max-cache-ttl=<time>
