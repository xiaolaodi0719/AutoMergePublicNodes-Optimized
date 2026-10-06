# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-06 00:02:04 |
| 运行耗时 | 445.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98529 |
| 去重后节点 | 27355 |
| TCP 可达 | 3000 |
| 真实可用 | 409 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27355 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| geo | 1.5 |
| tcp | 45.9 |
| probe | 200.2 |
| real_test | 158.8 |
| generate | 31.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58675 |
| vmess | 15715 |
| shadowsocks | 11618 |
| trojan | 10166 |
| hysteria2 | 1396 |
| http | 635 |
| shadowsocksr | 169 |
| socks | 92 |
| anytls | 27 |
| tuic | 19 |
| hysteria | 17 |

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
| 85.53 | hysteria2 | 222.2 | 567.2 | 22.63 | 0.0 | 10.0 | 14.32 | 19.58 | Au1rxx-base64 | 66.94.121.46 |
| 85.46 | hysteria2 | 222.6 | 227.8 | 22.63 | 6.46 | 9.3 | 14.32 | 19.58 | Au1rxx-base64 | open.w2m.ink |
| 83.87 | vless | 223.4 | 547.4 | 22.61 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 15.204.97.216 |
| 82.62 | hysteria2 | 229.0 | 235.6 | 22.48 | 6.16 | 9.94 | 14.32 | 19.58 | Au1rxx-base64 | 132.226.14.77 |
| 81.77 | trojan | 246.3 | 572.2 | 22.08 | 0.0 | 10.0 | 12.61 | 19.58 | Au1rxx-base64 | 44.255.123.205 |
| 81.63 | trojan | 242.2 | 558.3 | 22.17 | 0.0 | 9.77 | 12.61 | 19.58 | Au1rxx-base64 | happy-gibbon.rooster465.autos |
| 81.49 | shadowsocks | 248.5 | 610.1 | 22.03 | 0.0 | 10.0 | 13.88 | 19.58 | Au1rxx-base64 | 149.22.95.183 |
| 81.31 | shadowsocks | 235.5 | 560.1 | 22.33 | 0.0 | 10.0 | 13.88 | 19.1 | mheidari-all | 173.244.56.6 |
| 80.81 | shadowsocks | 239.1 | 566.2 | 22.24 | 0.0 | 10.0 | 13.88 | 19.1 | mheidari-all | 173.244.56.9 |
| 80.75 | vless | 358.2 | 933.0 | 19.49 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 51.81.203.63 |
| 79.71 | vless | 219.4 | 515.9 | 22.7 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 104.18.39.218 |
| 78.57 | vless | 257.9 | 636.0 | 21.81 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 104.18.46.46 |
| 78.37 | trojan | 303.0 | 725.8 | 20.76 | 0.0 | 8.92 | 12.61 | 19.58 | Au1rxx-base64 | ultimate-jaguar.rooster465.autos |
| 77.48 | trojan | 301.7 | 740.5 | 20.79 | 0.0 | 10.0 | 12.61 | 19.58 | Au1rxx-base64 | 34.220.15.24 |
| 77.44 | shadowsocks | 186.3 | 481.9 | 23.46 | 0.0 | 10.0 | 13.88 | 19.1 | mheidari-all | 216.105.168.18 |
| 76.96 | vless | 311.7 | 789.5 | 20.56 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 45.159.79.71 |
| 76.69 | vless | 325.9 | 328.6 | 20.23 | 2.68 | 9.94 | 11.68 | 19.58 | Au1rxx-base64 | 154.31.114.248 |
| 76.39 | hysteria2 | 375.9 | 772.2 | 19.08 | 0.0 | 10.0 | 14.32 | 19.1 | mheidari-all | 159.223.157.129 |
| 76.16 | vless | 340.2 | 939.3 | 19.9 | 0.0 | 10.0 | 11.68 | 19.58 | Au1rxx-base64 | 66.42.97.171 |
| 76.1 | shadowsocks | 288.4 | 655.1 | 21.1 | 0.0 | 10.0 | 13.88 | 19.58 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.929 | 295 | 1862 | prefer |
| mheidari-all | 0.91 | 0.837 | 104 | 23213 | prefer |
| ermaozi | 0.635 | 0.61 | 59 | 701 | observe |
| DeltaKronecker-all | 0.529 | 0.857 | 7 | 5300 | observe |
| Surfboard-tg-mixed | 0.4 | 0.75 | 4 | 7145 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5111 | observe |
| Epodonios-all | 0.255 | None | 0 | 7624 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9352 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5642 | observe |
| barry-far-vless | 0.255 | None | 0 | 5871 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4375 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 26 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 7 |
| geo | ClientOSError | - | 6 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
