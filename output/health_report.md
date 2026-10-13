# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 14:06:40 |
| 运行耗时 | 759.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99026 |
| 去重后节点 | 27329 |
| TCP 可达 | 3000 |
| 真实可用 | 393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27329 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.2 |
| tcp | 46.3 |
| probe | 303.8 |
| real_test | 311.8 |
| generate | 88.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58303 |
| vmess | 16033 |
| shadowsocks | 12008 |
| trojan | 10670 |
| hysteria2 | 1299 |
| http | 435 |
| shadowsocksr | 169 |
| socks | 59 |
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
| 83.44 | hysteria2 | 266.4 | 732.7 | 21.61 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 82.18 | shadowsocks | 263.5 | 708.9 | 21.68 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 82.12 | shadowsocks | 266.0 | 719.5 | 21.62 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.88 | shadowsocks | 254.7 | 670.7 | 21.88 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 140.82.63.79 |
| 81.72 | shadowsocks | 283.2 | 763.3 | 21.22 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.71 | shadowsocks | 348.6 | 921.5 | 19.71 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 64.74.163.69 |
| 79.69 | shadowsocks | 282.4 | 653.5 | 21.24 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.7 | shadowsocks | 315.6 | 755.5 | 20.47 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.78 | vless | 269.8 | 686.1 | 21.53 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 76.54 | shadowsocks | 315.3 | 756.3 | 20.48 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.48 | vless | 282.7 | 723.8 | 21.23 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 76.43 | vless | 284.8 | 668.0 | 21.18 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 76.08 | vless | 300.0 | 739.0 | 20.83 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 75.81 | trojan | 465.8 | 1295.5 | 17.0 | 0.0 | 10.0 | 13.81 | 20.0 | Au1rxx-base64 | 69.164.240.85 |
| 75.76 | vless | 294.9 | 628.8 | 20.95 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.173 |
| 75.13 | vless | 341.2 | 899.3 | 19.88 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 74.8 | shadowsocks | 327.1 | 596.2 | 20.21 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 74.69 | vless | 360.0 | 860.3 | 19.44 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.163 |
| 74.67 | shadowsocks | 332.9 | 613.3 | 20.07 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 74.51 | vless | 367.8 | 853.1 | 19.26 | 0.0 | 10.0 | 5.25 | 20.0 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | 0.864 | 317 | 1754 | prefer |
| mheidari-all | 0.813 | 0.744 | 43 | 24075 | prefer |
| Surfboard-tg-mixed | 0.77 | 0.696 | 69 | 7201 | prefer |
| DeltaKronecker-all | 0.756 | 0.686 | 35 | 5076 | prefer |
| zhangkai | 0.572 | 0.769 | 13 | 144 | observe |
| ermaozi-get_subscribe | 0.302 | 0.278 | 18 | 534 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7717 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9931 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5723 | observe |
| barry-far-vless | 0.255 | None | 0 | 5973 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4312 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 32 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 14 |
| geo | TimeoutError | - | 10 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
