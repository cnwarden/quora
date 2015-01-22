# Quora Program Questions
---
## HTML
[HTML live-preview](https://www.quora.com/What-is-the-best-text-editor-for-HTML-CSS-that-has-live-preview)

## Brackets
[Beautify HTML, CSS, and Javascript in Adobe Brackets](https://github.com/drewhamlett/brackets-beautify)

# Weixin
[Analyze Weixin Protocal](http://www.blogjava.net/yongboy/archive/2014/03/05/410636.html)
[QT UI](https://github.com/xiangzhai/qwx)

**URL**
http://dns.weixin.qq.com/cgi-bin/micromsg-bin/newgetdns?uin=22898665&clientversion=637534778&scene=0&net=1&md5=219ea25340018dbf2272e17653efcac3&devicetype=android-17&lan=zh_CN&sigver=1

**URL**
http://support.weixin.qq.com/cgi-bin/mmsupport-bin/reportdevice?channel=0&deviceid=Aa1c4872b7fca198&clientversion=637534778&platform=0&lang=zh_CN&installtype=1

so 
BIZ & UIN is stable, need the key

uin is used for futher: uin=MjI4OTg2NjU= with based 64

GET /cgi-bin/micromsg-bin/newgetdns?uin=22898665&clientversion=637534778&scene=0&net=1&md5=219ea25340018dbf2272e17653efcac3&devicetype=android-17&lan=zh_CN&sigver=1 HTTP/1.0
Accept: */*
Accept-Encoding: deflate
Cache-Control: no-cache
Connection: close
Content-Type: application/octet-stream
Host: dns.weixin.qq.com
User-Agent: **MicroMessenger Client**

first report service:
http://mp.weixin.qq.com/cgi-bin/mmsupport-bin/reportdevice?channel=0&deviceid=Aa1c4872b7fca198&clientversion=637534778&platform=0&lang=zh_CN&installtype=1 HTTP/1.1 

Get list:
http://mp.weixin.qq.com/mp/getmasssendmsg?__biz=MzA5MDM5MzgwOQ==&uin=MjI4OTg2NjU=&key=79cf83ea5128c3e5ed80bb731f2ce9d4a23cfd591722b7162eb31e84a99f5913f631ddf1758bed804bb9621340f2c746

&f=json&frommsgid=201681534&count=10&uin=MjI4OTg2NjU%3D&key=79cf83ea5128c3e5ed80bb731f2ce9d4a23cfd591722b7162eb31e84a99f5913f631ddf1758bed804bb9621340f2c746&pass_ticket=x97iODks1KTvxOWsUz%2Bccz4v%2BQoXeqkHk086pirabaw%3D
