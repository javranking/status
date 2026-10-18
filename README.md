# JavRanking Official Status & Mirror Directory
# JavRanking 官方可用网址发布与状态中心

> **Status: All Systems Operational · 所有节点正常运行**  
> **Official Repository / 官方唯一防失联发布仓库**: [github.com/javranking/status](https://github.com/javranking/status)  
> **GitHub Pages / 网页版在线测速**: [javranking.github.io/status](https://javranking.github.io/status/)

---

## ⚡️ Quick Access / 快速直达

| 线路类型 / Gateway Type | 官方网址 / Official URL | 线路定位 / Purpose & Role | 连通性状态 / Status |
| :--- | :--- | :--- | :--- |
| **官方主力主站 (Primary)** | **[https://javranking.cc](https://javranking.cc)** | **日常首选主站**：全量权威排行榜、神作探索、4K预告与冲码跨端标记 | 🟢 正常服务 (Operational) |
| **官方常青中转站 (Relay)** | **[https://javranking.top](https://javranking.top)** | **合规常青中转**：纯净无敏感内容，专职全路由安全重定向，长期抗封 | 🟢 长期在线 (Clean Gateway) |
| **应急找回邮箱 (Email)** | **[contact@javranking.cc](mailto:contact@javranking.cc)** | **离线应急通道**：发送任意邮件，系统秒级自动回复最新可用网址 | 🟢 自动回复 (Auto-Reply) |

---

## 🧭 系统定位与关系说明 (Architecture Overview)

JavRanking 采用**“三位一体”**的去中心化防失联体系，确保无论任何局部网络受到何种程度的干扰，影迷均能无缝找到最新可用入口：

1. **`javranking.cc`（核心主站）**：
   - 包含历年 JavDB Top 250、年度精选、女优战力榜、独家加权积分算法及高清预告片库。
   - 采用纯静态 SSG 架构与全球 Anycast 分布式 CDN，日常访问体验最完整。
2. **`javranking.top`（常青导航站）**：
   - JavRanking 的原始品牌域名。为符合注册局合规要求，该域名**不承载任何敏感成人内容**，专职作为中立纯净的“域名迁移通知与安全重定向导航站”。
   - 正因为纯净合规，它不会被注册局二次封停，成为立于风暴之外的永久中转哨所。
3. **`GitHub 永久发布页`（本仓库）**：
   - 托管于 GitHub 全球抗封锁基础设施，脱离商业顶级域名审核体系。
   - 是全网最高权威的真实源（Single Source of Truth），发生任何突发域名调整时在此第一时间广播。

---

## 🛠️ 网络排障与访问优化 (Troubleshooting Guide)

如果遇到网页打不开或提示“连接被重置（ERR_CONNECTION_RESET）”，95% 以上是由于本地运营商的 DNS 劫持污染或 SNI 过滤引起，并非网站服务器故障。

### 推荐方案一：配置公共纯净安全 DNS 并开启 DoH（免翻墙首选）

将设备或路由器的默认 DNS 更改为知名公共 DNS，并在浏览器中开启“基于 HTTPS 的安全 DNS (DoH)”：

- **Google Public DNS**: `8.8.8.8` / `8.8.4.4`  
  DoH 地址: `https://dns.google/dns-query`
- **阿里公共 DNS (AliDNS)**: `223.5.5.5` / `223.6.6.6`  
  DoH 地址: `https://dns.alidns.com/dns-query`
- **114 DNS**: `114.114.114.114` / `114.114.115.115`

#### 浏览器开启安全 DNS (DoH) 步骤：
1. **Chrome / Edge**: 打开「设置」->「隐私和安全性」->「安全」-> 找到「使用安全 DNS」-> 选择自定义提供商（如 Google 或 AliDNS）。
2. **Firefox**: 打开「设置」->「隐私与安全」->「基于 HTTPS 的 DNS」-> 选择「最大保护」或「增强保护」。

### 推荐方案二：搭配代理工具（VPN / Proxy）

- 如遇高级别 SNI 阻断，建议开启代理工具并优先选择 **中国香港 (HK)、中国台湾 (TW)、日本 (JP)、新加坡 (SG)** 等亚太低延迟高速节点。
- 若代理支持分流规则（如 Clash、Sing-box、Surge），可将 `javranking.cc` 与 `javranking.top` 添加至代理规则列表（Proxy）。

---

## 🛡️ 官方防伪与防诈骗严正声明 (Security Notice)

- **100% 免费与无账号体系**：JavRanking 是纯静态公开排行榜，**无账号登录、无注册充值、无会员 VIP 等级、无私下打赏**。
- **100% 无流氓广告**：站点坚守克制审美，绝无恶意跳转、悬浮拦截弹窗、诱导下载可疑 APK/APP、博彩或菠菜推广。
- **警惕假冒钓鱼**：任何打着 JavRanking 旗号要求“付费看片、加微信/QQ 私聊转账、输入银行卡密码”的网站均为假冒钓鱼，请立即关闭举报！
- **官方域名唯二**：官方公开域名仅以 `javranking.cc` 与 `javranking.top` 为准。

---

## 📜 域名变更与维护记录 (Changelog)

- **2026-10**：正式上线 `javranking/status` GitHub 永久状态发布仓库与 GitHub Pages 网页版；主站正式集成地址发布页 `/domains/`。
- **2026-09**：针对 `.top` 注册局监管合规进行彻底改造，将 `javranking.top` 转型为永久合规纯净中转导航站（`deploy/redirect-top`），全面解封并恢复服务。
- **2026-08**：主站全量迁移至全新主力域名 `javranking.cc`，完成 SSG 全站静态架构与双语国际化升级。

---

© 2026 JavRanking · Curated Adult Video Rankings & Anti-Lost Status Hub
