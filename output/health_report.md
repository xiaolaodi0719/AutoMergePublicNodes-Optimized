# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 22:39:05 |
| 运行耗时 | 662.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97854 |
| 去重后节点 | 27601 |
| TCP 可达 | 3000 |
| 真实可用 | 444 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27601 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.7 |
| tcp | 47.5 |
| probe | 250.2 |
| real_test | 274.8 |
| generate | 79.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57405 |
| vmess | 15656 |
| shadowsocks | 11874 |
| trojan | 10602 |
| hysteria2 | 1499 |
| http | 506 |
| shadowsocksr | 173 |
| socks | 79 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 13 |

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
| 79.45 | vless | 242.3 | 539.2 | 22.17 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 144.202.126.147 |
| 78.45 | shadowsocks | 240.4 | 617.0 | 22.21 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 156.146.38.168 |
| 78.38 | shadowsocks | 243.4 | 609.3 | 22.14 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 156.146.38.169 |
| 77.82 | vless | 236.5 | 515.1 | 22.3 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 47.251.108.158 |
| 77.33 | shadowsocks | 245.6 | 631.3 | 22.09 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 156.146.38.167 |
| 77.25 | vless | 280.3 | 596.0 | 21.29 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 195.123.240.65 |
| 77.11 | vless | 268.4 | 594.4 | 21.56 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 15.204.97.216 |
| 76.96 | shadowsocks | 244.4 | 616.2 | 22.12 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 156.146.38.170 |
| 76.95 | vless | 270.1 | 598.7 | 21.52 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 15.204.97.197 |
| 76.25 | hysteria2 | 316.3 | 740.1 | 20.46 | 0.0 | 10.0 | 12.35 | 18.08 | Au1rxx-base64 | 129.213.91.185 |
| 75.27 | vless | 350.9 | 805.7 | 19.66 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 107.173.237.146 |
| 74.36 | shadowsocks | 339.8 | 850.5 | 19.91 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 5.78.51.123 |
| 74.11 | hysteria2 | 307.0 | 282.5 | 20.67 | 4.41 | 6.37 | 12.35 | 18.08 | Au1rxx-base64 | open.2ml.bid |
| 73.24 | hysteria2 | 333.9 | 385.0 | 20.05 | 0.56 | 9.67 | 12.35 | 18.08 | Au1rxx-base64 | 158.101.148.79 |
| 72.99 | shadowsocks | 304.2 | 299.7 | 20.74 | 3.76 | 9.79 | 12.16 | 18.08 | Au1rxx-base64 | 149.22.87.241 |
| 72.88 | vless | 266.9 | 591.0 | 21.6 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 15.204.97.219 |
| 72.83 | shadowsocks | 300.6 | 588.8 | 20.82 | 0.0 | 10.0 | 12.16 | 18.08 | Au1rxx-base64 | 108.181.0.177 |
| 72.69 | vless | 297.3 | 664.7 | 20.9 | 0.0 | 10.0 | 10.35 | 14.94 | mheidari-all | 195.211.98.43 |
| 72.45 | vless | 373.0 | 798.0 | 19.14 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 66.70.179.198 |
| 72.33 | vless | 386.6 | 826.5 | 18.83 | 0.0 | 10.0 | 10.35 | 18.08 | Au1rxx-base64 | 23.95.222.127 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 1.0 | 0.963 | 27 | 7025 | prefer |
| Au1rxx-base64 | 0.99 | 0.92 | 373 | 1805 | prefer |
| mheidari-all | 0.916 | 0.846 | 65 | 23076 | prefer |
| zhangkai | 0.779 | 0.938 | 16 | 144 | prefer |
| tg-V2RAYProxy | 0.264 | 1.0 | 1 | 217 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7582 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9986 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5812 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4346 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1805 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
