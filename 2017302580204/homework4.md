p23、  
a、服务器向每个客户端并行发送文件，此速率为 us/N，因为 us/N <= dmin，  
所以客户端也以该速率下载。则每个客户端接收完文件的时间为 F / (us / N) = NF / us  
b、仍然考虑服务器向每个客户端并行发送文件，以 dmin 为速率，因为 us/N >= dmin，   
所以 us >= Ndmin，故服务器可以承受此速率，各服务器以 dmin 为下载速率，故接收时间为 F/dmin    
c、当 us/N <= dmin 时：  
        N/us >= 1/dmin  
        NF/us >= F/dmin  
        此时 t = NF/us = max{NF/us, F/dmin}  
当 us/N >= dmin 时：  
        N/us <= 1/dmin  
        NF/us <= F/dmin  
        此时 t = F/dmin = max{NF/us, F/dmin}  

因此：得出最小分发时间为 max{NF/us，F/dmin}  
p26、    
a.  
这是可能的，BitTorrent 存在漏洞，不能防止不合作的搭便车行为。  
比如 BitThief，它声称自己可以从 BitTorrent swarm 上下载却无需贡献任何资源  

b.  
他可以在每台主机上都运行客户端，并使他们搭便车，然后将它们收集的块聚合成一个文件，  
他还可以使不同主机下载不同的块，这是实际上一种 Sybil 攻击。  
p27、  
对等方 3 可以查它的第二后继对等方 4，使对等方 4 返回它的第一后继对等方 8。  
对等方 3 的第一后继是对等方 4，第二后继是对等方 8  