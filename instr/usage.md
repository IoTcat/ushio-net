# 用户注册

Ushio-Net使用Ushio系统进行用户管理。

如果您还没有注册过，请<button onClick="session.onload(function(){if(session.get('group') !== 'anonymous'){tips.show({message: session.get('nickname')+', 您已登录！', position: 'center', timeout: 10000});}else{window.open('https://login.yimian.xyz/?require=tel&from=https://v2ray.yimian.xyz/','_blank');}});">点击这里</button>进行注册。


# 授权

完成注册后，请您联系我(微信或[邮件](mailto:i@iotcat.me))对您进行授权。

考虑到服务的特殊性，原则上，<mark>Ushio-Net只对满足以下条件之一的人进行授权</mark>。
 - 我认识的人
 - 我朋友认识的人
 - Members of XJTLU
 - Members of University of Liverpool
 - Members of Cornell University


!> 使用人须承诺**永不使用本服务进行任何可能危害中国国家安全的行为**！


# 配置客户端


## 介绍

<!-- tabs:start -->

#### **Win10**

Win10拥有一些支持V2ray内核的开源图形化客户端，例如[V2RayN](https://github.com/2dust/v2rayN), [V2RayW](https://github.com/Cenmrev/V2RayW), [clash](https://github.com/Fndroid/clash_for_windows_pkg), [Qv2ray](https://github.com/lhy0403/Qv2ray), [Mellow](https://github.com/mellow-io/mellow)等。

本文将介绍如何配置<mark>V2RayN<sub>V5.34</sub></mark>作为你的Ushio-Net客户端。



#### **Android**

Android拥有一些支持V2ray内核的图形化客户端，例如[V2RayNG](https://github.com/2dust/v2rayNG), [BifrostV](https://play.google.com/store/apps/details?id=com.github.dawndiy.bifrostv), [Kitsunebi](https://play.google.com/store/apps/details?id=fun.kitsunebi.kitsunebi4android&hl=en_US)等。

本文将介绍如何配置<mark>V2RayNG<sub>V1.7.3</sub></mark>作为你的Ushio-Net客户端。


#### **IOS/IPad**

IOS/IPad拥有一些支持V2ray内核的图形化客户端，例如[Shadowrocket](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8), [i2Ray](https://itunes.apple.com/us/app/i2ray/id1445270056?mt=8), [Kitsunebi](https://itunes.apple.com/us/app/kitsunebi-proxy-utility/id1446584073?mt=8)等。

本文将介绍如何配置<mark>Shadowrocket<sub>V2.2.16</sub></mark>作为你的Ushio-Net客户端。


#### **Mac**

Mac拥有一些支持V2ray内核的开源图形化客户端，例如[V2RayU](https://github.com/yanue/V2rayU), [V2RayX](https://github.com/Cenmrev/V2RayX), [V2RayC](https://github.com/gssdromen/V2RayC)等。

由于我手中没有Mac设备，因此暂不提供Mac的配置教程，只提供一个V2RayU的国内下载链接。



#### **Linux**

Linux拥有一些支持V2ray内核的开源图形化客户端，例如[Qv2ray](https://github.com/lhy0403/Qv2ray), [Mellow](https://github.com/mellow-io/mellow)等。

由于我手中没有Linux设备，因此暂不提供Linux的配置教程。请自行探索配置！


<!-- tabs:end -->


## 下载客户端

请从以下链接下载并安装客户端！


<!-- tabs:start -->

#### **Win10**
 - [V2Ray链接](https://proxy.yimian.xyz/get/?url=aHR0cHM6Ly9naXRodWIuY29tLzJkdXN0L3YycmF5Ti9yZWxlYXNlcy9kb3dubG9hZC81LjM0L3YycmF5Ti1Db3JlLnppcA==)
 - [V2Ray备用链接](https://github.com/2dust/v2rayN/releases/download/5.34/v2rayN-Core.zip)

#### **Android**

 - [V2Ray链接](https://proxy.yimian.xyz/get/?url=aHR0cHM6Ly9naXRodWIuY29tLzJkdXN0L3YycmF5TkcvcmVsZWFzZXMvZG93bmxvYWQvMS43LjMvdjJyYXlOR18xLjcuMy5hcGs=)
 - [V2Ray备用链接](https://github.com/2dust/v2rayNG/releases/download/1.7.3/v2rayNG_1.7.3.apk)

#### **IOS/IPad**

如果你的应用商店地区在国外，如美国、英国，请直接从应用商店搜索<mark>shadowrocket</mark>付费下载。如果你的应用商店地区在国内，请参考[这个链接](https://shadowsockshelp.github.io/ios/)。


#### **Mac**

 - [V2RayU链接](https://proxy.yimian.xyz/get/?url=aHR0cHM6Ly9naXRodWIuY29tL3lhbnVlL1YycmF5VS9yZWxlYXNlcy9kb3dubG9hZC8yLjMuMS9WMnJheVUuZG1n)
 - [V2RayU备用链接](https://github.com/yanue/V2rayU/releases/download/2.3.1/V2rayU.dmg)


#### **Linux**



<!-- tabs:end -->


## 安装客户端

!> 请确保您的设备上没有正在运行的V2Ray其它软件！！

<!-- tabs:start -->

#### **Win10**

1. 请解压下载的压缩文件到您的电脑，比如`C:\v2ray\v2rayN-Core`。
1. 请双击打开`C:\v2ray\v2rayN-Core\v2rayN.exe`或者`C:\v2ray\v2rayN-Core\v2rayN`。


#### **Android**

请安装下载的安装包。

?> 如果提示无法安装，请从手机设置中开启**允许安装外部来源应用**

#### **IOS/IPad**

请根据上述网址下载并安装Shadowrocket。


#### **Mac**



#### **Linux**



<!-- tabs:end -->


## 设置客户端

!> 如果您遇到了任何问题，请务必告知我！我们一起来改善这份教程！

<!-- tabs:start -->

#### **Win10**

1. 请在屏幕右下角**任务栏**找到V图标![v2rayN icon](/img/v2rayN_ico.png)并点击。

?> **注意** 任务栏可能被自动折叠，请展开任务栏查找！

1. 在弹出的窗口中，选择<mark>设置</mark>-><mark>参数设置</mark>。
1. 找到<mark>v2rayN设置</mark>，勾选<mark>开机自启动</mark>。
1. 点击下方<mark>解除Windows10 UWP应用回环代理限制</mark>，在弹出的窗口中，点击<mark>Exempt All</mark>，然后点击<mark>Save Changes</mark>。
1. 点击参数设置窗口的<mark>确定</mark>键。

#### **Android**

1. 打开v2rayNG。
1. 点击右上角三个点，选择<mark>删除全部配置</mark>。
1. 到手机系统设置->>应用->>应用启动管理，关掉系统对V2RayNG的自动管理，并给V2RayNG所有权限（允许自启动，允许关联启动，允许后台活动等）！！！

?> 这里我用的是华为系统的步骤，其它手机类似。

?> 对于部分手机（比如华为, 小米等），可以将v2rayNG设置为通知栏常驻，从而可以像开关WiFi那样方便的开关V2RayNG，



#### **IOS/IPad**

1. 打开Shadowrocket。


#### **Mac**

#### **Linux**

<!-- tabs:end -->



## 订阅Ushio-Net



<!-- tabs:start -->

#### **Win10**

1. [点击这里](https://v2ray.yimian.xyz/)查看你的Ushio-Net订阅信息。
1. 请点击网页上的<mark>Copy</mark>按钮。
1. 重新回到V2RayN的主页面，点击上方<mark>订阅->>订阅设置</mark>。
1. 在订阅设置窗口中，点击左下方<mark>添加</mark>。
1. 将刚才复制的内容黏贴到<mark>地址</mark>中。
1. 点击下方<mark>确定</mark>。
1. 回到V2RayN主页面，点击上方<mark>订阅->>更新订阅（不通过代理）</mark>.
1. 如果主窗口中有新的服务器出现，则代表订阅成功。


#### **Android**


1. 用手机浏览器打开[https://v2ray.yimian.xyz](https://v2ray.yimian.xyz/)查看你的Ushio-Net订阅信息。
1. 请点击网页上的<mark>Copy</mark>按钮。
1. 重新打开V2RayNG的主页面，点击<mark>左上方三条杠->>订阅设置</mark>。
1. 点击右上方<mark>加号</mark>。
1. 将刚才从网页上复制的内容粘贴到<mark>地址</mark>中。
1. 在备注中随便填点东西。
1. 点击<mark>右上角对号</mark>。
1. 回到主页面，点击<mark>右上角三个点->>更新订阅</mark>。
1. 若观察到主页面中出现新的服务器，则代表订阅成功。



#### **IOS/IPad**

1. 用IOS/IPad浏览器打开[https://v2ray.yimian.xyz](https://v2ray.yimian.xyz/)查看你的Ushio-Net订阅信息。
1. 请点击网页上的<mark>Copy</mark>按钮。
1. 重新打开Shadowrocket的主页面，点击<mark>右上角加号</mark>。
1. 类型选择<mark>Subscribe</mark>。
1. 将刚才从网页上复制的内容粘贴到<mark>URL</mark>中。
1. 点击右上角<mark>完成</mark>。
1. 回到主页面，点击新出现的服务器节点（一般是`api.yimian.xyz`）。
1. 如果下方出现多个新的服务器，则代表订阅成功。


#### **Mac**

#### **Linux**

<!-- tabs:end -->



----------------

## 配置客户端-访问外网


!> **注意** 当前为国内访问外网。<mark>从国外访问国内[见下方](/usage?id=配置客户端-回国)</mark>。



<!-- tabs:start -->

#### **Win10**

1. 在主窗口中，选择<mark>设置</mark>-><mark>路由设置</mark>。
1. 点击<mark>高级功能</mark>-><mark>添加规则集</mark>
1. 在别名，填写<mark>出国</mark>，订阅地址填写<mark>https://v2ray.yimian.xyz/rules/FlyToWorld.rul</mark>
1. 点击<mark>导入规则</mark>-><mark>从订阅Url中导入规则</mark>，在是否追加的弹出中，选择<mark>否</mark>。
1. 在规则集设置窗口，点击<mark>确定</mark>
1. 在路由设置窗口，点击<mark>确定</mark>


#### **Android**

1. 在V2RayNG主页面，点击<mark>左上角三个杠->>设置</mark>。
1. 点击<mark>分应用代理</mark>，确保<mark>分应用代理</mark>选项被打开。
1. 在分应用代理里，点击<mark>右上角三个点->>自动选中需代理应用</mark>。
1. 这时，应该有一些应用被选中了。你可以根据你的需求微调一下，选择你认为需要翻墙的APP。
1. 点击左上角箭头返回到设置页面。
1. 在设置页面，找到<mark>域名策略</mark>设置为<mark>IPIfNonMatch</mark>。
1. 在设置页面，找到<mark>预定义规则</mark>设置为<mark>绕过局域网及大陆地址</mark>。
1. 返回到主页面，点击选中`Los_Angeles`那一项，让其左侧变绿。

#### **IOS/IPad**

1. 在Shadowrocket主页面，点击下方<mark>配置</mark>。
1. 点击<mark>恢复默认配置</mark>，弹窗点击<mark>好</mark>。
1. 在Shadowrocket主页面，点击下方<mark>首页</mark>。
1. 点击`Los_Angeles`，让它左边出现黄点。
1. 点击<mark>全局路由->>配置</mark>。


#### **Mac**

#### **Linux**

<!-- tabs:end -->




## 使用Ushio-Net-访问外网



<!-- tabs:start -->

#### **Win10**

**开启外网访问**

-  请在屏幕右下角**任务栏**找到V图标![v2rayN icon](/img/v2rayN_ico.png)并<mark>**右键**</mark>点击，选择<mark>服务器->Los_Angeles</mark>。
-  选择<mark>路由->出国</mark>。
-  选择<mark>系统代理->自动配置系统代理</mark>。


?> 完成这个操作后，你将能够使用浏览器访问Google等服务。国内的网站将会直接连接，而不会通过代理。此模式<mark>**推荐长期使用**</mark>！


**关闭外网访问**

-  请在屏幕右下角**任务栏**找到V图标![v2rayN icon](/img/v2rayN_ico_red.png)并<mark>**右键**</mark>点击，选择<mark>系统代理->清除系统代理</mark>。

?> 完成这个操作后，你将无法访问Google等服务，但国内网站可正常访问。



#### **Android**

**开启外网访问**

 - 在V2RayNG主页面，点击右下角的V字图标，使其变绿。

?> 完成这个操作后，你配置的APP将能够使用访问Google等服务。其它APP将会直接连接，而不会通过代理。此模式<mark>**推荐长期使用**</mark>！

?> 对于部分手机如华为，你也可以直接点击通知栏中的V图标即可开启和关闭服务。就像开关手电筒一样。

**关闭外网访问**

 - 在V2RayNG主页面，点击右下角的V字图标，使其变灰。

?> 完成这个操作后，V2rayNG将被关闭，你的所有APP将无法访问Google等服务。！



#### **IOS/IPad**

**开启外网访问**

-  打开Shadowrocket首页, 点击上面第一项<mark>未连接</mark>，使其显示<mark>Los_Angeles</mark> 。


?> 完成这个操作后，你将能够访问Google等服务。国内的网站将会直接连接，而不会通过代理。此模式<mark>**推荐长期使用**</mark>！


**关闭外网访问**

-  打开Shadowrocket首页, 点击上面第一项<mark>Los_Angeles</mark>，使其显示<mark>未连接</mark> 。

?> 完成这个操作后，你将无法访问Google等服务，但国内网站可正常访问。



#### **Mac**

#### **Linux**

<!-- tabs:end -->



---------------------
---------------



## 配置客户端-回国


!> **注意** 当前为国外访问国内。<mark>从国内访问国外[见上方](/usage?id=配置客户端-访问外网)</mark>。


<!-- tabs:start -->

#### **Win10**


1. 在主窗口中，选择<mark>设置</mark>-><mark>路由设置</mark>。
1. 点击<mark>高级功能</mark>-><mark>添加规则集</mark>
1. 在别名，填写<mark>回国</mark>，订阅地址填写<mark>https://v2ray.yimian.xyz/rules/BackToChina.rul</mark>
1. 点击<mark>导入规则</mark>-><mark>从订阅Url中导入规则</mark>，在是否追加的弹出中，选择<mark>否</mark>。
1. 在规则集设置窗口，点击<mark>确定</mark>
1. 在路由设置窗口，点击<mark>确定</mark>

#### **Android**


1. 在V2RayNG主页面，点击<mark>左上角三个杠->>设置</mark>。
1. 点击<mark>分应用代理</mark>，确保<mark>分应用代理</mark>选项被打开。
1. 在分应用代理页面，<mark>**仅选择**</mark>所有<mark>你认为需要翻墙回国打破IP版权限制的APP</mark>。
1. 点击左上角箭头返回到设置页面。
1. 在设置页面，找到<mark>域名策略</mark>设置为<mark>IPIfNonMatch</mark>。
1. 在设置页面，找到<mark>预定义规则</mark>设置为<mark>绕过局域网地址</mark>。
1. 返回到主页面，点击选中`China-Taian`那一项，让其左侧变绿。


#### **IOS/IPad**

1. 点击左上角，扫描以下二维码    

![回国配置](/img/qrcode_ios_backcn.png)    

1. 配置页面，点击get.conf (也有可能叫其他名字，总之不是default.conf)
1. 在Shadowrocket首页，点击`China-Taian`，让它左边出现黄点。
1. 点击<mark>全局路由->>代理</mark>。


#### **Mac**

#### **Linux**

<!-- tabs:end -->


## 使用Ushio-Net-回国



<!-- tabs:start -->

#### **Win10**

**开启访问国内**

-  请在屏幕右下角**任务栏**找到V图标![v2rayN icon](/img/v2rayN_ico.png)并<mark>**右键**</mark>点击，选择<mark>服务器->China-Taian</mark>。
-  选择<mark>路由->回国</mark>。
-  选择<mark>系统代理->自动配置系统代理</mark>。


?> 完成这个操作后，你将能够打破IP限制访问国内资源。只有中国网站会被代理，国外网站将直接连接，不会影响国外网站访问速度，推荐长期使用！！


**关闭访问国内**

-  请在屏幕右下角**任务栏**找到V图标![v2rayN icon](/img/v2rayN_ico_red.png)并<mark>**右键**</mark>点击，选择<mark>系统代理->清除系统代理</mark>。

?> 完成这个操作后，你将无法打破国内资源的IP限制。



#### **Android**

**开启访问回国**

 - 在V2RayNG主页面，点击右下角的V字图标，使其变绿。

?> 完成这个操作后，你配置的APP将能够使用国内IP访问资源，从而打破IP版权限制。其它APP将会直接连接，而不会通过代理。此模式<mark>**推荐长期使用**</mark>！

?> 对于部分手机如华为，你也可以直接点击状态栏中的V图标即可开启服务。

**关闭外访问回国**

 - 在V2RayNG主页面，点击右下角的V字图标，使其变灰。

?> 完成这个操作后，V2rayNG将被关闭，你的国内APP将无法打破IP版权限制！


#### **IOS/IPad**


**开启访问回国**

-  打开Shadowrocket首页, 点击上面第一项<mark>未连接</mark>，使其显示<mark>China-Taian</mark> 。


?> 完成这个操作后，你的所有APP将能够使用国内IP访问资源，从而打破IP版权限制。国外的网站和APP访问速度不会下降。此模式<mark>**推荐长期使用**</mark>！

**关闭访问回国**

-  打开Shadowrocket首页, 点击上面第一项<mark>China-Taian</mark>，使其显示<mark>未连接</mark> 。

?> 完成这个操作后，V2rayNG将被关闭，你的APP将无法打破IP版权限制。

#### **Mac**

#### **Linux**

<!-- tabs:end -->



---------------
----------------

[<kbd>&rarr;</kbd> 下一页](/advanced?id=进阶)
