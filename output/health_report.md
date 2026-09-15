# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 11:38:30 |
| 运行耗时 | 717.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90261 |
| 去重后节点 | 25576 |
| TCP 可达 | 3000 |
| 真实可用 | 434 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25576 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 41.6 |
| probe | 349.3 |
| real_test | 238.3 |
| generate | 79.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55603 |
| vmess | 13054 |
| shadowsocks | 10071 |
| trojan | 8804 |
| hysteria2 | 1849 |
| http | 667 |
| shadowsocksr | 128 |
| socks | 56 |
| hysteria | 14 |
| anytls | 8 |
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
| 75.76 | shadowsocks | 290.3 | 803.0 | 21.06 | 0.0 | 10.0 | 14.04 | 15.16 | Surfboard-tg-mixed | 38.180.135.156 |
| 74.77 | vless | 230.7 | 605.4 | 22.44 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 195.123.235.177 |
| 74.44 | vless | 244.6 | 632.2 | 22.11 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 137.184.218.169 |
| 74.3 | vless | 251.0 | 654.9 | 21.97 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.182 |
| 74.15 | shadowsocks | 318.6 | 725.6 | 20.4 | 0.0 | 10.0 | 14.04 | 17.32 | Au1rxx-base64 | 108.181.57.93 |
| 74.1 | vless | 245.0 | 642.4 | 22.11 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.35 |
| 73.91 | shadowsocks | 463.6 | 1223.0 | 17.05 | 0.0 | 10.0 | 14.04 | 17.32 | Au1rxx-base64 | 51.222.200.165 |
| 73.84 | vless | 270.8 | 648.5 | 21.51 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.16 |
| 73.76 | vless | 274.4 | 679.9 | 21.43 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.133 |
| 73.75 | shadowsocks | 280.0 | 640.8 | 21.3 | 0.0 | 10.0 | 14.04 | 15.16 | Surfboard-tg-mixed | 156.146.38.167 |
| 73.73 | vless | 275.4 | 611.6 | 21.4 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.235 |
| 73.64 | hysteria2 | 363.4 | 691.1 | 19.37 | 0.0 | 10.0 | 14.03 | 17.32 | Au1rxx-base64 | 62.210.124.146 |
| 73.32 | vless | 293.0 | 717.1 | 20.99 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.173 |
| 73.14 | hysteria2 | 406.4 | 836.0 | 18.37 | 0.0 | 10.0 | 14.03 | 17.32 | Au1rxx-base64 | 5.129.235.85 |
| 73.05 | vless | 288.1 | 771.4 | 21.11 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.231 |
| 72.99 | vless | 307.3 | 793.7 | 20.66 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 66.70.179.198 |
| 72.96 | vless | 308.8 | 702.8 | 20.63 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.89 |
| 72.68 | hysteria2 | 400.8 | 872.1 | 18.5 | 0.0 | 10.0 | 14.03 | 17.32 | Au1rxx-base64 | 107.175.219.48 |
| 72.55 | vless | 326.4 | 903.1 | 20.22 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 185.95.231.156 |
| 72.35 | vless | 334.9 | 858.0 | 20.02 | 0.0 | 10.0 | 5.01 | 17.32 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | 0.869 | 320 | 1440 | prefer |
| mheidari-all | 0.742 | 0.667 | 75 | 21594 | prefer |
| Surfboard-tg-mixed | 0.696 | 0.618 | 110 | 7608 | observe |
| ermaozi | 0.647 | 0.635 | 52 | 425 | observe |
| DeltaKronecker-all | 0.382 | 0.357 | 14 | 5932 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| Epodonios-all | 0.255 | None | 0 | 8009 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8760 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6177 | observe |
| barry-far-vless | 0.255 | None | 0 | 6343 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4258 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.233 | None | 0 | 1440 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| geo | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 19 |
| cn-block | ClientOSError | - | 16 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 10 |
| geo | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
