# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 21:26:32 |
| 运行耗时 | 299.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 90115 |
| 去重后节点 | 25048 |
| TCP 可达 | 3000 |
| 真实可用 | 563 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25048 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 41.6 |
| probe | 86.7 |
| real_test | 116.4 |
| generate | 47.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55968 |
| vmess | 12629 |
| shadowsocks | 10668 |
| trojan | 8877 |
| hysteria2 | 1604 |
| http | 138 |
| shadowsocksr | 128 |
| socks | 59 |
| hysteria | 17 |
| anytls | 16 |
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
| 82.0 | hysteria2 | 245.3 | 642.1 | 22.1 | 0.0 | 10.0 | 14.38 | 19.62 | Au1rxx-base64 | 159.223.157.129 |
| 81.77 | vless | 257.3 | 646.6 | 21.82 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.182 |
| 81.43 | vless | 297.3 | 728.5 | 20.9 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 66.70.179.198 |
| 81.08 | vless | 289.7 | 747.6 | 21.07 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.35 |
| 80.97 | vless | 316.8 | 759.9 | 20.44 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.163 |
| 80.33 | vless | 301.4 | 729.3 | 20.8 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.212 |
| 80.18 | vless | 351.1 | 929.6 | 19.65 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.133 |
| 79.97 | vless | 360.4 | 906.3 | 19.44 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.229 |
| 79.96 | vless | 360.7 | 894.8 | 19.43 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.90 |
| 79.89 | vless | 325.8 | 845.6 | 20.24 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.224 |
| 79.87 | hysteria2 | 295.3 | 583.4 | 20.94 | 0.0 | 10.0 | 14.38 | 19.62 | Au1rxx-base64 | 66.94.121.46 |
| 79.7 | vless | 371.7 | 1009.7 | 19.17 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 185.95.231.156 |
| 79.69 | shadowsocks | 323.7 | 816.8 | 20.29 | 0.0 | 10.0 | 14.28 | 19.62 | Au1rxx-base64 | 51.222.200.165 |
| 79.55 | shadowsocks | 229.4 | 602.0 | 22.47 | 0.0 | 10.0 | 14.28 | 16.8 | Surfboard-tg-mixed | 198.98.53.130 |
| 79.37 | vless | 262.1 | 669.7 | 21.71 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.235 |
| 79.28 | vless | 260.4 | 663.8 | 21.75 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 195.123.235.177 |
| 79.26 | vless | 331.1 | 868.8 | 20.11 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.104 |
| 79.23 | vless | 379.2 | 884.6 | 19.0 | 0.0 | 10.0 | 10.91 | 19.62 | Au1rxx-base64 | 169.40.42.15 |
| 79.04 | shadowsocks | 286.9 | 657.0 | 21.14 | 0.0 | 10.0 | 14.28 | 19.62 | Au1rxx-base64 | 156.146.38.169 |
| 78.82 | shadowsocks | 260.7 | 689.6 | 21.74 | 0.0 | 10.0 | 14.28 | 16.8 | Surfboard-tg-mixed | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.946 | 371 | 1688 | prefer |
| DeltaKronecker-all | 0.898 | 0.85 | 20 | 6417 | prefer |
| mheidari-all | 0.819 | 0.744 | 86 | 16413 | prefer |
| Surfboard-tg-mixed | 0.802 | 0.725 | 142 | 7444 | prefer |
| zhangkai | 0.686 | 0.696 | 23 | 144 | observe |
| xiaoji235-airport-v2ray-all | 0.45 | 0.36 | 25 | 5750 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 196 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7899 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8444 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6179 | observe |
| barry-far-vless | 0.255 | None | 0 | 6394 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4218 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 28 |
| geo | ClientOSError | - | 20 |
| 204 | TimeoutError | - | 19 |
| cn-block | ClientOSError | - | 13 |
| 204 | ProxyConnectionError | - | 7 |
| speed | ClientOSError | - | 6 |
| geo | TimeoutError | - | 6 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
