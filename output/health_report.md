# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 10:06:13 |
| 运行耗时 | 346.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84235 |
| 去重后节点 | 22876 |
| TCP 可达 | 3000 |
| 真实可用 | 837 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22876 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 31.4 |
| probe | 69.9 |
| real_test | 208.3 |
| generate | 29.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46872 |
| trojan | 15553 |
| shadowsocks | 10521 |
| vmess | 10340 |
| hysteria2 | 622 |
| shadowsocksr | 103 |
| socks | 93 |
| http | 84 |
| anytls | 22 |
| hysteria | 13 |
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
| 81.57 | shadowsocks | 238.0 | 661.0 | 22.27 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 37.19.198.160 |
| 81.4 | shadowsocks | 245.4 | 685.8 | 22.1 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 37.19.198.243 |
| 80.34 | shadowsocks | 291.3 | 819.1 | 21.04 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 37.19.198.244 |
| 79.68 | trojan | 400.0 | 1126.1 | 18.52 | 0.0 | 10.0 | 14.42 | 19.74 | Au1rxx-base64 | 153.75.250.171 |
| 79.34 | shadowsocks | 268.8 | 634.3 | 21.55 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 185.196.61.82 |
| 78.79 | trojan | 434.1 | 1095.0 | 17.73 | 0.0 | 10.0 | 14.42 | 19.74 | Au1rxx-base64 | 148.72.168.35 |
| 78.38 | shadowsocks | 284.4 | 655.0 | 21.2 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 156.146.38.167 |
| 78.08 | hysteria2 | 230.4 | 644.8 | 22.44 | 0.0 | 10.0 | 12.0 | 19.74 | Au1rxx-base64 | 159.223.157.129 |
| 77.91 | shadowsocks | 274.7 | 632.5 | 21.42 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 156.146.38.170 |
| 77.05 | shadowsocks | 318.6 | 759.6 | 20.4 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 156.146.38.168 |
| 76.86 | shadowsocks | 225.5 | 624.8 | 22.56 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 37.19.198.236 |
| 76.01 | shadowsocks | 325.4 | 735.4 | 20.24 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 108.181.57.93 |
| 75.81 | shadowsocks | 283.5 | 660.8 | 21.21 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 156.146.38.169 |
| 74.79 | hysteria2 | 356.6 | 685.4 | 19.52 | 0.0 | 10.0 | 12.0 | 19.74 | Au1rxx-base64 | 62.210.124.146 |
| 73.51 | shadowsocks | 311.9 | 607.6 | 20.56 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 173.244.56.6 |
| 72.85 | trojan | 532.3 | 1341.1 | 15.46 | 0.0 | 10.0 | 14.42 | 19.74 | Au1rxx-base64 | 163.245.196.68 |
| 72.81 | shadowsocks | 356.9 | 727.7 | 19.52 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 108.181.0.177 |
| 72.67 | shadowsocks | 344.5 | 656.9 | 19.8 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 72.5 | shadowsocks | 371.9 | 725.6 | 19.17 | 0.0 | 10.0 | 13.56 | 19.74 | Au1rxx-base64 | 108.181.118.10 |
| 72.45 | trojan | 443.2 | 779.1 | 17.52 | 0.0 | 10.0 | 14.42 | 19.74 | Au1rxx-base64 | 79.133.126.237 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.974 | 0.92 | 413 | 1407 | prefer |
| mheidari-all | 0.906 | 0.829 | 234 | 19339 | prefer |
| Surfboard-tg-mixed | 0.552 | 0.472 | 197 | 5483 | observe |
| tg-oneclickvpnkeys | 0.445 | 1.0 | 5 | 132 | observe |
| DeltaKronecker-all | 0.383 | 0.302 | 285 | 5643 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3959 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 174 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6410 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6188 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4173 | observe |
| barry-far-vless | 0.255 | None | 0 | 4692 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5017 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 148 |
| speed | ClientOSError | - | 68 |
| 204 | TimeoutError | - | 39 |
| geo | ClientOSError | - | 33 |
| 204 | ProxyError | - | 27 |
| cn-block | TimeoutError | - | 22 |
| speed | TimeoutError | - | 21 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 7 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
