# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-19 13:01:34 |
| 运行耗时 | 347.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82413 |
| 去重后节点 | 22576 |
| TCP 可达 | 3000 |
| 真实可用 | 1136 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22576 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.1 |
| geo | 0.8 |
| tcp | 35.8 |
| probe | 63.5 |
| real_test | 201.0 |
| generate | 26.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44754 |
| trojan | 17707 |
| shadowsocks | 9991 |
| vmess | 8499 |
| hysteria2 | 1062 |
| http | 165 |
| socks | 122 |
| shadowsocksr | 94 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 4 |

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
| 82.21 | shadowsocks | 226.2 | 626.8 | 22.54 | 0.0 | 10.0 | 13.67 | 20.0 | mheidari-all | 37.19.198.243 |
| 81.17 | vless | 261.6 | 624.5 | 21.72 | 0.0 | 9.36 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 80.91 | vless | 273.3 | 666.5 | 21.45 | 0.0 | 9.37 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.90 |
| 80.67 | vless | 284.6 | 620.7 | 21.19 | 0.0 | 9.39 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 80.37 | vless | 323.8 | 823.2 | 20.28 | 0.0 | 10.0 | 10.09 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 80.3 | shadowsocks | 308.8 | 689.2 | 20.63 | 0.0 | 10.0 | 13.67 | 20.0 | mheidari-all | 37.19.198.244 |
| 79.45 | vless | 251.4 | 682.2 | 21.96 | 0.0 | 10.0 | 10.09 | 17.4 | Surfboard-tg-mixed | 204.48.20.223 |
| 79.3 | vless | 370.2 | 886.1 | 19.21 | 0.0 | 10.0 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 79.22 | shadowsocks | 243.8 | 677.4 | 22.14 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 78.35 | vless | 270.3 | 658.4 | 21.52 | 0.0 | 9.41 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 78.35 | vless | 324.9 | 738.3 | 20.26 | 0.0 | 10.0 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.173 |
| 78.12 | vless | 261.5 | 621.5 | 21.72 | 0.0 | 9.26 | 10.09 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 78.04 | shadowsocks | 283.1 | 657.4 | 21.23 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.9 | trojan | 374.7 | 884.2 | 19.1 | 0.0 | 10.0 | 14.73 | 20.0 | mheidari-all | 64.94.95.118 |
| 77.87 | shadowsocks | 289.9 | 669.8 | 21.07 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 77.77 | vless | 241.8 | 651.2 | 22.18 | 0.0 | 10.0 | 10.09 | 20.0 | mheidari-all | 172.64.146.153 |
| 77.59 | shadowsocks | 279.6 | 643.1 | 21.31 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.17 | vless | 312.6 | 786.4 | 20.54 | 0.0 | 10.0 | 10.09 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 77.13 | shadowsocks | 315.1 | 718.2 | 20.48 | 0.0 | 10.0 | 13.67 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 77.12 | shadowsocks | 315.3 | 728.0 | 20.48 | 0.0 | 10.0 | 13.67 | 20.0 | mheidari-all | 23.150.248.20 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.976 | 614 | 1765 | prefer |
| mheidari-all | 0.989 | 0.911 | 315 | 16605 | prefer |
| zhangkai | 0.979 | 0.982 | 111 | 144 | prefer |
| Surfboard-tg-mixed | 0.917 | 0.842 | 158 | 6304 | prefer |
| DeltaKronecker-all | 0.418 | 0.5 | 10 | 6390 | observe |
| nscl5-all | 0.391 | 1.0 | 2 | 3330 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7081 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7049 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4858 | observe |
| barry-far-vless | 0.255 | None | 0 | 5240 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3995 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 8 |
| geo | TimeoutError | - | 7 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| geo | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
