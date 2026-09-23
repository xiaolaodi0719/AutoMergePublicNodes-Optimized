# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-23 11:18:52 |
| 运行耗时 | 532.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 96837 |
| 去重后节点 | 26486 |
| TCP 可达 | 3000 |
| 真实可用 | 433 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26486 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 43.2 |
| probe | 214.5 |
| real_test | 195.3 |
| generate | 72.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59304 |
| vmess | 14980 |
| shadowsocks | 11153 |
| trojan | 8827 |
| hysteria2 | 1622 |
| http | 650 |
| shadowsocksr | 174 |
| socks | 77 |
| anytls | 24 |
| hysteria | 18 |
| tuic | 8 |

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
| 79.17 | shadowsocks | 219.7 | 526.1 | 22.69 | 0.0 | 10.0 | 14.48 | 16.0 | Surfboard-tg-mixed | 173.244.56.6 |
| 78.02 | hysteria2 | 328.2 | 738.0 | 20.18 | 0.0 | 9.55 | 14.46 | 17.64 | Au1rxx-base64 | 159.223.157.129 |
| 77.96 | shadowsocks | 271.9 | 471.0 | 21.48 | 0.0 | 10.0 | 14.48 | 16.0 | Surfboard-tg-mixed | 173.244.56.9 |
| 77.33 | shadowsocks | 241.9 | 660.9 | 22.18 | 0.0 | 9.53 | 14.48 | 17.64 | Au1rxx-base64 | 129.146.124.141 |
| 76.3 | hysteria2 | 406.5 | 719.0 | 18.37 | 0.0 | 9.52 | 14.46 | 17.64 | Au1rxx-base64 | 66.94.121.46 |
| 75.91 | vless | 195.6 | 503.7 | 23.25 | 0.0 | 9.62 | 5.4 | 17.64 | Au1rxx-base64 | 70.39.196.142 |
| 75.76 | shadowsocks | 344.3 | 879.2 | 19.81 | 0.0 | 10.0 | 14.48 | 16.0 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.69 | vless | 201.4 | 520.9 | 23.11 | 0.0 | 9.54 | 5.4 | 17.64 | Au1rxx-base64 | 172.235.43.210 |
| 75.46 | vless | 212.3 | 522.3 | 22.86 | 0.0 | 9.56 | 5.4 | 17.64 | Au1rxx-base64 | 195.123.240.65 |
| 74.71 | http | 202.1 | 521.5 | 23.1 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.202 |
| 74.71 | http | 202.2 | 517.5 | 23.1 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.203 |
| 74.68 | http | 203.4 | 513.2 | 23.07 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.216 |
| 74.65 | http | 204.7 | 508.8 | 23.04 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.213 |
| 74.63 | http | 205.4 | 535.7 | 23.02 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.220 |
| 74.63 | http | 205.6 | 513.6 | 23.02 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.204 |
| 74.62 | http | 206.0 | 525.6 | 23.01 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.206 |
| 74.6 | http | 206.7 | 532.4 | 22.99 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.207 |
| 74.57 | http | 207.9 | 531.8 | 22.96 | 0.0 | 10.0 | 10.59 | 14.02 | ermaozi | 138.199.35.211 |
| 74.5 | vless | 202.2 | 522.1 | 23.1 | 0.0 | 10.0 | 5.4 | 16.0 | Surfboard-tg-mixed | 172.235.38.85 |
| 74.47 | shadowsocks | 260.0 | 633.7 | 21.76 | 0.0 | 9.59 | 14.48 | 17.64 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.94 | 0.879 | 224 | 1602 | prefer |
| mheidari-all | 0.816 | 0.742 | 89 | 22242 | prefer |
| Surfboard-tg-mixed | 0.788 | 0.711 | 128 | 7036 | prefer |
| ermaozi | 0.76 | 0.754 | 57 | 346 | prefer |
| DeltaKronecker-all | 0.572 | 0.492 | 61 | 6471 | observe |
| ermaozi-get_subscribe | 0.296 | 0.4 | 10 | 372 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 119 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5131 | observe |
| Epodonios-all | 0.255 | None | 0 | 7633 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9066 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5755 | observe |
| barry-far-vless | 0.255 | None | 0 | 5975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4187 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| 204 | ProxyError | - | 24 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 15 |
| speed | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 5 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
