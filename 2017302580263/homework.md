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
**P14**
```
1.SMTP 使用仅包含一个句号的一行来标志报文体结束，HTTP 使用 Content-Length 标志。
2.不能，因为报文内容可能含有句号。
```
**P20**
```
可以，在一段时间内， DNS 服务器缓存中出现最频繁的 web 服务器就是最流行的
```
