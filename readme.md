# Surge 代理规则小片段

这个仓库搜集了我用自己用到的适用于Surge 的一些规则清单🧾。

## 已有的规则片段

文件 | 说明 
------------- | -------------
[Academic.conf](Academic.conf) | 这些规则适用于学术机构已经购买了某些期刊商的版权，且需要直连才可以访问的情况。 
[Apple.conf](Apple.conf) | Apple Service，苹果的服务。 



## 如何使用

形如`*.conf` 的规则清单适用于全部版本的Surge。

对于Surge 2，可以通过「复制粘贴」的方式来将这个仓库里的规则清单加入你的配置文件中。

而Surge ，由于`RULE-SET` 特性的加入，你可以通过加入一行RULE-SET 规则订阅的办法来使用这个仓库的中的配置清单，大概像下面这样：

```
RULE-SET,https://raw.githubusercontent.com/Yohoa/Academic.conf, 学术代理
RULE-SET,https://raw.githubusercontent.com/Yohoa/Apple.conf, Apple Services
```

_Enjoy!_

<img src="./img/icon.jpg" width = "300" height = "300" alt="Surge" align=center />
