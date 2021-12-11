# NBMinerProxy	

   NBMinerProxy 是一个挖矿代理软件。

## NBMinerProxy什么作用？	

   NBMinerProxy目前支持ETH、ETC等代理支持多个端口代理不同矿池和币种，支持本地局域网安装，可集中管理您的矿机，做到一键更改矿池和钱包地址，集中管理矿机，加密，集中反抽水。 NBMinerProxy支持VPS安装，为您存放在不同地域不同钱包的矿机提供矿池代理服务。	

## NBMinerProxy模式分别什么作用？	

   云端代理服务模式：该模式下软件需运行于服务器上，通过设置矿池地址和服务器端口，解决目前无法直连矿池和挖矿数据解密问题。
   内网加密端模式：该模式下软件在矿机本机或者局域网统一接收处理挖矿软件的数据加密后传输到服务器云端，主要用于内网和服务器之间的加密通讯传输问题。

## NBMinerProxy如何切换模式？	

   在需要启动的模式选项卡下面点击“保存设置”即可切换。软件最底部可区分当前软件模式以及运行转态

## NBMinerProxy是怎么使用的？	

   方案一：单独只使用云端代理服务模式挖矿，那么您的挖矿地址就是服务器IP:端口，挖矿软件的矿池地址填写<服务器IP:端口>，挖矿软件单独连接您自己的服务器，服务器帮助您把算力推送到矿池；
   方案二：使用云端代理+本地内网加密，内网加密端是架设在内网或者矿机本身的加密转发软件，启动后挖矿软件的矿池地址填写<192.168.0.X:端口>，挖矿软件将算力推送到内网加密端，内网加密端将算力解密后推送到云端代理服务器，服务器将算力转发到矿池，这个过程实现了加密挖矿和独立代理挖矿，能有效绕过网络监管。

## 内网加密端模式 的使用步骤
### 1、启动软件切换到内网加密端模式