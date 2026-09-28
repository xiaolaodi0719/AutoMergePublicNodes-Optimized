# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 04:58:24 |
| 运行耗时 | 976.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95255 |
| 去重后节点 | 26807 |
| TCP 可达 | 3000 |
| 真实可用 | 535 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26807 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.6 |
| tcp | 44.0 |
| probe | 343.9 |
| real_test | 492.4 |
| generate | 88.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57656 |
| vmess | 14873 |
| shadowsocks | 11469 |
| trojan | 8887 |
| hysteria2 | 1450 |
| http | 621 |
| shadowsocksr | 176 |
| socks | 76 |
| anytls | 24 |
| hysteria | 15 |
| tuic | 8 |

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
| 82.79 | vless | 233.2 | 621.2 | 22.38 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 195.123.235.177 |
| 82.61 | vless | 240.8 | 690.5 | 22.2 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 79.141.172.154 |
| 82.54 | vless | 244.0 | 684.8 | 22.13 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 47.253.144.114 |
| 82.5 | vless | 245.9 | 672.2 | 22.09 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 137.184.218.169 |
| 82.1 | vless | 263.2 | 669.3 | 21.69 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.229 |
| 81.96 | vless | 269.2 | 728.6 | 21.55 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 185.95.231.233 |
| 81.75 | vless | 278.0 | 687.4 | 21.34 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.232 |
| 81.69 | vless | 280.8 | 694.0 | 21.28 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.104 |
| 81.67 | vless | 281.5 | 693.5 | 21.26 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.35 |
| 81.49 | vless | 289.5 | 740.0 | 21.08 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 66.70.179.198 |
| 81.17 | vless | 303.3 | 689.8 | 20.76 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.179 |
| 81.15 | vless | 303.9 | 760.3 | 20.74 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 158.69.112.254 |
| 81.03 | vless | 292.7 | 696.3 | 21.0 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 130.107.73.148 |
| 80.59 | vless | 328.4 | 755.9 | 20.18 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.163 |
| 80.45 | vless | 309.5 | 839.0 | 20.61 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.75 |
| 80.3 | vless | 339.7 | 837.8 | 19.91 | 0.0 | 10.0 | 11.93 | 19.3 | mheidari-all | 5.34.178.120 |
| 80.05 | vless | 267.5 | 648.9 | 21.59 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.89 |
| 80.03 | vless | 302.9 | 697.1 | 20.77 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 198.251.78.29 |
| 79.94 | vless | 260.9 | 683.8 | 21.74 | 0.0 | 10.0 | 11.93 | 18.48 | Au1rxx-base64 | 169.40.42.184 |
| 79.91 | shadowsocks | 250.5 | 702.1 | 21.98 | 0.0 | 10.0 | 13.45 | 18.48 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | 0.847 | 321 | 1437 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.671 | 76 | 6916 | prefer |
| ermaozi | 0.735 | 0.732 | 41 | 347 | prefer |
| mheidari-all | 0.409 | 0.328 | 533 | 22305 | observe |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 5466 | observe |
| tg-oneclickvpnkeys | 0.313 | 1.0 | 2 | 51 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7506 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9195 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5591 | observe |
| barry-far-vless | 0.255 | None | 0 | 5817 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4185 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 187 |
| speed | TimeoutError | - | 83 |
| geo | ClientOSError | - | 52 |
| speed | ClientOSError | - | 45 |
| 204 | ProxyError | - | 33 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
