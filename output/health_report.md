# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 05:31:25 |
| 运行耗时 | 892.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97105 |
| 去重后节点 | 27062 |
| TCP 可达 | 3000 |
| 真实可用 | 478 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27062 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.6 |
| probe | 324.1 |
| real_test | 437.1 |
| generate | 75.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56742 |
| vmess | 15986 |
| shadowsocks | 11622 |
| trojan | 10242 |
| hysteria2 | 1486 |
| http | 698 |
| shadowsocksr | 166 |
| socks | 105 |
| anytls | 30 |
| hysteria | 17 |
| tuic | 11 |

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
| 82.86 | vless | 241.7 | 534.8 | 22.18 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 47.251.108.158 |
| 82.54 | vless | 261.6 | 626.3 | 21.72 | 0.0 | 10.0 | 12.43 | 20.0 | mheidari-all | 216.227.161.95 |
| 82.5 | shadowsocks | 243.4 | 613.4 | 22.14 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 82.37 | shadowsocks | 249.0 | 615.4 | 22.01 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.37 | shadowsocks | 249.0 | 606.4 | 22.01 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.87 | hysteria2 | 309.7 | 735.1 | 20.61 | 0.0 | 10.0 | 14.25 | 20.0 | Au1rxx-base64 | 129.213.91.185 |
| 81.39 | shadowsocks | 291.7 | 773.5 | 21.03 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.81 | vless | 272.9 | 580.4 | 21.46 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 107.173.237.146 |
| 80.8 | vless | 273.7 | 585.1 | 21.44 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 79.99 | hysteria2 | 352.5 | 793.4 | 19.62 | 0.0 | 10.0 | 14.25 | 20.0 | mheidari-all | 159.223.157.129 |
| 79.52 | hysteria2 | 273.1 | 302.9 | 21.46 | 3.64 | 7.61 | 14.25 | 20.0 | Au1rxx-base64 | open.w2m.ink |
| 79.22 | hysteria2 | 253.1 | 251.7 | 21.92 | 5.56 | 9.74 | 14.25 | 20.0 | Au1rxx-base64 | 45.32.10.7 |
| 79.15 | shadowsocks | 299.7 | 697.9 | 20.84 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 5.78.51.123 |
| 79.08 | vless | 338.5 | 711.4 | 19.94 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 79.06 | vless | 295.7 | 670.4 | 20.93 | 0.0 | 10.0 | 12.43 | 20.0 | mheidari-all | 195.211.98.43 |
| 78.76 | vless | 284.9 | 616.4 | 21.18 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 78.37 | vless | 259.0 | 551.1 | 21.78 | 0.0 | 10.0 | 12.43 | 20.0 | Au1rxx-base64 | 154.17.1.248 |
| 77.13 | shadowsocks | 298.8 | 653.3 | 20.86 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 77.11 | trojan | 298.9 | 620.5 | 20.86 | 0.0 | 8.6 | 14.2 | 20.0 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 77.1 | shadowsocks | 304.8 | 588.5 | 20.72 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.897 | 300 | 1797 | prefer |
| Surfboard-tg-mixed | 0.765 | 0.69 | 71 | 7006 | prefer |
| ermaozi | 0.529 | 0.5 | 48 | 726 | observe |
| mheidari-all | 0.432 | 0.351 | 379 | 22990 | observe |
| DeltaKronecker-all | 0.305 | 0.3 | 10 | 4889 | observe |
| Epodonios-all | 0.255 | None | 0 | 7476 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9204 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5583 | observe |
| barry-far-vless | 0.255 | None | 0 | 5829 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4373 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1797 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 151 |
| speed | TimeoutError | - | 60 |
| geo | ClientOSError | - | 30 |
| 204 | TimeoutError | - | 24 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyConnectionError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
