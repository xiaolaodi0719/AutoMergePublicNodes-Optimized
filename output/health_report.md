# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-26 21:01:53 |
| 运行耗时 | 558.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 96520 |
| 去重后节点 | 26455 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26455 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 43.6 |
| probe | 217.8 |
| real_test | 210.2 |
| generate | 79.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58929 |
| vmess | 14943 |
| shadowsocks | 11304 |
| trojan | 8927 |
| hysteria2 | 1509 |
| http | 611 |
| shadowsocksr | 170 |
| socks | 77 |
| anytls | 25 |
| hysteria | 15 |
| tuic | 10 |

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
| 82.32 | vless | 209.0 | 522.6 | 22.94 | 0.0 | 9.57 | 11.15 | 18.66 | Au1rxx-base64 | 195.123.240.65 |
| 81.93 | vless | 222.4 | 574.1 | 22.63 | 0.0 | 9.49 | 11.15 | 18.66 | Au1rxx-base64 | 38.244.20.25 |
| 81.28 | vless | 252.4 | 619.8 | 21.94 | 0.0 | 9.53 | 11.15 | 18.66 | Au1rxx-base64 | 137.175.82.40 |
| 79.7 | hysteria2 | 271.9 | 272.9 | 21.48 | 4.77 | 8.25 | 13.57 | 18.66 | Au1rxx-base64 | open.w2m.ink |
| 79.19 | shadowsocks | 233.7 | 559.5 | 22.37 | 0.0 | 9.5 | 12.66 | 18.66 | Au1rxx-base64 | 173.244.56.9 |
| 78.64 | shadowsocks | 260.2 | 634.5 | 21.76 | 0.0 | 9.56 | 12.66 | 18.66 | Au1rxx-base64 | 156.146.38.169 |
| 78.11 | vless | 215.2 | 509.3 | 22.8 | 0.0 | 9.5 | 11.15 | 18.66 | Au1rxx-base64 | 173.249.207.28 |
| 78.07 | vless | 254.7 | 575.3 | 21.88 | 0.0 | 9.6 | 11.15 | 18.66 | Au1rxx-base64 | 23.95.222.127 |
| 77.35 | vless | 230.5 | 531.2 | 22.44 | 0.0 | 9.6 | 11.15 | 18.66 | Au1rxx-base64 | 188.114.97.6 |
| 76.43 | shadowsocks | 222.1 | 545.2 | 22.64 | 0.0 | 9.47 | 12.66 | 18.66 | Au1rxx-base64 | 173.244.56.6 |
| 76.39 | vless | 270.8 | 485.5 | 21.51 | 0.0 | 9.57 | 11.15 | 18.66 | Au1rxx-base64 | 104.18.46.234 |
| 76.34 | vless | 335.2 | 771.3 | 20.02 | 0.0 | 9.5 | 11.15 | 18.66 | Au1rxx-base64 | 79.141.172.154 |
| 76.08 | shadowsocks | 266.8 | 655.5 | 21.6 | 0.0 | 10.0 | 12.66 | 16.32 | Surfboard-tg-mixed | 108.181.118.10 |
| 75.95 | shadowsocks | 272.7 | 680.6 | 21.47 | 0.0 | 10.0 | 12.66 | 16.32 | Surfboard-tg-mixed | 108.181.0.177 |
| 75.83 | vless | 248.6 | 484.1 | 22.02 | 0.0 | 9.6 | 11.15 | 18.66 | Au1rxx-base64 | 104.18.47.113 |
| 75.47 | shadowsocks | 212.0 | 552.3 | 22.87 | 0.0 | 10.0 | 12.66 | 14.44 | mheidari-all | 192.3.247.109 |
| 75.16 | vless | 238.7 | 515.4 | 22.25 | 0.0 | 9.6 | 11.15 | 18.66 | Au1rxx-base64 | 162.159.43.187 |
| 74.93 | trojan | 247.3 | 506.4 | 22.05 | 0.0 | 10.0 | 12.86 | 14.44 | mheidari-all | 100.42.228.109 |
| 74.86 | vless | 338.3 | 401.1 | 19.95 | 0.0 | 9.6 | 11.15 | 18.66 | Au1rxx-base64 | 172.64.229.170 |
| 74.8 | shadowsocks | 187.2 | 493.4 | 23.45 | 0.0 | 9.53 | 12.66 | 18.66 | Au1rxx-base64 | 216.105.168.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.95 | 0.887 | 282 | 1654 | prefer |
| Surfboard-tg-mixed | 0.784 | 0.708 | 113 | 7263 | prefer |
| mheidari-all | 0.614 | 0.535 | 114 | 22366 | observe |
| ermaozi | 0.426 | 0.421 | 19 | 296 | observe |
| DeltaKronecker-all | 0.349 | 0.667 | 3 | 5512 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4355 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5242 | observe |
| Epodonios-all | 0.255 | None | 0 | 7740 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8923 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6052 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1654 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | ClientOSError | - | 35 |
| 204 | TimeoutError | - | 35 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 11 |
| geo | TimeoutError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 5 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
