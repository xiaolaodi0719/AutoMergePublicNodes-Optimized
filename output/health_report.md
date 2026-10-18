# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 15:51:05 |
| 运行耗时 | 715.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98080 |
| 去重后节点 | 27710 |
| TCP 可达 | 3000 |
| 真实可用 | 384 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27710 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.5 |
| tcp | 48.8 |
| probe | 320.4 |
| real_test | 249.0 |
| generate | 87.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57779 |
| vmess | 16736 |
| shadowsocks | 11753 |
| trojan | 9609 |
| hysteria2 | 1308 |
| http | 613 |
| shadowsocksr | 167 |
| socks | 69 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 7 |

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
| 79.35 | vless | 249.1 | 672.2 | 22.01 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 147.45.60.160 |
| 79.23 | hysteria2 | 256.4 | 686.6 | 21.84 | 0.0 | 10.0 | 11.25 | 17.64 | Au1rxx-base64 | 129.213.91.185 |
| 78.86 | vless | 270.5 | 721.4 | 21.52 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.89 |
| 78.66 | vless | 270.9 | 657.9 | 21.51 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.104 |
| 78.54 | vless | 284.1 | 773.9 | 21.2 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 195.123.235.183 |
| 78.35 | vless | 292.3 | 655.9 | 21.01 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.74 |
| 78.12 | vless | 302.4 | 744.8 | 20.78 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.232 |
| 77.7 | vless | 320.6 | 872.4 | 20.36 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.225 |
| 77.21 | vless | 341.8 | 688.4 | 19.87 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.15 |
| 77.14 | vless | 263.0 | 647.2 | 21.69 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.184 |
| 76.99 | vless | 351.3 | 939.6 | 19.65 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.163 |
| 76.92 | vless | 354.3 | 976.8 | 19.58 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 185.95.231.156 |
| 76.77 | vless | 274.4 | 655.2 | 21.43 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.212 |
| 76.61 | vless | 367.6 | 879.9 | 19.27 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.133 |
| 76.43 | vless | 289.1 | 726.1 | 21.09 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.90 |
| 76.34 | vless | 249.4 | 653.2 | 22.0 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.202 |
| 76.3 | vless | 251.3 | 666.5 | 21.96 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.179 |
| 76.04 | shadowsocks | 370.4 | 958.4 | 19.2 | 0.0 | 10.0 | 13.7 | 17.64 | Au1rxx-base64 | 51.222.136.236 |
| 75.88 | shadowsocks | 269.5 | 701.2 | 21.54 | 0.0 | 10.0 | 13.7 | 17.64 | Au1rxx-base64 | 37.19.198.236 |
| 75.86 | vless | 324.7 | 824.9 | 20.26 | 0.0 | 10.0 | 9.7 | 17.64 | Au1rxx-base64 | 169.40.42.173 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.85 | 0.783 | 345 | 1729 | prefer |
| mheidari-all | 0.802 | 0.735 | 34 | 23775 | prefer |
| Surfboard-tg-mixed | 0.667 | 0.588 | 102 | 7095 | observe |
| ermaozi | 0.657 | 0.639 | 36 | 639 | observe |
| DeltaKronecker-all | 0.407 | 0.455 | 11 | 4750 | observe |
| Epodonios-all | 0.287 | 0.5 | 2 | 7485 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10058 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5602 | observe |
| barry-far-vless | 0.255 | None | 0 | 5815 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1729 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 43 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 15 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 13 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 11 |
| geo | TimeoutError | - | 7 |
| geo | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
