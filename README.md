# tvbox-multi

TVBox / FongMi 影视多仓索引（多仓 = urls 索引 JSON）。

## 文件

| 文件 | 说明 |
|---|---|
| duocang-lite.json | 精简版，8 个站点数最多的仓（推荐） |
| duocang-full.json | 全量 34 个独立源 |
| urls.txt | 34 条裸接口 URL，可逐条添加 |

## 用法（FongMi / TVBox）

设置 → 接口 → 填入本仓库 JSON 的原始链接（多仓模式）；或把 urls.txt 里的地址逐条添加。

国内网络如直连 GitHub 失败，可换镜像前缀：

- https://ghproxy.net/ + 原始链接
- https://gh-proxy.com/ + 原始链接

## 来源与说明

- 源数据来自公开索引页 https://0.12yue.de5.net/ （upstream: github.com/lubin776/tvbox-api-backup），镜像域 0.wudaozhe.net 等。
- 采集时间：2026-11-13/14；48 个条目逐个探测，47 个可用；去重后 34 个独立源。
- 所有条目共用同一镜像域与同一整理者，不构成真正冗余；换线只需把域名替换为 1.wudaozhe.net / 0.cdz.qzz.io / 0.wdzb.eu.cc。
- 这些配置不含 danmaku 字段，弹幕需在 App 内单独设置。
- 第三方源多为非授权内容，接口随时失效；spider 为远程 jar，权限等同普通 App。仅供学习测试，请勿用于商业用途。
