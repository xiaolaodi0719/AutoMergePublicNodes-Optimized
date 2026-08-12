# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 13:24:52 |
| 运行耗时 | 277.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 80139 |
| 去重后节点 | 22314 |
| TCP 可达 | 3000 |
| 真实可用 | 554 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22314 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.3 |
| geo | 1.4 |
| tcp | 33.7 |
| probe | 55.9 |
| real_test | 134.6 |
| generate | 38.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46104 |
| vmess | 13300 |
| shadowsocks | 9639 |
| trojan | 9472 |
| hysteria2 | 1302 |
| http | 159 |
| socks | 73 |
| shadowsocksr | 71 |
| tuic | 11 |
| hysteria | 7 |
| anytls | 1 |

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
| 81.75 | hysteria2 | 258.3 | 680.9 | 21.8 | 0.0 | 10.0 | 12.75 | 18.2 | Au1rxx-base64 | 138.124.68.188 |
| 81.65 | hysteria2 | 258.3 | 675.2 | 21.8 | 0.0 | 10.0 | 12.75 | 18.2 | Au1rxx-base64 | 159.223.157.129 |
| 80.39 | http | 399.6 | 1091.9 | 18.53 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 80.28 | http | 404.2 | 1106.1 | 18.42 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 80.23 | http | 406.6 | 1110.5 | 18.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 79.98 | http | 417.1 | 1126.4 | 18.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 79.92 | shadowsocks | 253.2 | 672.4 | 21.92 | 0.0 | 10.0 | 13.8 | 18.2 | Au1rxx-base64 | 37.19.198.236 |
| 79.88 | http | 421.7 | 1143.5 | 18.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 79.8 | shadowsocks | 258.4 | 686.0 | 21.8 | 0.0 | 10.0 | 13.8 | 18.2 | Au1rxx-base64 | 37.19.198.160 |
| 79.32 | http | 402.4 | 1087.3 | 18.46 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 79.26 | http | 405.0 | 1114.7 | 18.4 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.11 |
| 79.21 | http | 407.2 | 1109.4 | 18.35 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.15 |
| 79.17 | http | 409.2 | 1103.9 | 18.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.10 |
| 79.04 | http | 414.8 | 1136.4 | 18.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.19 |
| 78.99 | shadowsocks | 250.1 | 677.0 | 21.99 | 0.0 | 10.0 | 13.8 | 18.2 | Au1rxx-base64 | 37.19.198.243 |
| 78.95 | http | 418.7 | 1140.3 | 18.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |
| 77.01 | http | 545.5 | 1520.1 | 15.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 76.98 | http | 546.9 | 1525.9 | 15.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 76.71 | hysteria2 | 259.6 | 710.1 | 21.77 | 0.0 | 4.99 | 12.75 | 18.2 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 76.47 | http | 525.8 | 1460.1 | 15.61 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.27 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.911 | 0.846 | 428 | 1660 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.624 | 85 | 6099 | prefer |
| mheidari-all | 0.373 | 0.6 | 5 | 16658 | observe |
| DeltaKronecker-all | 0.372 | 0.273 | 22 | 4975 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7502 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4929 | observe |
| barry-far-vless | 0.255 | None | 0 | 5264 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 14 |
| 204 | ProxyError | - | 12 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
