# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 21:11:58 |
| 运行耗时 | 408.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 88556 |
| 去重后节点 | 25499 |
| TCP 可达 | 3000 |
| 真实可用 | 371 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25499 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.4 |
| tcp | 42.3 |
| probe | 161.4 |
| real_test | 158.3 |
| generate | 36.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53114 |
| vmess | 14216 |
| shadowsocks | 10577 |
| trojan | 8474 |
| hysteria2 | 1318 |
| http | 584 |
| shadowsocksr | 165 |
| socks | 77 |
| hysteria | 14 |
| anytls | 11 |
| tuic | 6 |

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
| 82.69 | hysteria2 | 257.5 | 691.1 | 21.82 | 0.0 | 10.0 | 13.33 | 18.64 | Au1rxx-base64 | 159.223.157.129 |
| 80.66 | vless | 246.5 | 708.3 | 22.07 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 79.141.172.154 |
| 80.15 | shadowsocks | 258.3 | 711.1 | 21.8 | 0.0 | 10.0 | 13.71 | 18.64 | Au1rxx-base64 | 37.19.198.243 |
| 79.59 | vless | 292.6 | 728.5 | 21.0 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 66.70.179.198 |
| 79.4 | vless | 281.1 | 654.9 | 21.27 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 138.124.60.146 |
| 79.18 | shadowsocks | 300.0 | 837.3 | 20.83 | 0.0 | 10.0 | 13.71 | 18.64 | Au1rxx-base64 | 37.19.198.236 |
| 79.04 | shadowsocks | 306.3 | 848.1 | 20.69 | 0.0 | 10.0 | 13.71 | 18.64 | Au1rxx-base64 | 37.19.198.244 |
| 79.0 | vless | 318.2 | 875.1 | 20.41 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 137.184.218.169 |
| 78.86 | vless | 281.0 | 691.1 | 21.27 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.168 |
| 78.86 | vless | 324.5 | 754.5 | 20.27 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.89 |
| 78.7 | vless | 331.5 | 657.5 | 20.11 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.225 |
| 78.42 | vless | 343.2 | 860.3 | 19.83 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.223 |
| 78.24 | vless | 351.3 | 908.8 | 19.65 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.173 |
| 78.22 | vless | 351.9 | 971.6 | 19.63 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 185.95.231.156 |
| 78.14 | vless | 355.6 | 950.7 | 19.55 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.202 |
| 78.07 | vless | 289.2 | 771.9 | 21.08 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.52 |
| 77.95 | vless | 363.8 | 1046.8 | 19.36 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 34.85.179.6 |
| 77.84 | vless | 289.9 | 711.2 | 21.07 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.90 |
| 77.7 | vless | 374.7 | 732.0 | 19.11 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.212 |
| 77.54 | vless | 381.3 | 992.7 | 18.95 | 0.0 | 10.0 | 9.95 | 18.64 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.877 | 0.81 | 305 | 1718 | prefer |
| mheidari-all | 0.833 | 0.759 | 83 | 15951 | prefer |
| DeltaKronecker-all | 0.774 | 0.702 | 47 | 6324 | prefer |
| ermaozi | 0.653 | 0.8 | 15 | 325 | observe |
| Surfboard-tg-mixed | 0.515 | 0.636 | 11 | 7279 | observe |
| xiaoji235-airport-v2ray-all | 0.441 | 0.462 | 13 | 4242 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 116 | observe |
| Epodonios-all | 0.255 | None | 0 | 7749 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9217 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5930 | observe |
| barry-far-vless | 0.255 | None | 0 | 5928 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4252 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1718 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 40 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 15 |
| geo | TimeoutError | - | 13 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
