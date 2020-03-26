## 作业4
**1、nslookup www.whu.edu.cn**
```
nslookup www.whu.edu.cn
服务器:  UnKnown
Address:  192.168.1.1

非权威应答:
名称:    www.whu.edu.cn
Addresses:  2001:250:4001:1::1001
          202.114.64.200

```
**2、nslookup 有关**
```
nslookup用于查询DNS的记录，查询域名解析是否正常，在网络故障时用来诊断网络问题
```
## 习题
**P8**
```
a.
2RTT0 + RTT1 + RTT2 + … + RTTn + 8 * 2 RTT0 = 18 RTT0 + RTT1 + RTT2 + … + RTTn

b.
2RTT0 + RTT1 + RTT2 + … + RTTn + 2 * 2 RTT0 = 6 RTT0 + RTT1 + RTT2 + … + RTTn

c.
2RTT0 + RTT1 + RTT2 + … + RTTn + RTT0 = 3 RTT0 + RTT1 + RTT2 + … + RTTn
```
**P10**
```
10米短链路，忽略其传播时延。

带有并行连接的非持续连接且并行下载：
(200b / 150bps) * 3 + ((10^5)b/ 150bps) + (200b / (150bps / 10)) * 3 + ((10^5)b / (150bps / 10)) = 7377.3s

持续连接：
(200b / 150bps) * 3 + ((10^5)b / 150bps) + 10 * (200b/150bps + (10^5)b/150bps) = 7351s
```
**P20**
```
可以，在一段时间内， DNS 服务器缓存中出现最频繁的 web 服务器就是最流行的
```
