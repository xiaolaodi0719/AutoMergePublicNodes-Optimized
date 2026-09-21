# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-21 04:30:59 |
| 运行耗时 | 847.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83915 |
| 去重后节点 | 23652 |
| TCP 可达 | 3000 |
| 真实可用 | 658 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23652 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 39.8 |
| probe | 280.7 |
| real_test | 444.0 |
| generate | 74.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50275 |
| vmess | 13549 |
| shadowsocks | 9783 |
| trojan | 8346 |
| hysteria2 | 1090 |
| http | 647 |
| shadowsocksr | 140 |
| socks | 67 |
| hysteria | 9 |
| anytls | 5 |
| tuic | 4 |

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
| 82.99 | vless | 227.5 | 651.5 | 22.51 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 216.152.147.28 |
| 82.46 | vless | 250.5 | 633.0 | 21.98 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 195.211.98.43 |
| 81.94 | vless | 273.0 | 656.2 | 21.46 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 195.123.235.177 |
| 81.85 | vless | 276.9 | 703.9 | 21.37 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 79.141.172.154 |
| 80.64 | hysteria2 | 262.4 | 689.5 | 21.7 | 0.0 | 10.0 | 14.0 | 16.04 | mheidari-all | 159.223.157.129 |
| 80.04 | shadowsocks | 298.5 | 796.0 | 20.87 | 0.0 | 10.0 | 14.15 | 19.52 | Au1rxx-base64 | 15.204.247.206 |
| 79.04 | vless | 277.1 | 599.5 | 21.36 | 0.0 | 10.0 | 10.96 | 17.72 | DeltaKronecker-all | 172.67.130.144 |
| 78.6 | vless | 347.1 | 713.6 | 19.74 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 169.40.42.225 |
| 78.48 | vless | 339.7 | 743.2 | 19.91 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 169.40.42.235 |
| 78.28 | hysteria2 | 318.0 | 586.8 | 20.42 | 0.0 | 10.0 | 14.0 | 19.52 | Au1rxx-base64 | 66.94.121.46 |
| 78.25 | vless | 305.9 | 650.4 | 20.7 | 0.0 | 10.0 | 10.96 | 17.72 | DeltaKronecker-all | 104.21.8.176 |
| 78.18 | vless | 271.4 | 564.3 | 21.5 | 0.0 | 10.0 | 10.96 | 17.72 | DeltaKronecker-all | 172.67.214.106 |
| 77.98 | shadowsocks | 258.6 | 664.1 | 21.79 | 0.0 | 10.0 | 14.15 | 16.04 | mheidari-all | 37.19.198.244 |
| 77.95 | vless | 382.7 | 888.5 | 18.92 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 169.40.42.133 |
| 77.84 | shadowsocks | 264.8 | 685.7 | 21.65 | 0.0 | 10.0 | 14.15 | 16.04 | mheidari-all | 37.19.198.236 |
| 77.83 | vless | 426.6 | 1114.1 | 17.9 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 209.200.246.148 |
| 77.79 | shadowsocks | 374.1 | 1016.3 | 19.12 | 0.0 | 10.0 | 14.15 | 19.52 | Au1rxx-base64 | 142.4.216.225 |
| 77.71 | shadowsocks | 270.4 | 698.2 | 21.52 | 0.0 | 10.0 | 14.15 | 16.04 | mheidari-all | 37.19.198.160 |
| 77.68 | vless | 367.1 | 767.6 | 19.28 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 169.40.42.95 |
| 77.67 | shadowsocks | 331.9 | 804.1 | 20.09 | 0.0 | 10.0 | 14.15 | 19.52 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | 0.871 | 310 | 1693 | prefer |
| ermaozi | 0.696 | 0.69 | 42 | 355 | observe |
| Surfboard-tg-mixed | 0.617 | 0.538 | 158 | 7202 | observe |
| DeltaKronecker-all | 0.562 | 0.482 | 452 | 6092 | observe |
| mheidari-all | 0.561 | 0.48 | 102 | 15960 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4315 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 74 | observe |
| Epodonios-all | 0.255 | None | 0 | 7661 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8828 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5800 | observe |
| barry-far-vless | 0.255 | None | 0 | 6015 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1693 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 174 |
| geo | ClientOSError | - | 82 |
| speed | TimeoutError | - | 51 |
| speed | ClientOSError | - | 44 |
| 204 | ProxyError | - | 24 |
| cn-block | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
