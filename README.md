# Performance-Monitoring
为showjoy前端组开发的前端性能监控系统
## 需求

服务器自动跑线上页面，收集性能指标数据，前端展示数据。
收集真实用户的线上性能数据，在后台页面展示。
## 参考文档

 - http://fex.baidu.com/blog/2014/05/build-performance-monitor-in-7-days/
 - https://github.com/hax/WebPerf
 - http://mp.weixin.qq.com/s?__biz=MjM5MTA1MjAxMQ==&mid=400023974&idx=1&sn=12658409ddc4a56d4381ad9322fbd4a8&scene=1&srcid=1020NgATVsXLudFoN6Lpd9wi&key=b410d3164f5f798e6f765418b59f2c5ca4ad8d92f002223cdaada282f3c9f4f94889ce1e05e580f7dc6223c422a503d4&ascene=0&uin=Mjg1NTY1OTY2MA%3D%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.10.4+build(14E46)&version=11020201&pass_ticket=QZ3ZC%2BOgTYgxkormhPhCBIc3hXXCX%2FtWWCcOU7nhBgUnedppYUyiO3Yr%2BZyv%2F3%2BI
## 目标

1.  完成服务器搭建，写好埋点js，手动跑页面，得到页面加载性能的数据（json格式）。数据类型有：
 - 白屏时间
 - 页面渲染完成时间
 - 页面load时间
 - 。。。