# 如何连上QENET2

Version 1.0 By 1107

**阅读本文章可以教会宁如何连上QE的以太网，有问题请==不要联系作者==**

~~我当然知道怎么抓包， 当然知道怎么用Wireshark(bushi~~

### 你需要

> 一台电脑
>
> 一根网线     ==***请不要拿着宁的电话线当作网线用***==
>
> 一个智慧的大脑

------------------------

Step1>在搜索框里输入服务/win+R输入services.msc, 然后enter/按下确认

Step2>找到Wired Autoconfig, 右键找到属性改成'自动'    ==*不是WWAN Autoconfig, 也不是WLAN Autoconfig*==

Step3>打开控制面板->网络和Internet->网络和共享中心

Step4>左边栏按下'更改适配器设置'

Step5>找到以太网（Ethernet)双击找到属性，打开

Step6>切到身份验证->其他设置, 打开'指定身份验证', 切到'用户身份验证'， 按下保存凭证

Step7>输入宁的用户名密码

> 假设宁的用户名为114514@qestudent.org或者114514@qe.thorpeunderwood.com, 密码为1919810, 那么宁的用户名就是114514， 密码就是1919810

Step8>搞定

==Q&A==

Q:为什么我没有以太网接口

A:因为你没有

Q:网线长啥样？

A:......

Q:为啥我设置完了还是连不上

A:有没有一种可能QE的网线口子坏了

Report Bug请发邮件至1107@siwg.top

