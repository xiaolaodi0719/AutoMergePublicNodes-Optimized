# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-29 19:28:51 |
| 运行耗时 | 279.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79381 |
| 去重后节点 | 22734 |
| TCP 可达 | 3000 |
| 真实可用 | 469 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22734 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 11.6 |
| geo | 1.4 |
| tcp | 32.0 |
| probe | 56.7 |
| real_test | 133.9 |
| generate | 43.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46492 |
| vmess | 10968 |
| trojan | 10595 |
| shadowsocks | 10571 |
| hysteria2 | 514 |
| shadowsocksr | 75 |
| http | 73 |
| socks | 52 |
| anytls | 26 |
| hysteria | 12 |
| tuic | 3 |

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
| 78.69 | shadowsocks | 190.2 | 475.8 | 23.38 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 108.181.118.10 |
| 78.59 | shadowsocks | 216.0 | 511.0 | 22.78 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 173.244.56.6 |
| 78.42 | shadowsocks | 223.2 | 533.7 | 22.61 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 173.244.56.9 |
| 78.33 | shadowsocks | 205.7 | 488.3 | 23.02 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 108.181.0.177 |
| 77.74 | shadowsocks | 252.5 | 596.3 | 21.93 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 149.22.95.183 |
| 75.34 | vless | 328.0 | 810.5 | 20.19 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 52.43.158.158 |
| 75.26 | vless | 187.6 | 486.3 | 23.44 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 154.19.184.40 |
| 75.15 | vless | 225.0 | 605.6 | 22.57 | 0.0 | 10.0 | 9.06 | 14.52 | Surfboard-tg-mixed | 198.41.209.87 |
| 75.03 | hysteria2 | 360.7 | 737.3 | 19.43 | 0.0 | 10.0 | 14.0 | 17.26 | Au1rxx-base64 | 159.223.157.129 |
| 75.0 | vless | 176.8 | 494.5 | 23.68 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | reseau.proxy.rlwy.net |
| 74.29 | shadowsocks | 272.7 | 282.5 | 21.47 | 4.41 | 9.89 | 12.55 | 17.26 | Au1rxx-base64 | 149.22.87.204 |
| 74.03 | vless | 219.1 | 505.9 | 22.71 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 172.247.109.66 |
| 73.72 | shadowsocks | 188.6 | 471.9 | 23.41 | 0.0 | 10.0 | 12.55 | 17.26 | Au1rxx-base64 | 185.236.200.210 |
| 73.72 | vless | 253.8 | 688.2 | 21.9 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 172.67.202.17 |
| 73.11 | trojan | 299.6 | 642.3 | 20.84 | 0.0 | 10.0 | 11.79 | 17.26 | Au1rxx-base64 | 64.94.95.114 |
| 73.1 | trojan | 304.4 | 652.1 | 20.73 | 0.0 | 10.0 | 11.79 | 17.26 | Au1rxx-base64 | 64.94.95.117 |
| 72.79 | trojan | 303.1 | 649.6 | 20.76 | 0.0 | 10.0 | 11.79 | 17.26 | Au1rxx-base64 | 64.94.95.115 |
| 72.32 | vless | 331.7 | 666.0 | 20.1 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 216.227.161.95 |
| 71.8 | vless | 315.3 | 581.7 | 20.48 | 0.0 | 10.0 | 9.06 | 17.26 | Au1rxx-base64 | 31.58.50.200 |
| 71.72 | shadowsocks | 293.1 | 341.8 | 20.99 | 2.18 | 9.89 | 12.55 | 17.26 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | 1.0 | 70 | 84 | prefer |
| Au1rxx-base64 | 0.818 | 0.764 | 276 | 1384 | prefer |
| DeltaKronecker-all | 0.683 | 0.605 | 177 | 5519 | observe |
| Surfboard-tg-mixed | 0.661 | 0.583 | 127 | 5853 | observe |
| mheidari-all | 0.489 | 0.833 | 6 | 16105 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5118 | observe |
| Epodonios-all | 0.255 | None | 0 | 6489 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6586 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4561 | observe |
| barry-far-vless | 0.255 | None | 0 | 4922 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5076 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 50 |
| 204 | TimeoutError | - | 38 |
| cn-block | TimeoutError | - | 32 |
| speed | TimeoutError | - | 26 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
