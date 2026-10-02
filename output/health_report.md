# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 05:14:10 |
| 运行耗时 | 941.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98630 |
| 去重后节点 | 27538 |
| TCP 可达 | 3000 |
| 真实可用 | 427 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27538 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.7 |
| tcp | 47.9 |
| probe | 346.0 |
| real_test | 505.2 |
| generate | 34.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60091 |
| vmess | 15752 |
| shadowsocks | 11577 |
| trojan | 8982 |
| hysteria2 | 1429 |
| http | 509 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 35 |
| hysteria | 17 |
| tuic | 9 |

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
| 81.89 | vless | 239.8 | 526.4 | 22.23 | 0.0 | 10.0 | 12.38 | 19.1 | mheidari-all | 47.251.108.158 |
| 81.56 | vless | 305.8 | 735.7 | 20.7 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 79.141.172.154 |
| 81.42 | hysteria2 | 266.0 | 575.4 | 21.62 | 0.0 | 10.0 | 14.32 | 19.08 | Au1rxx-base64 | 192.255.128.123 |
| 80.93 | vless | 272.2 | 601.3 | 21.48 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 15.204.97.216 |
| 80.7 | shadowsocks | 242.6 | 626.3 | 22.16 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 156.146.38.170 |
| 80.69 | shadowsocks | 243.2 | 627.1 | 22.15 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 156.146.38.167 |
| 80.05 | vless | 269.5 | 578.6 | 21.54 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 195.123.240.65 |
| 79.87 | vless | 268.5 | 562.8 | 21.56 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 172.233.139.46 |
| 79.66 | vless | 318.8 | 697.7 | 20.4 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 198.251.78.29 |
| 79.53 | vless | 268.8 | 578.4 | 21.56 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 172.235.43.210 |
| 78.26 | hysteria2 | 368.7 | 855.6 | 19.24 | 0.0 | 10.0 | 14.32 | 19.08 | Au1rxx-base64 | 159.223.157.129 |
| 77.34 | shadowsocks | 236.5 | 593.5 | 22.3 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 66.23.201.172 |
| 77.09 | vless | 333.3 | 692.5 | 20.06 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 137.175.82.40 |
| 77.03 | vless | 437.1 | 1061.5 | 17.66 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 51.81.203.63 |
| 76.86 | hysteria2 | 511.7 | 1316.5 | 15.93 | 0.0 | 10.0 | 14.32 | 19.08 | Au1rxx-base64 | 66.94.121.46 |
| 76.32 | vless | 275.8 | 602.1 | 21.39 | 0.0 | 10.0 | 12.38 | 19.08 | Au1rxx-base64 | 15.204.97.214 |
| 75.99 | shadowsocks | 266.9 | 517.4 | 21.6 | 0.0 | 10.0 | 13.46 | 19.1 | mheidari-all | 108.181.118.10 |
| 75.95 | shadowsocks | 275.4 | 588.6 | 21.4 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 108.181.0.177 |
| 75.65 | shadowsocks | 238.5 | 525.1 | 22.26 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 103.214.109.197 |
| 75.51 | shadowsocks | 246.4 | 516.9 | 22.07 | 0.0 | 10.0 | 13.46 | 19.08 | Au1rxx-base64 | 104.192.225.106 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.905 | 253 | 1731 | prefer |
| Surfboard-tg-mixed | 0.803 | 0.733 | 45 | 7165 | prefer |
| ermaozi | 0.717 | 0.708 | 24 | 618 | prefer |
| mheidari-all | 0.431 | 0.35 | 414 | 23308 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5324 | observe |
| Epodonios-all | 0.255 | None | 0 | 7654 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9200 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5778 | observe |
| barry-far-vless | 0.255 | None | 0 | 6015 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 5603 | downweight |
| Au1rxx-clash | 0.244 | None | 0 | 1731 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 161 |
| speed | TimeoutError | - | 67 |
| geo | ClientOSError | - | 26 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 19 |
| speed | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
