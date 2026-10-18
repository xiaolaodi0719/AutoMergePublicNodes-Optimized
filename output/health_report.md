# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 10:54:11 |
| 运行耗时 | 723.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98645 |
| 去重后节点 | 27677 |
| TCP 可达 | 3000 |
| 真实可用 | 409 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27677 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.5 |
| tcp | 49.3 |
| probe | 297.5 |
| real_test | 293.6 |
| generate | 76.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57464 |
| vmess | 16504 |
| shadowsocks | 12003 |
| trojan | 9969 |
| hysteria2 | 1653 |
| http | 750 |
| shadowsocksr | 170 |
| socks | 85 |
| anytls | 24 |
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
| 81.99 | hysteria2 | 295.2 | 730.3 | 20.94 | 0.0 | 10.0 | 14.29 | 18.26 | Au1rxx-base64 | 129.213.91.185 |
| 80.32 | hysteria2 | 299.0 | 620.4 | 20.86 | 0.0 | 10.0 | 14.29 | 18.26 | Au1rxx-base64 | 66.94.121.46 |
| 80.16 | shadowsocks | 272.0 | 740.7 | 21.48 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 156.146.38.168 |
| 79.05 | shadowsocks | 257.9 | 574.3 | 21.81 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 173.244.56.6 |
| 78.83 | shadowsocks | 253.3 | 561.9 | 21.91 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 173.244.56.9 |
| 76.65 | trojan | 327.5 | 881.9 | 20.2 | 0.0 | 10.0 | 12.19 | 18.26 | Au1rxx-base64 | 66.23.203.21 |
| 76.28 | shadowsocks | 325.6 | 766.2 | 20.24 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 37.19.198.243 |
| 76.17 | shadowsocks | 325.1 | 768.0 | 20.25 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 37.19.198.160 |
| 75.37 | vless | 301.0 | 648.0 | 20.81 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 212.104.141.233 |
| 75.36 | shadowsocks | 263.6 | 721.0 | 21.68 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 156.146.38.170 |
| 75.15 | vless | 259.6 | 551.2 | 21.77 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 67.209.184.133 |
| 74.7 | vless | 288.4 | 596.6 | 21.1 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 154.29.145.196 |
| 74.41 | vless | 256.4 | 533.9 | 21.84 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 47.77.196.79 |
| 74.31 | shadowsocks | 319.8 | 315.4 | 20.37 | 3.17 | 9.72 | 14.42 | 18.26 | Au1rxx-base64 | 149.22.87.204 |
| 73.79 | vless | 285.2 | 593.3 | 21.18 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 154.40.55.185 |
| 73.61 | shadowsocks | 333.1 | 654.9 | 20.07 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 149.22.95.183 |
| 73.57 | vless | 337.6 | 724.9 | 19.96 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 154.12.38.202 |
| 73.33 | vless | 301.8 | 588.5 | 20.79 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 23.95.222.127 |
| 72.83 | shadowsocks | 349.5 | 839.8 | 19.69 | 0.0 | 10.0 | 14.42 | 18.26 | Au1rxx-base64 | 37.19.198.244 |
| 72.63 | vless | 355.6 | 786.5 | 19.55 | 0.0 | 10.0 | 8.94 | 18.26 | Au1rxx-base64 | 5.34.178.120 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | 0.806 | 408 | 1920 | prefer |
| ermaozi | 0.558 | 0.53 | 100 | 710 | observe |
| Surfboard-tg-mixed | 0.433 | 0.348 | 66 | 7030 | observe |
| mheidari-all | 0.281 | 0.214 | 14 | 23769 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| Epodonios-all | 0.255 | None | 0 | 7561 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10015 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5615 | observe |
| barry-far-vless | 0.255 | None | 0 | 5830 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.252 | None | 0 | 1920 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| DeltaKronecker-all | 0.226 | 0.2 | 5 | 4750 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 49 |
| 204 | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 26 |
| geo | ClientOSError | - | 18 |
| 204 | ClientOSError | - | 12 |
| geo | TimeoutError | - | 11 |
| speed | TimeoutError | - | 10 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
