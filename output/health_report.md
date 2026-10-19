# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 12:51:33 |
| 运行耗时 | 610.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95095 |
| 去重后节点 | 26228 |
| TCP 可达 | 3000 |
| 真实可用 | 361 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26228 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 44.4 |
| probe | 243.5 |
| real_test | 222.8 |
| generate | 93.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55617 |
| vmess | 16652 |
| shadowsocks | 11632 |
| trojan | 8885 |
| hysteria2 | 1509 |
| http | 496 |
| shadowsocksr | 172 |
| socks | 63 |
| anytls | 46 |
| hysteria | 17 |
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
| 80.95 | shadowsocks | 210.4 | 526.6 | 22.91 | 0.0 | 10.0 | 13.94 | 18.1 | Au1rxx-base64 | 173.244.56.9 |
| 79.99 | shadowsocks | 217.4 | 543.7 | 22.74 | 0.0 | 9.21 | 13.94 | 18.1 | Au1rxx-base64 | 173.244.56.6 |
| 79.0 | hysteria2 | 272.7 | 634.5 | 21.46 | 0.0 | 10.0 | 13.7 | 18.1 | Au1rxx-base64 | 66.94.121.46 |
| 78.96 | shadowsocks | 262.0 | 635.7 | 21.71 | 0.0 | 9.21 | 13.94 | 18.1 | Au1rxx-base64 | 156.146.38.168 |
| 78.6 | vless | 223.2 | 550.3 | 22.61 | 0.0 | 9.25 | 8.64 | 18.1 | Au1rxx-base64 | 195.123.240.65 |
| 77.75 | shadowsocks | 262.1 | 635.8 | 21.71 | 0.0 | 10.0 | 13.94 | 18.1 | Au1rxx-base64 | 156.146.38.169 |
| 76.0 | shadowsocks | 290.8 | 625.7 | 21.05 | 0.0 | 10.0 | 13.94 | 18.1 | Au1rxx-base64 | 149.22.95.183 |
| 75.97 | shadowsocks | 262.6 | 639.5 | 21.7 | 0.0 | 9.23 | 13.94 | 18.1 | Au1rxx-base64 | 156.146.38.167 |
| 75.67 | vless | 187.5 | 489.7 | 23.44 | 0.0 | 10.0 | 8.64 | 18.1 | Au1rxx-base64 | 131.143.180.87 |
| 74.99 | shadowsocks | 281.6 | 287.7 | 21.26 | 4.21 | 9.91 | 13.94 | 18.1 | Au1rxx-base64 | 149.22.87.240 |
| 74.93 | vless | 198.5 | 515.0 | 23.18 | 0.0 | 10.0 | 8.64 | 18.1 | Au1rxx-base64 | 45.63.53.81 |
| 74.46 | shadowsocks | 296.1 | 324.4 | 20.92 | 2.84 | 9.9 | 13.94 | 18.1 | Au1rxx-base64 | 149.22.87.241 |
| 74.0 | vless | 245.7 | 553.1 | 22.09 | 0.0 | 10.0 | 8.64 | 18.1 | Au1rxx-base64 | 23.95.222.127 |
| 73.45 | shadowsocks | 297.3 | 331.2 | 20.9 | 2.58 | 9.21 | 13.94 | 18.1 | Au1rxx-base64 | 149.22.87.204 |
| 73.4 | vless | 410.8 | 914.2 | 18.27 | 0.0 | 9.23 | 8.64 | 18.1 | Au1rxx-base64 | 95.111.212.241 |
| 73.0 | trojan | 487.6 | 1238.6 | 16.49 | 0.0 | 10.0 | 14.14 | 18.1 | Au1rxx-base64 | 66.23.203.21 |
| 72.78 | trojan | 369.0 | 310.8 | 19.24 | 3.34 | 8.05 | 14.14 | 18.1 | Au1rxx-base64 | jp.tronsg.com |
| 72.67 | shadowsocks | 365.9 | 795.1 | 19.31 | 0.0 | 10.0 | 13.94 | 18.1 | Au1rxx-base64 | 37.19.198.236 |
| 72.37 | vless | 277.9 | 619.5 | 21.35 | 0.0 | 10.0 | 8.64 | 18.1 | Au1rxx-base64 | 15.204.97.219 |
| 72.22 | vless | 283.3 | 647.9 | 21.22 | 0.0 | 10.0 | 8.64 | 18.1 | Au1rxx-base64 | 181.214.152.137 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | 0.818 | 374 | 1717 | prefer |
| Surfboard-tg-mixed | 0.647 | 0.569 | 58 | 6948 | observe |
| zhangkai | 0.555 | 1.0 | 8 | 144 | observe |
| mheidari-all | 0.501 | 0.444 | 18 | 23446 | observe |
| ermaozi | 0.441 | 1.0 | 5 | 42 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| Epodonios-all | 0.255 | None | 0 | 7331 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10132 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5438 | observe |
| barry-far-vless | 0.255 | None | 0 | 5622 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1717 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 18 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 15 |
| speed | ClientOSError | - | 14 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| geo | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
