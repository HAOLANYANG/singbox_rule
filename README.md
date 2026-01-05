# singbox_rule
目前的完整版有：test  
singbox-openwrt系列跟完整版的区别为：  
  dns-servers：local使用内网dns，bilibili删除（合并进local），且请求方式从加密https变成udp  
  dns-rules：bilibili单独的rules合并进local  
  outbounds：删除“📺 哔哩哔哩”
  route-rules：bilibili，cnmax,cnip,apple等原本走direct-全球直连的规则删掉，强制走漏网之鱼，即强制代理。（分流主要靠dns与bgp负责）  
  rule-ruleset：不变  
  其余不变  
