## Homework4

------

### 周梓浩

------

nslookup

<img src="C:\Users\junow\Desktop\nslookup.png" alt="nslookup" style="zoom:60%;" />

------

P22

<img src="C:\Users\junow\Desktop\P22.PNG" alt="P22" style="zoom:60%;" />

| 客户端-服务器 | 10      | 100      | 1000      |
| ------------- | ------- | -------- | --------- |
| 300kbps       | 7680sec | 51200sec | 512000sec |
| 700kbps       | 7680sec | 51200sec | 512000sec |
| 2Mbps         | 7680sec | 51200sec | 512000sec |

| P2P    | 10      | 100        | 1000        |
| ------ | ------- | ---------- | ----------- |
| 300kps | 7680sec | 25600sec   | 47558.78sec |
| 700kps | 7680sec | 15616.2sec | 21524.85sec |
| 2Mbps  | 7680sec | 7680sec    | 7680sec     |

------

P23

<img src="C:\Users\junow\Desktop\p23.PNG" alt="p23" style="zoom:60%;" />

a. us/N<=dmin,每个用戶可以以us/N的速率進行接收,分发时间为NF/us

b. us/N>=dmin,服务器可以以dmin速率進行分发,分发时间为F/dmin。

c. 由上两题：

us/N<=dmin时，NF/us>=F/dmin，此时Dcs=NF/us。

us/N>=dmin时，NF/us>=F/dmin，此时Dcs=F/dmin。

所以Dcs=max{NF/us,F/dmin}

------

P25

<img src="C:\Users\junow\Desktop\p25.PNG" alt="p25" style="zoom:60%;" />

共N个节点，N(N-1)/2条边

