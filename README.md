# burp-random-header

Realize the dynamic modification of the request header，用于实现请求头的动态修改burp插件 。

=============================================

RandomHeadrPlus1.2 更新记录

    1、添加%RealHost%变量,当端口为80或443时，RealHost==RHost,否则RealHost = RHOST+:+RPORT
    3、对于请求头为--开头的项目，将不会被替换，间接实现请求头替换开关。
    3、关闭默认开启的Apply to in-scope requests only
    4、修改LOGO并取消点击LOGO图标跳转到网页
    5、添加一些--开头的常用示例，--开头不会被启用

=============================================

RandomHeadrPlus1.1 更新记录

    1、修复UI显示重合问题
    1、通过字符串替换实现动态变量,
        %RURL%      请求URL
        %RHOST%     请求HOST 
        %RPORT%     请求PORT
        %RPROTOCOL% 请求协议
        %RURLPATH% 请求URL的路径
        %RURLQUERY% 请求URL的参数
        %RMETHOD%   请求方法
        
1.1版本具体介绍与使用方法：
RandomHeadrPlus-实现请求头动态替换
https://mp.weixin.qq.com/s/51MbozMPZAZTc2mrcRNjGA

=============================================


