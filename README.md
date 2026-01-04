# singbox_rule
目前的完整版有：test
singbox-openwrt系列跟完整版的区别为：  
  dns-servers：local与bilibili的dns使用内网dns  
  dns-rules：不变  
  route-rules：cnmax,cnip,apple等原本走direct-全球直连的规则删掉，强制走漏网之鱼，即强制代理。（分流主要靠dns与bgp负责）  
  rule-ruleset：不变  
  其余不变  
