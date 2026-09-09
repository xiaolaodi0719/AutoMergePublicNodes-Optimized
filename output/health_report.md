# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 16:29:16 |
| 运行耗时 | 663.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84876 |
| 去重后节点 | 22035 |
| TCP 可达 | 3000 |
| 真实可用 | 496 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22035 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 37.2 |
| probe | 265.0 |
| real_test | 270.4 |
| generate | 83.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51926 |
| vmess | 12415 |
| shadowsocks | 9945 |
| trojan | 7995 |
| hysteria2 | 1831 |
| http | 560 |
| shadowsocksr | 133 |
| socks | 52 |
| hysteria | 9 |
| tuic | 8 |
| anytls | 2 |

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
| 80.88 | vless | 332.3 | 874.9 | 20.09 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 216.152.147.28 |
| 80.86 | vless | 298.8 | 706.9 | 20.86 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.229 |
| 80.25 | vless | 273.3 | 630.6 | 21.45 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 195.123.235.177 |
| 80.04 | vless | 296.8 | 656.5 | 20.91 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.16 |
| 80.0 | shadowsocks | 261.0 | 635.9 | 21.74 | 0.0 | 10.0 | 13.02 | 19.24 | Au1rxx-base64 | 156.146.38.169 |
| 79.71 | hysteria2 | 264.6 | 563.0 | 21.65 | 0.0 | 10.0 | 12.63 | 19.24 | Au1rxx-base64 | 66.94.121.46 |
| 79.39 | vless | 319.3 | 712.5 | 20.39 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.224 |
| 79.31 | vless | 312.0 | 771.2 | 20.56 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 47.253.226.114 |
| 79.22 | vless | 362.0 | 898.3 | 19.4 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 185.95.231.156 |
| 78.93 | vless | 377.6 | 945.2 | 19.04 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.168 |
| 78.8 | vless | 350.8 | 832.0 | 19.66 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 66.70.179.198 |
| 78.76 | vless | 375.8 | 893.7 | 19.08 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.202 |
| 78.46 | vless | 328.8 | 686.5 | 20.17 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.173 |
| 78.38 | vless | 414.6 | 1005.5 | 18.18 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.89 |
| 78.27 | vless | 329.0 | 745.1 | 20.16 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.52 |
| 78.04 | vless | 362.7 | 907.8 | 19.38 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.212 |
| 78.02 | vless | 409.3 | 986.8 | 18.3 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.235 |
| 77.62 | vless | 424.7 | 979.9 | 17.95 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 169.40.42.231 |
| 77.57 | hysteria2 | 283.6 | 670.5 | 21.21 | 0.0 | 10.0 | 12.63 | 15.9 | Surfboard-tg-mixed | 159.223.157.129 |
| 77.54 | vless | 375.7 | 868.8 | 19.08 | 0.0 | 10.0 | 11.55 | 19.24 | Au1rxx-base64 | 137.184.218.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | 0.916 | 273 | 1634 | prefer |
| DeltaKronecker-all | 0.822 | 0.75 | 60 | 5187 | prefer |
| Surfboard-tg-mixed | 0.796 | 0.719 | 146 | 7428 | prefer |
| ermaozi | 0.731 | 0.731 | 26 | 410 | prefer |
| mheidari-all | 0.692 | 0.613 | 119 | 16618 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 205 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7926 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9327 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6118 | observe |
| barry-far-vless | 0.255 | None | 0 | 6336 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1634 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 46 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 10 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 3 |
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
