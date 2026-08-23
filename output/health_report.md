# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 01:47:06 |
| 运行耗时 | 310.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 83081 |
| 去重后节点 | 23824 |
| TCP 可达 | 3000 |
| 真实可用 | 858 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23824 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.3 |
| tcp | 40.3 |
| probe | 60.7 |
| real_test | 168.7 |
| generate | 31.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49774 |
| trojan | 10633 |
| shadowsocks | 10372 |
| vmess | 10337 |
| hysteria2 | 1479 |
| shadowsocksr | 174 |
| http | 167 |
| socks | 115 |
| anytls | 16 |
| hysteria | 11 |
| tuic | 3 |

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
| 82.98 | vless | 257.9 | 679.4 | 21.81 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.229 |
| 82.73 | vless | 268.7 | 697.1 | 21.56 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.104 |
| 82.47 | vless | 280.0 | 624.2 | 21.3 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.184 |
| 82.46 | vless | 280.2 | 745.2 | 21.29 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.225 |
| 81.97 | vless | 295.3 | 721.7 | 20.94 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 158.69.112.254 |
| 81.96 | vless | 301.9 | 835.4 | 20.79 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 137.184.218.169 |
| 81.66 | shadowsocks | 242.4 | 670.5 | 22.17 | 0.0 | 10.0 | 13.73 | 19.76 | Au1rxx-base64 | 37.19.198.244 |
| 81.55 | vless | 319.7 | 856.9 | 20.38 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.133 |
| 81.18 | vless | 278.3 | 611.7 | 21.34 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.232 |
| 81.17 | vless | 276.4 | 674.2 | 21.38 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.212 |
| 81.02 | vless | 295.8 | 670.7 | 20.93 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 198.251.78.29 |
| 80.67 | vless | 357.7 | 858.2 | 19.5 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.202 |
| 80.55 | vless | 362.7 | 985.8 | 19.38 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.15 |
| 80.53 | vless | 363.7 | 941.2 | 19.36 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.179 |
| 80.47 | vless | 366.2 | 882.1 | 19.3 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.89 |
| 80.35 | vless | 323.0 | 865.0 | 20.3 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.16 |
| 80.33 | vless | 329.5 | 904.7 | 20.15 | 0.0 | 9.01 | 11.41 | 19.76 | Au1rxx-base64 | 79.127.243.217 |
| 80.28 | shadowsocks | 302.0 | 811.5 | 20.79 | 0.0 | 10.0 | 13.73 | 19.76 | Au1rxx-base64 | 142.4.216.225 |
| 80.09 | vless | 382.7 | 988.4 | 18.92 | 0.0 | 10.0 | 11.41 | 19.76 | Au1rxx-base64 | 169.40.42.74 |
| 80.0 | hysteria2 | 321.2 | 882.7 | 20.34 | 0.0 | 10.0 | 13.7 | 17.06 | mheidari-all | 159.223.157.129 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.936 | 516 | 1658 | prefer |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.888 | 0.811 | 180 | 6297 | prefer |
| mheidari-all | 0.613 | 0.533 | 165 | 14498 | observe |
| xiaoji235-airport-v2ray-all | 0.43 | 0.342 | 38 | 5974 | observe |
| nscl5-all | 0.355 | 1.0 | 2 | 1082 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 146 | observe |
| Epodonios-all | 0.255 | None | 0 | 6920 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7010 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5114 | observe |
| barry-far-vless | 0.255 | None | 0 | 5496 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |
| DeltaKronecker-all | 0.249 | 0.159 | 69 | 5015 | downweight |
| Au1rxx-clash | 0.241 | None | 0 | 1660 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 74 |
| speed | TimeoutError | - | 54 |
| geo | ClientOSError | - | 45 |
| cn-block | TimeoutError | - | 19 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
