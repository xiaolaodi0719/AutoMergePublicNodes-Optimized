# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 14:24:10 |
| 运行耗时 | 236.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87256 |
| 去重后节点 | 24192 |
| TCP 可达 | 3000 |
| 真实可用 | 512 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24192 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 0.8 |
| tcp | 36.9 |
| probe | 49.0 |
| real_test | 111.5 |
| generate | 31.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51747 |
| vmess | 13101 |
| trojan | 10691 |
| shadowsocks | 10142 |
| hysteria2 | 1340 |
| socks | 74 |
| shadowsocksr | 68 |
| http | 39 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 14 |

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
| 81.28 | hysteria2 | 236.8 | 639.3 | 22.3 | 0.0 | 8.56 | 12.14 | 19.38 | Au1rxx-base64 | 159.223.157.129 |
| 81.02 | hysteria2 | 251.6 | 687.7 | 21.95 | 0.0 | 8.55 | 12.14 | 19.38 | Au1rxx-base64 | 138.124.68.188 |
| 80.84 | hysteria2 | 246.2 | 672.1 | 22.08 | 0.0 | 8.24 | 12.14 | 19.38 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 80.38 | vless | 255.8 | 687.8 | 21.86 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 47.253.226.114 |
| 78.98 | vless | 265.3 | 617.3 | 21.64 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 216.227.161.95 |
| 78.26 | shadowsocks | 279.1 | 761.8 | 21.32 | 0.0 | 8.62 | 12.94 | 19.38 | Au1rxx-base64 | 37.19.198.244 |
| 78.23 | vless | 326.7 | 797.8 | 20.22 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 158.69.112.254 |
| 78.23 | vless | 348.3 | 859.0 | 19.71 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 169.40.42.15 |
| 78.11 | shadowsocks | 285.7 | 779.3 | 21.17 | 0.0 | 8.62 | 12.94 | 19.38 | Au1rxx-base64 | 37.19.198.160 |
| 77.08 | shadowsocks | 243.7 | 648.2 | 22.14 | 0.0 | 8.62 | 12.94 | 19.38 | Au1rxx-base64 | 37.19.198.236 |
| 76.09 | vless | 311.6 | 830.9 | 20.57 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 159.89.87.21 |
| 75.9 | shadowsocks | 278.3 | 644.9 | 21.34 | 0.0 | 8.61 | 12.94 | 19.38 | Au1rxx-base64 | 156.146.38.168 |
| 75.74 | vless | 261.6 | 659.4 | 21.72 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 172.64.144.82 |
| 75.31 | vless | 280.3 | 711.1 | 21.29 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 172.64.145.202 |
| 75.24 | vless | 261.7 | 661.5 | 21.72 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 167.17.69.171 |
| 74.68 | shadowsocks | 287.5 | 663.5 | 21.12 | 0.0 | 8.61 | 12.94 | 19.38 | Au1rxx-base64 | 156.146.38.169 |
| 74.62 | vless | 310.3 | 826.3 | 20.6 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 104.16.72.41 |
| 74.46 | shadowsocks | 282.8 | 646.4 | 21.23 | 0.0 | 8.61 | 12.94 | 19.38 | Au1rxx-base64 | 156.146.38.167 |
| 74.18 | vless | 329.0 | 868.2 | 20.16 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 104.16.148.244 |
| 74.15 | vless | 330.6 | 891.6 | 20.13 | 0.0 | 10.0 | 9.14 | 19.38 | Au1rxx-base64 | 104.18.185.26 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | 0.931 | 418 | 1552 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.683 | 0.604 | 144 | 5862 | observe |
| mheidari-all | 0.542 | 0.458 | 24 | 20132 | observe |
| DeltaKronecker-all | 0.326 | 0.267 | 15 | 5316 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 4655 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6386 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7443 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4686 | observe |
| barry-far-vless | 0.255 | None | 0 | 4943 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5147 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1594 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 37 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 14 |
| geo | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 10 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
