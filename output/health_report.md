# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 07:27:45 |
| 运行耗时 | 231.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 89705 |
| 去重后节点 | 24235 |
| TCP 可达 | 3000 |
| 真实可用 | 482 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24235 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.2 |
| tcp | 35.8 |
| probe | 50.3 |
| real_test | 94.3 |
| generate | 44.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52575 |
| vmess | 13487 |
| trojan | 11381 |
| shadowsocks | 10453 |
| hysteria2 | 1533 |
| socks | 106 |
| shadowsocksr | 72 |
| http | 35 |
| anytls | 30 |
| hysteria | 21 |
| tuic | 12 |

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
| 83.1 | hysteria2 | 270.6 | 691.7 | 21.51 | 0.0 | 10.0 | 12.95 | 19.74 | Au1rxx-base64 | 159.223.157.129 |
| 83.07 | hysteria2 | 276.4 | 723.1 | 21.38 | 0.0 | 10.0 | 12.95 | 19.74 | Au1rxx-base64 | 138.124.68.188 |
| 81.61 | hysteria2 | 274.9 | 712.5 | 21.41 | 0.0 | 8.51 | 12.95 | 19.74 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.35 | shadowsocks | 250.7 | 609.6 | 21.98 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 156.146.38.170 |
| 81.0 | shadowsocks | 265.6 | 678.8 | 21.63 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 37.19.198.244 |
| 80.92 | shadowsocks | 268.9 | 685.3 | 21.55 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 37.19.198.160 |
| 80.82 | trojan | 300.5 | 740.2 | 20.82 | 0.0 | 10.0 | 13.26 | 19.74 | Au1rxx-base64 | 153.75.250.171 |
| 80.78 | shadowsocks | 259.0 | 633.6 | 21.78 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 80.08 | shadowsocks | 283.9 | 721.7 | 21.21 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 68.168.222.210 |
| 79.58 | shadowsocks | 253.3 | 620.8 | 21.91 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 156.146.38.167 |
| 78.84 | trojan | 284.8 | 641.5 | 21.19 | 0.0 | 10.0 | 13.26 | 19.74 | Au1rxx-base64 | 163.245.196.68 |
| 77.89 | shadowsocks | 270.5 | 693.2 | 21.52 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 37.19.198.243 |
| 76.18 | shadowsocks | 302.3 | 639.4 | 20.78 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 75.61 | shadowsocks | 294.4 | 586.1 | 20.96 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 75.59 | http | 329.7 | 579.2 | 20.14 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 75.49 | trojan | 496.2 | 1295.4 | 16.29 | 0.0 | 10.0 | 13.26 | 19.74 | Au1rxx-base64 | 64.94.95.117 |
| 75.36 | shadowsocks | 302.8 | 566.1 | 20.77 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 173.244.56.9 |
| 75.36 | http | 329.5 | 584.0 | 20.15 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 75.33 | shadowsocks | 329.5 | 725.9 | 20.15 | 0.0 | 10.0 | 13.63 | 19.74 | Au1rxx-base64 | 108.181.57.93 |
| 74.9 | trojan | 528.2 | 1399.7 | 15.55 | 0.0 | 10.0 | 13.26 | 19.74 | Au1rxx-base64 | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | 0.936 | 389 | 1300 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.623 | 0.545 | 33 | 20715 | observe |
| DeltaKronecker-all | 0.613 | 0.536 | 28 | 5326 | observe |
| Surfboard-tg-mixed | 0.572 | 0.492 | 128 | 6241 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1772 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5184 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5282 | observe |
| Epodonios-all | 0.255 | None | 0 | 6873 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7440 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4967 | observe |
| barry-far-vless | 0.255 | None | 0 | 5297 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5247 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 40 |
| geo | ClientOSError | - | 25 |
| 204 | TimeoutError | - | 19 |
| speed | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyError | - | 8 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
