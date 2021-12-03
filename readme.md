# Surge 代理规则小片段

这个仓库搜集了我用自己用到的适用于Surge 的一些规则清单🧾。

## 最近更新

加入了URL Rewrite的规则。

## 已有的规则片段

文件 | 说明 
------------- | -------------
[Academic.conf](Academic.conf) | 这些规则适用于学术机构已经购买了某些期刊商的版权，且需要直连才可以访问的情况。 
[Apple.conf](Apple.conf) | Apple Service，苹果的服务。 
[URL_Rewrite.md](URL_Rewrite.md) | URL_Rewrite规则。


## 如何使用

形如`*.conf` 的规则清单适用于全部版本的Surge。

对于Surge 2，可以通过「复制粘贴」的方式来将这个仓库里的规则清单加入你的配置文件中。

而新版本的Surge ，由于`RULE-SET` 特性的加入，你可以通过加入一行RULE-SET 规则订阅的办法来使用这个仓库的中的配置清单，大概像下面这样，你直接拷贝过去用好了🤓：

```
RULE-SET,https://raw.githubusercontent.com/Yohoa/Rulesets-of-Surge/master/Academic.conf, 学术代理
RULE-SET,https://raw.githubusercontent.com/Yohoa/Rulesets-of-Surge/master/Apple.conf, Apple Services
```

_Enjoy!_

<img src="./img/icon.jpg" width = "300" height = "300" alt="Surge" align=center />

## 为Clash 加载

为每条规则前面加上一个" - "，之后配置好对应的Proxies Policy 为“学术代理”，就可以直接为Clash 所用了。
