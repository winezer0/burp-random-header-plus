# burp-random-header

Realize the dynamic modification of the request header，用于实现请求头的动态修改burp插件 。

介绍与使用方法：

RandomHeadrPlus-实现请求头动态替换
https://mp.weixin.qq.com/s/51MbozMPZAZTc2mrcRNjGA

修改记录

1、通过字符串替换实现动态变量,

    %RURL%      请求URL
    %RHOST%     请求HOST 
    %RPORT%     请求PORT
    %RPROTOCOL% 请求协议
    %RURLPATH% 请求URL的路径
    %RURLQUERY% 请求URL的参数
    %RMETHOD%   请求方法

2、修复UI显示重合问题

