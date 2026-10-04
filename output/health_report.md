# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-04 21:15:57 |
| 运行耗时 | 613.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99286 |
| 去重后节点 | 27467 |
| TCP 可达 | 3000 |
| 真实可用 | 498 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27467 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.0 |
| tcp | 47.3 |
| probe | 268.6 |
| real_test | 223.5 |
| generate | 69.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59612 |
| vmess | 15678 |
| shadowsocks | 11499 |
| trojan | 10212 |
| hysteria2 | 1463 |
| http | 522 |
| shadowsocksr | 170 |
| socks | 72 |
| anytls | 27 |
| hysteria | 16 |
| tuic | 15 |

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
| 80.41 | shadowsocks | 241.7 | 601.1 | 22.18 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 156.146.38.170 |
| 79.18 | shadowsocks | 295.1 | 562.0 | 20.95 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 156.146.38.168 |
| 79.11 | vless | 337.4 | 706.1 | 19.97 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 169.40.42.104 |
| 78.8 | shadowsocks | 311.5 | 750.9 | 20.57 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 156.146.38.169 |
| 78.35 | vless | 297.1 | 598.9 | 20.9 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 107.173.237.146 |
| 77.91 | shadowsocks | 301.9 | 749.8 | 20.79 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 37.19.198.243 |
| 77.81 | hysteria2 | 337.0 | 848.2 | 19.98 | 0.0 | 10.0 | 12.63 | 16.7 | mheidari-all | 129.213.91.185 |
| 77.8 | shadowsocks | 304.8 | 753.3 | 20.72 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 37.19.198.160 |
| 77.5 | vless | 320.4 | 718.8 | 20.36 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 195.123.235.177 |
| 77.44 | vless | 334.3 | 752.6 | 20.04 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 66.70.179.198 |
| 77.2 | shadowsocks | 329.2 | 824.1 | 20.16 | 0.0 | 10.0 | 13.03 | 19.2 | Au1rxx-base64 | 37.19.198.236 |
| 76.89 | hysteria2 | 295.8 | 331.0 | 20.93 | 2.59 | 9.2 | 12.63 | 19.2 | Au1rxx-base64 | open.w2m.ink |
| 76.59 | vless | 314.2 | 612.8 | 20.5 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 195.123.240.65 |
| 76.57 | vless | 381.8 | 858.6 | 18.94 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 169.40.42.16 |
| 76.38 | vless | 317.5 | 718.5 | 20.43 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 159.89.87.21 |
| 76.27 | vless | 324.1 | 651.9 | 20.28 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 15.204.97.216 |
| 75.81 | hysteria2 | 303.3 | 675.1 | 20.76 | 0.0 | 10.0 | 12.63 | 19.2 | Au1rxx-base64 | 66.94.121.46 |
| 75.81 | vless | 415.9 | 1003.6 | 18.15 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 2.24.124.64 |
| 75.62 | hysteria2 | 325.2 | 754.6 | 20.25 | 0.0 | 10.0 | 12.63 | 16.7 | mheidari-all | 159.223.157.129 |
| 75.47 | vless | 378.8 | 768.2 | 19.01 | 0.0 | 10.0 | 12.05 | 19.2 | Au1rxx-base64 | 169.40.42.232 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.998 | 0.926 | 367 | 1858 | prefer |
| ermaozi | 0.952 | 0.96 | 25 | 653 | prefer |
| mheidari-all | 0.852 | 0.782 | 55 | 23222 | prefer |
| Surfboard-tg-mixed | 0.804 | 0.728 | 114 | 7257 | prefer |
| Au1rxx-clash | 0.432 | 1.0 | 3 | 1844 | observe |
| ermaozi-get_subscribe | 0.341 | 0.75 | 4 | 518 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 68 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5173 | observe |
| Epodonios-all | 0.255 | None | 0 | 7751 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9655 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5820 | observe |
| barry-far-vless | 0.255 | None | 0 | 6058 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4365 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 7 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
