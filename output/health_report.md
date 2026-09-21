# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 22:01:41 |
| 运行耗时 | 616.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 88299 |
| 去重后节点 | 25177 |
| TCP 可达 | 3000 |
| 真实可用 | 535 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 42.2 |
| probe | 242.3 |
| real_test | 238.2 |
| generate | 86.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52966 |
| vmess | 14150 |
| shadowsocks | 10240 |
| trojan | 8810 |
| hysteria2 | 1268 |
| http | 627 |
| shadowsocksr | 139 |
| socks | 67 |
| hysteria | 14 |
| anytls | 12 |
| tuic | 6 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 81.03 | vless | 220.5 | 501.5 | 22.67 | 0.0 | 10.0 | 9.62 | 18.74 | mheidari-all | 47.251.108.158 |
| 80.95 | vless | 207.2 | 524.4 | 22.98 | 0.0 | 9.59 | 9.62 | 18.76 | Au1rxx-base64 | 172.235.43.210 |
| 79.93 | shadowsocks | 261.9 | 633.3 | 21.72 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 156.146.38.168 |
| 79.16 | shadowsocks | 271.2 | 676.5 | 21.5 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 108.181.118.10 |
| 78.08 | hysteria2 | 359.4 | 800.5 | 19.46 | 0.0 | 10.0 | 14.21 | 18.74 | mheidari-all | 159.223.157.129 |
| 76.99 | shadowsocks | 263.1 | 635.6 | 21.69 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 23.150.248.20 |
| 76.49 | vless | 276.5 | 612.5 | 21.38 | 0.0 | 9.82 | 9.62 | 18.76 | Au1rxx-base64 | 15.204.97.216 |
| 76.48 | vless | 201.2 | 521.0 | 23.12 | 0.0 | 10.0 | 9.62 | 18.74 | mheidari-all | 172.233.139.46 |
| 75.77 | shadowsocks | 245.2 | 519.1 | 22.1 | 0.0 | 10.0 | 13.49 | 14.18 | Surfboard-tg-mixed | 173.244.56.9 |
| 75.69 | shadowsocks | 291.8 | 627.6 | 21.02 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 149.22.95.183 |
| 75.67 | shadowsocks | 249.5 | 503.6 | 22.0 | 0.0 | 10.0 | 13.49 | 14.18 | Surfboard-tg-mixed | 173.244.56.6 |
| 75.17 | vless | 329.7 | 747.7 | 20.15 | 0.0 | 9.59 | 9.62 | 18.76 | Au1rxx-base64 | 79.141.172.154 |
| 74.2 | shadowsocks | 265.0 | 646.8 | 21.64 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 156.146.38.170 |
| 74.19 | shadowsocks | 299.2 | 748.9 | 20.85 | 0.0 | 10.0 | 13.49 | 14.18 | Surfboard-tg-mixed | 156.146.38.169 |
| 73.79 | vless | 206.7 | 538.1 | 22.99 | 0.0 | 10.0 | 9.62 | 14.18 | Surfboard-tg-mixed | 172.235.38.85 |
| 73.67 | shadowsocks | 262.7 | 632.4 | 21.7 | 0.0 | 10.0 | 13.49 | 14.18 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.91 | vless | 286.9 | 456.7 | 21.14 | 0.0 | 9.64 | 9.62 | 18.76 | Au1rxx-base64 | 162.159.43.187 |
| 72.61 | shadowsocks | 373.2 | 822.5 | 19.14 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 37.19.198.160 |
| 72.59 | vless | 350.3 | 703.9 | 19.67 | 0.0 | 9.61 | 9.62 | 18.76 | Au1rxx-base64 | 195.211.98.43 |
| 72.56 | shadowsocks | 368.2 | 803.3 | 19.26 | 0.0 | 10.0 | 13.49 | 18.74 | mheidari-all | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.912 | 0.845 | 277 | 1752 | prefer |
| Surfboard-tg-mixed | 0.714 | 0.636 | 151 | 7121 | prefer |
| mheidari-all | 0.633 | 0.554 | 327 | 20197 | observe |
| ermaozi | 0.593 | 0.583 | 36 | 350 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 377 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 138 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5290 | observe |
| Epodonios-all | 0.255 | None | 0 | 7717 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8749 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5672 | observe |
| barry-far-vless | 0.255 | None | 0 | 6075 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 61 |
| geo | ClientOSError | - | 51 |
| geo | TimeoutError | - | 43 |
| speed | ClientOSError | - | 30 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 13 |
| speed | TimeoutError | - | 11 |
| 204 | ProxyConnectionError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
