# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 19:07:13 |
| 运行耗时 | 218.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82709 |
| 去重后节点 | 23525 |
| TCP 可达 | 3000 |
| 真实可用 | 408 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23525 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 34.9 |
| probe | 52.7 |
| real_test | 92.6 |
| generate | 32.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47553 |
| vmess | 12853 |
| trojan | 11073 |
| shadowsocks | 9754 |
| hysteria2 | 1278 |
| shadowsocksr | 75 |
| socks | 65 |
| http | 35 |
| hysteria | 13 |
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
| 84.42 | hysteria2 | 281.9 | 737.1 | 21.25 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 83.48 | hysteria2 | 274.8 | 710.3 | 21.42 | 0.0 | 8.89 | 14.17 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.65 | hysteria2 | 272.0 | 665.6 | 21.48 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 80.86 | shadowsocks | 255.6 | 621.0 | 21.86 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.45 | shadowsocks | 259.4 | 631.8 | 21.77 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 80.25 | trojan | 324.9 | 790.6 | 20.26 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 79.91 | shadowsocks | 321.0 | 836.3 | 20.35 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.77 | shadowsocks | 327.0 | 848.6 | 20.21 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.61 | shadowsocks | 253.7 | 617.0 | 21.9 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 79.06 | trojan | 359.5 | 888.0 | 19.46 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 64.94.95.117 |
| 78.86 | trojan | 374.5 | 935.7 | 19.11 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 78.65 | trojan | 360.1 | 897.9 | 19.44 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 78.57 | trojan | 399.6 | 1017.2 | 18.53 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 78.56 | shadowsocks | 292.6 | 741.8 | 21.0 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 77.92 | shadowsocks | 276.8 | 699.9 | 21.37 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 76.93 | shadowsocks | 276.3 | 565.9 | 21.38 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.26 | trojan | 326.6 | 577.8 | 20.22 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 76.15 | trojan | 325.6 | 576.1 | 20.24 | 0.0 | 10.0 | 14.41 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 76.09 | shadowsocks | 269.7 | 600.2 | 21.53 | 0.0 | 10.0 | 13.56 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 75.56 | http | 313.9 | 598.7 | 20.51 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | 0.903 | 362 | 1543 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| mheidari-all | 0.738 | 0.662 | 71 | 17684 | prefer |
| Surfboard-tg-mixed | 0.441 | 0.462 | 13 | 6368 | observe |
| DeltaKronecker-all | 0.432 | 0.429 | 14 | 5326 | observe |
| Epodonios-all | 0.287 | 0.5 | 2 | 7096 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5282 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7593 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5103 | observe |
| barry-far-vless | 0.255 | None | 0 | 5504 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5175 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1543 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 8 |
| geo | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
