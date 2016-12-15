# Surge_config
a config file for Surge application
# Usage
Surge App 的配置文件,默认使用 Custom 方式,附加模块**SSEncrypt.module**可在此处下载,

## 更新内容（2016.12.15）

- 增加对 `Managed feature` 的支持

- 移除了所有 `reject` 规则

- 修改默认规则为 `nProxy`

- 改变了所有与 `Apple` 服务有关的规则策略，例如 `AppStore` ，`AppleMusic` ，使之全部走 `Proxy`，加快加载下载速度


-----

## 更新内容(2016.4.21)

- 增加了对 Apple DNS 加速的支持
- 增加了对 `THe Economist` , `Readbility` , `Medium`,`inoreader` 加速访问的支持
- 增加了URL rewrite ,可将 Safari 默认搜索重定向到"https://www.google.com.ncr"
- 移除了 Local DNS OVERRIDE ,因最近测试发现使用 ISP 自带的 DNS 综合效果更为良好.
 
## 关于 Apple DNS 
在配置文件中加入了此项 DNS Map ,意为根据所在地区的 ISP 的不同,使用适合的 DNS 记录加速 Apple 相关的服务,比如 AppStore, 
Apple Music 等.默认配置文件中的 DNS 适用于广州联通用户,其他的地区的用户可以根据自己实际需求来制作此文件,制作方法可参考
https://github.com/gongjianhui/AppleDNS
