# GPFSWorld 
GPFSWorld 基于[fyne](https://github.com/fyne-io/fyne)框架开发，是GPFS网络的GUI节点，是GPFS生态不可或缺的一部分。所有人都可以用它自由地分享自己的文件。它不仅仅是一个文件管理工具，它还是一个基于P2P协议的资源搜索引擎。

 
![](11.png)

## 功能列表

| 功能            | 状态         |
| -------------- | ---------- | 
| 文件导入 | OK |   
| 文件导出 | TODO | 
| 配置管理 |TODO |
| 资源搜索 |TODO | 
|  挖矿 |TODO |

##  Q&A
- 导入文件后为什么从浏览器打开链接访问不到？   
 答：文件同步需要时间，GFPS(IFPS)网关基本上都在国外。如果很长时间还打不开，可以在这里 https://ipfs.github.io/public-gateway-checker/  选择合适的网关，替换掉默认链接中的网关访问。   
 比如下面，同一个个文件可以使用不同的网关，只要文件CID一样即可:

     https://infura-ipfs.io/ipfs/QmVjgobGV2vL12Jv2d5KeJKVu1obVycEN8Sk1GLXPFMfLv?filename=gpfs.jpg  
     https://astyanax.io/ipfs/QmVjgobGV2vL12Jv2d5KeJKVu1obVycEN8Sk1GLXPFMfLv?filename=gpfs.jpg  
     https://dweb.link/ipfs/QmVjgobGV2vL12Jv2d5KeJKVu1obVycEN8Sk1GLXPFMfLv?filename=gpfs.jpg  
 
- 软件不用的时候可以关闭吗？  
 答： 文件在分享过程中尽量不要关闭。
 
- 软件关闭后别人还能访问我的文件吗？   
 答： 若你的文件已经同步到其他节点，即使你关机或删除文件，别人还是能够访问。但GPFS网络并不保证数据永久保存，所以为了让别人持续可访问你的文件，请不要关闭软件。







