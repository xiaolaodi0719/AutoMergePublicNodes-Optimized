# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-11 19:12:00 |
| 运行耗时 | 270.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81101 |
| 去重后节点 | 23130 |
| TCP 可达 | 3000 |
| 真实可用 | 570 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23130 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.4 |
| tcp | 35.1 |
| probe | 57.3 |
| real_test | 123.2 |
| generate | 45.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46356 |
| vmess | 13214 |
| trojan | 10272 |
| shadowsocks | 9697 |
| hysteria2 | 1238 |
| http | 159 |
| shadowsocksr | 75 |
| socks | 66 |
| tuic | 14 |
| hysteria | 10 |

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
| 82.67 | hysteria2 | 264.8 | 665.3 | 21.65 | 0.0 | 10.0 | 14.06 | 18.06 | Au1rxx-base64 | 159.223.157.129 |
| 82.63 | hysteria2 | 270.6 | 694.2 | 21.51 | 0.0 | 10.0 | 14.06 | 18.06 | Au1rxx-base64 | 138.124.68.188 |
| 81.46 | http | 291.4 | 693.5 | 21.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |
| 81.26 | http | 301.2 | 706.6 | 20.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 81.23 | http | 299.4 | 713.6 | 20.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 81.19 | http | 301.2 | 719.9 | 20.81 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 81.15 | http | 301.7 | 720.0 | 20.79 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 81.01 | http | 298.6 | 721.8 | 20.87 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.21 |
| 80.65 | http | 287.9 | 697.2 | 21.11 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 79.52 | shadowsocks | 250.6 | 599.1 | 21.98 | 0.0 | 10.0 | 13.48 | 18.06 | Au1rxx-base64 | 156.146.38.168 |
| 79.2 | shadowsocks | 264.2 | 659.7 | 21.66 | 0.0 | 10.0 | 13.48 | 18.06 | Au1rxx-base64 | 37.19.198.236 |
| 79.19 | shadowsocks | 264.8 | 667.5 | 21.65 | 0.0 | 10.0 | 13.48 | 18.06 | Au1rxx-base64 | 37.19.198.160 |
| 78.99 | shadowsocks | 273.5 | 683.6 | 21.45 | 0.0 | 10.0 | 13.48 | 18.06 | Au1rxx-base64 | 37.19.198.244 |
| 78.9 | hysteria2 | 270.8 | 693.6 | 21.51 | 0.0 | 6.27 | 14.06 | 18.06 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 78.23 | shadowsocks | 293.9 | 731.2 | 20.97 | 0.0 | 10.0 | 13.48 | 18.06 | Au1rxx-base64 | 156.146.38.170 |
| 77.48 | trojan | 317.9 | 760.0 | 20.42 | 0.0 | 10.0 | 14.51 | 18.06 | Au1rxx-base64 | 64.94.95.118 |
| 77.27 | http | 310.6 | 748.9 | 20.59 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.39 |
| 77.02 | http | 303.8 | 726.8 | 20.75 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.4 |
| 76.8 | http | 292.9 | 707.3 | 21.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.28 |
| 76.69 | http | 285.9 | 680.4 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.947 | 0.889 | 370 | 1503 | prefer |
| Surfboard-tg-mixed | 0.794 | 0.718 | 103 | 6169 | prefer |
| mheidari-all | 0.74 | 0.667 | 51 | 16649 | prefer |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 5522 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5419 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 6745 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7634 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5045 | observe |
| barry-far-vless | 0.255 | None | 0 | 5313 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1503 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 13 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| geo | TimeoutError | - | 8 |
| geo | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
