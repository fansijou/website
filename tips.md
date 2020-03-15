* 不保留配置升级：[图文](./upgrade.md)                 
* 请务必保持启用passwall的高级设置里的守护进程！      
* 在passwall运行状态下修改LAN的静态IP后可能会无法自动唤起DNS导致无法上网，需要重启passwall或者重启软路由         
* 不允许访客使用代理、自由指定不同客户端使用不同线路、盒子看Netflix：                 
[https://youtu.be/qkga9DN5H08](https://youtu.be/qkga9DN5H08)             
* 如何DDNS外网无需加端口远程访问 dynuDNS解析 URL转发 治愈强迫症：      
[https://youtu.be/c4HSZzTM7G0](https://youtu.be/c4HSZzTM7G0)         
* 单线or双线，最简单的iptv内网融合教程，需要懂一点基础：      
[https://github.com/luckyyyyy/blog/issues/44](https://github.com/luckyyyyy/blog/issues/44)                  
* 手动单独更新passwall按钮不要一直使用，当出问题后还是需要完整不保留配置刷入最新完整固件的，否则依赖包不会更新，无法修复bug和获得优化体验        
* 如果出现YouTube等一些网站的页面上的特定内容错误显示，比如广告区域加载失败，只有框框没有图片，大概率是你的系统（不是固件！）的负责域名快速解析的HOSTS文件在作妖，解决办法是删除HOSTS文件里的所有规则（# 号注释掉的内容可以不管，其他的都删掉）                               
* 始终无法连接到软路由网络、始终无网络：[可能解决办法](./winproxy.md)               
* 科学上网测速注意：[注意事项](./speed.md)           
* 基于Chromium内核的浏览器建议关闭QUIC：[教程](https://www.echoteen.com/turnoff-quic.html)               
* 修改win10的tcp配置参数来提升打开youtube的速度：[教程](https://bincode.cc/ssr-win10-tcp-youtube-speed/)              

