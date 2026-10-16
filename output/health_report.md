# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 16:35:40 |
| 运行耗时 | 751.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99087 |
| 去重后节点 | 27705 |
| TCP 可达 | 3000 |
| 真实可用 | 374 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27705 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.5 |
| tcp | 47.8 |
| probe | 279.1 |
| real_test | 265.5 |
| generate | 148.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58339 |
| vmess | 16359 |
| shadowsocks | 12089 |
| trojan | 10056 |
| hysteria2 | 1307 |
| http | 662 |
| shadowsocksr | 164 |
| socks | 59 |
| anytls | 29 |
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
| 79.31 | vless | 243.1 | 649.5 | 22.15 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 147.45.60.160 |
| 78.52 | hysteria2 | 258.7 | 711.0 | 21.79 | 0.0 | 10.0 | 11.25 | 16.98 | Au1rxx-base64 | 129.213.91.185 |
| 77.82 | shadowsocks | 252.0 | 692.4 | 21.94 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 37.19.198.244 |
| 77.69 | shadowsocks | 257.7 | 709.6 | 21.81 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 37.19.198.236 |
| 77.54 | shadowsocks | 264.4 | 711.9 | 21.66 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 37.19.198.243 |
| 77.39 | shadowsocks | 270.7 | 752.5 | 21.51 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 37.19.198.160 |
| 76.13 | vless | 380.6 | 995.1 | 18.97 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 66.70.179.198 |
| 76.08 | vless | 382.7 | 1028.0 | 18.92 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 185.95.231.156 |
| 75.27 | shadowsocks | 281.4 | 647.5 | 21.26 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 156.146.38.167 |
| 75.01 | shadowsocks | 282.4 | 646.6 | 21.24 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 156.146.38.169 |
| 74.88 | vless | 326.3 | 823.1 | 20.22 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 195.211.98.43 |
| 74.23 | shadowsocks | 314.1 | 738.9 | 20.51 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 156.146.38.168 |
| 72.64 | vless | 337.0 | 939.5 | 19.98 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 104.243.33.154 |
| 72.38 | vless | 326.5 | 822.7 | 20.22 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 169.40.42.75 |
| 71.67 | shadowsocks | 323.6 | 774.2 | 20.29 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 156.146.38.170 |
| 71.49 | vless | 581.0 | 1645.2 | 14.33 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 169.40.42.202 |
| 71.21 | vless | 324.2 | 757.5 | 20.27 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 69.48.201.136 |
| 71.19 | vless | 257.1 | 690.4 | 21.83 | 0.0 | 10.0 | 10.18 | 16.98 | Au1rxx-base64 | 137.184.218.169 |
| 70.4 | hysteria2 | 390.5 | 775.6 | 18.74 | 0.0 | 10.0 | 11.25 | 16.98 | Au1rxx-base64 | 62.210.124.146 |
| 70.24 | shadowsocks | 341.1 | 663.9 | 19.88 | 0.0 | 10.0 | 12.9 | 16.98 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.847 | 0.769 | 450 | 1991 | prefer |
| Surfboard-tg-mixed | 0.509 | 0.423 | 26 | 7090 | observe |
| mheidari-all | 0.432 | 0.429 | 14 | 23974 | observe |
| ermaozi-get_subscribe | 0.377 | 1.0 | 3 | 484 | observe |
| DeltaKronecker-all | 0.284 | 0.333 | 6 | 4946 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| peasoft-NoMoreWalls | 0.261 | 1.0 | 1 | 143 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9917 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5822 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 34 |
| 204 | ProxyError | - | 28 |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 12 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 9 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 7 |
| speed | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
