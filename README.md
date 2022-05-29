# Heroku-vless

再次声明，免费服务，且用且珍惜，尽量不要滥用。

## 简介
Heroku是一个支持多种编程语言的云平台即服务。目前支持Ruby、Java、Node.js、Scala、Clojure、Python、PHP和Perl等语言，基础操作系统是Debian。

本项目用于在 Heroku 上部署 vless+websocket+tls，每次部署自动选择最新的 alpine linux 和 xray core。相比vmess，vless的性能更加优秀，占用资源更少，运行更加稳定。

建议使用cloudflare的workers的流量中转，速度更快，原则上使用后不会有被墙风险。

## 一键部署

经测试本镜像占用内存资源较低，运行稳定。点击下方紫色图标部署。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/xiarae/get/)




https://github.com/badafans/better-cloudflare-ip

![自选IP配置](https://so.21t.co/2021/06/15/ed87c8.png)

自选ip后，将图中Address中原地址修改为你自选ip（使用域名也可）。

## 临时替代品 2046 
或者你也可以 使用 https://2046.gq/ 
原域名2024.ml，2024.ga，2017.ga被墙，请更换2046.gq继续使用
使用永久优惠码 `FREE2024` 选择免费套餐，流量超出后可再次使用增加流量（注:我提供多个节点免费使用，每帐号每月1T流量，已关闭支付接口，请勿支付，其中带广告屏蔽线路，屏蔽youtube等视频站点广告，带netflix等线路支持新加坡netflix解锁）

关于2024站点，看到一直有朋友们找我问怎么支付，再次说明一下，这个免费服务使用的是我闲置的服务器，不需要付费，支付时使用优惠码 FREE2024 即可，之前默认1T流量/月，发现经常有人滥用，现在修改为100G，如果流量超出，你可以再次使用优惠码。这个我会免费下去，直到这些节点被墙。
免费服务且用且珍惜，我一直没封BT等，建议尽量别滥用，之前就有用户用来发垃圾邮件，导致被vultr停机，目前大多节点我并没限速，仅部分流量费用较贵的节点我限速50M。如果不能满足建议使用heroku或者买云服务器自行搭建。


