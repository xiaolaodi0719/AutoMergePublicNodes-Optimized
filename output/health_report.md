# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 04:14:12 |
| 运行耗时 | 763.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85797 |
| 去重后节点 | 22922 |
| TCP 可达 | 3000 |
| 真实可用 | 505 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22922 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 39.1 |
| probe | 262.1 |
| real_test | 374.0 |
| generate | 80.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53136 |
| vmess | 11833 |
| shadowsocks | 10034 |
| trojan | 8359 |
| hysteria2 | 1576 |
| http | 638 |
| shadowsocksr | 127 |
| socks | 75 |
| hysteria | 9 |
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
| 81.03 | vless | 273.3 | 697.9 | 21.45 | 0.0 | 8.41 | 11.85 | 19.32 | Au1rxx-base64 | 167.17.69.171 |
| 80.73 | vless | 288.8 | 705.9 | 21.09 | 0.0 | 8.47 | 11.85 | 19.32 | Au1rxx-base64 | 66.70.179.198 |
| 80.62 | vless | 289.6 | 754.3 | 21.07 | 0.0 | 8.38 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.224 |
| 80.09 | vless | 262.4 | 706.7 | 21.7 | 0.0 | 10.0 | 11.85 | 16.54 | Surfboard-tg-mixed | 47.89.186.170 |
| 79.96 | vless | 321.1 | 834.8 | 20.35 | 0.0 | 8.44 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.163 |
| 79.78 | vless | 325.9 | 877.0 | 20.23 | 0.0 | 8.38 | 11.85 | 19.32 | Au1rxx-base64 | 137.184.218.169 |
| 79.76 | vless | 330.8 | 862.2 | 20.12 | 0.0 | 8.47 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.89 |
| 79.69 | vless | 332.6 | 870.4 | 20.08 | 0.0 | 8.44 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.90 |
| 79.51 | vless | 337.4 | 893.7 | 19.97 | 0.0 | 8.37 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.231 |
| 79.5 | vless | 349.2 | 875.9 | 19.69 | 0.0 | 8.64 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.133 |
| 79.37 | hysteria2 | 289.8 | 788.6 | 21.07 | 0.0 | 10.0 | 12.86 | 16.54 | Surfboard-tg-mixed | 159.223.157.129 |
| 79.18 | vless | 246.4 | 687.1 | 22.07 | 0.0 | 10.0 | 11.85 | 18.26 | DeltaKronecker-all | 79.141.172.154 |
| 78.94 | vless | 365.1 | 919.4 | 19.33 | 0.0 | 8.44 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.212 |
| 78.8 | vless | 372.1 | 877.6 | 19.16 | 0.0 | 8.47 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.235 |
| 78.79 | vless | 372.9 | 879.4 | 19.15 | 0.0 | 8.47 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.104 |
| 78.65 | vless | 376.2 | 1009.9 | 19.07 | 0.0 | 8.41 | 11.85 | 19.32 | Au1rxx-base64 | 185.95.231.156 |
| 78.55 | vless | 352.5 | 879.9 | 19.62 | 0.0 | 8.44 | 11.85 | 19.32 | Au1rxx-base64 | 169.40.42.179 |
| 78.36 | shadowsocks | 244.5 | 652.3 | 22.12 | 0.0 | 10.0 | 13.72 | 16.52 | mheidari-all | 37.19.198.160 |
| 78.36 | shadowsocks | 245.1 | 641.4 | 22.1 | 0.0 | 10.0 | 13.72 | 16.54 | Surfboard-tg-mixed | 198.98.53.130 |
| 78.31 | shadowsocks | 246.7 | 658.2 | 22.07 | 0.0 | 10.0 | 13.72 | 16.52 | mheidari-all | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.894 | 0.829 | 41 | 16648 | prefer |
| Au1rxx-base64 | 0.891 | 0.826 | 264 | 1690 | prefer |
| Surfboard-tg-mixed | 0.838 | 0.76 | 192 | 7520 | prefer |
| ermaozi | 0.629 | 0.618 | 34 | 442 | observe |
| ermaozi-get_subscribe | 0.572 | 0.579 | 19 | 473 | observe |
| DeltaKronecker-all | 0.433 | 0.351 | 205 | 6097 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 176 | observe |
| Epodonios-all | 0.255 | None | 0 | 7969 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8963 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6208 | observe |
| barry-far-vless | 0.255 | None | 0 | 6393 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 67 |
| 204 | ProxyError | - | 38 |
| geo | ClientOSError | - | 34 |
| speed | ClientOSError | - | 29 |
| speed | TimeoutError | - | 29 |
| cn-block | ClientOSError | - | 26 |
| cn-block | TimeoutError | - | 18 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
