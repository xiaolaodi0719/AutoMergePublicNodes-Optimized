# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 22:39:12 |
| 运行耗时 | 671.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98441 |
| 去重后节点 | 27354 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27354 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 47.4 |
| probe | 239.1 |
| real_test | 279.8 |
| generate | 97.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58285 |
| vmess | 16010 |
| shadowsocks | 11817 |
| trojan | 10346 |
| hysteria2 | 1277 |
| http | 424 |
| shadowsocksr | 171 |
| socks | 61 |
| anytls | 26 |
| hysteria | 18 |
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
| 80.83 | hysteria2 | 284.7 | 720.5 | 21.19 | 0.0 | 10.0 | 12.5 | 18.64 | Au1rxx-base64 | 129.213.91.185 |
| 79.44 | shadowsocks | 245.0 | 604.1 | 22.11 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 156.146.38.169 |
| 79.31 | shadowsocks | 261.4 | 639.0 | 21.73 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 156.146.38.168 |
| 79.09 | hysteria2 | 275.4 | 596.3 | 21.4 | 0.0 | 9.97 | 12.5 | 18.64 | Au1rxx-base64 | 66.94.121.46 |
| 79.05 | vless | 276.5 | 675.7 | 21.38 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 147.45.60.160 |
| 78.12 | shadowsocks | 307.4 | 742.3 | 20.66 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 37.19.198.236 |
| 78.09 | shadowsocks | 258.7 | 638.1 | 21.79 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 156.146.38.167 |
| 76.88 | vless | 328.2 | 717.5 | 20.18 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 159.89.87.21 |
| 76.78 | shadowsocks | 302.5 | 739.7 | 20.77 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 37.19.198.243 |
| 76.61 | vless | 246.3 | 603.7 | 22.08 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 38.180.137.143 |
| 76.47 | vless | 347.3 | 757.0 | 19.74 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 66.70.179.198 |
| 76.37 | vless | 278.7 | 538.3 | 21.33 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 47.251.108.158 |
| 76.14 | vless | 296.6 | 589.5 | 20.91 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 144.202.126.147 |
| 75.71 | vless | 342.1 | 757.0 | 19.86 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 167.17.69.171 |
| 75.57 | shadowsocks | 315.2 | 762.0 | 20.48 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 37.19.198.244 |
| 75.29 | vless | 390.7 | 908.7 | 18.73 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 169.40.42.104 |
| 75.04 | vless | 308.3 | 594.0 | 20.64 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 195.123.240.65 |
| 74.73 | shadowsocks | 286.8 | 578.3 | 21.14 | 0.0 | 10.0 | 12.94 | 18.64 | Au1rxx-base64 | 173.244.56.9 |
| 74.73 | vless | 293.2 | 664.0 | 20.99 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 69.48.201.136 |
| 74.35 | vless | 357.5 | 719.1 | 19.5 | 0.0 | 10.0 | 10.89 | 18.64 | Au1rxx-base64 | 169.40.42.212 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 0.967 | 60 | 23973 | prefer |
| Au1rxx-base64 | 0.973 | 0.903 | 352 | 1806 | prefer |
| Surfboard-tg-mixed | 0.945 | 0.88 | 50 | 7123 | prefer |
| zhangkai | 0.686 | 0.696 | 23 | 144 | observe |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 5076 | observe |
| ermaozi-get_subscribe | 0.314 | 0.6 | 5 | 534 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9832 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5683 | observe |
| barry-far-vless | 0.255 | None | 0 | 5929 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyConnectionError | - | 9 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 4 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ClientOSError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
