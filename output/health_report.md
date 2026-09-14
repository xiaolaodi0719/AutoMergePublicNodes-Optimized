# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-14 12:29:33 |
| 运行耗时 | 591.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84799 |
| 去重后节点 | 23007 |
| TCP 可达 | 3000 |
| 真实可用 | 451 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23007 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 37.6 |
| probe | 249.0 |
| real_test | 219.9 |
| generate | 77.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51960 |
| vmess | 12817 |
| shadowsocks | 9695 |
| trojan | 7960 |
| hysteria2 | 1522 |
| http | 638 |
| shadowsocksr | 126 |
| socks | 53 |
| tuic | 14 |
| hysteria | 11 |
| anytls | 3 |

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
| 77.76 | shadowsocks | 248.2 | 660.8 | 22.03 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 37.19.198.244 |
| 77.19 | vless | 242.5 | 609.0 | 22.16 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 195.123.235.177 |
| 76.96 | vless | 252.6 | 686.9 | 21.93 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 79.141.172.154 |
| 76.91 | vless | 254.8 | 696.2 | 21.88 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 47.253.226.114 |
| 76.88 | vless | 256.0 | 661.1 | 21.85 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 137.184.218.169 |
| 76.83 | shadowsocks | 310.1 | 772.3 | 20.6 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 51.222.12.127 |
| 76.52 | shadowsocks | 280.2 | 779.8 | 21.29 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 15.204.247.206 |
| 76.48 | shadowsocks | 238.1 | 596.9 | 22.27 | 0.0 | 10.0 | 13.81 | 14.4 | Surfboard-tg-mixed | 198.98.53.130 |
| 76.25 | shadowsocks | 311.5 | 775.8 | 20.57 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 51.222.141.125 |
| 76.09 | vless | 290.3 | 744.6 | 21.06 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 169.40.42.179 |
| 75.85 | vless | 300.8 | 652.4 | 20.82 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 169.40.42.212 |
| 75.64 | shadowsocks | 304.3 | 715.7 | 20.73 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 156.146.38.167 |
| 75.48 | hysteria2 | 246.1 | 642.3 | 22.08 | 0.0 | 10.0 | 13.2 | 11.3 | mheidari-all | 159.223.157.129 |
| 75.34 | shadowsocks | 313.4 | 750.1 | 20.52 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 156.146.38.168 |
| 75.17 | vless | 330.1 | 861.8 | 20.14 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 167.17.69.171 |
| 75.14 | vless | 331.3 | 823.5 | 20.11 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 169.40.42.15 |
| 75.06 | shadowsocks | 284.8 | 657.1 | 21.18 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 156.146.38.170 |
| 74.83 | shadowsocks | 396.4 | 1016.8 | 18.6 | 0.0 | 10.0 | 13.81 | 16.92 | Au1rxx-base64 | 51.222.200.165 |
| 74.82 | vless | 345.0 | 857.4 | 19.79 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 169.40.42.16 |
| 74.69 | vless | 350.9 | 919.8 | 19.66 | 0.0 | 10.0 | 8.11 | 16.92 | Au1rxx-base64 | 169.40.42.74 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | 0.879 | 298 | 1668 | prefer |
| DeltaKronecker-all | 0.872 | 0.818 | 22 | 5972 | prefer |
| mheidari-all | 0.848 | 0.778 | 54 | 15903 | prefer |
| Surfboard-tg-mixed | 0.786 | 0.709 | 117 | 7478 | prefer |
| ermaozi | 0.632 | 0.62 | 50 | 417 | observe |
| roosterkid-openproxylist-v2ray | 0.532 | 0.889 | 9 | 150 | observe |
| ermaozi-get_subscribe | 0.356 | 0.375 | 16 | 444 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9127 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6074 | observe |
| barry-far-vless | 0.255 | None | 0 | 6310 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4176 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 24 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyConnectionError | - | 9 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| geo | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
