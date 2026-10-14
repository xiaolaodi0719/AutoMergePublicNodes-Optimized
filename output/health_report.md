# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 04:31:00 |
| 运行耗时 | 758.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98590 |
| 去重后节点 | 27420 |
| TCP 可达 | 3000 |
| 真实可用 | 437 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27420 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.7 |
| tcp | 47.6 |
| probe | 258.9 |
| real_test | 352.7 |
| generate | 89.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58027 |
| vmess | 16099 |
| shadowsocks | 11898 |
| trojan | 10487 |
| hysteria2 | 1309 |
| http | 486 |
| shadowsocksr | 165 |
| socks | 70 |
| anytls | 25 |
| hysteria | 18 |
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
| 83.44 | vless | 276.7 | 687.1 | 21.37 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 147.45.60.160 |
| 82.7 | hysteria2 | 297.7 | 683.8 | 20.89 | 0.0 | 10.0 | 13.85 | 19.46 | Au1rxx-base64 | 129.213.91.185 |
| 82.11 | hysteria2 | 270.2 | 258.9 | 21.52 | 5.29 | 9.64 | 13.85 | 19.46 | Au1rxx-base64 | 45.32.10.7 |
| 81.95 | shadowsocks | 231.0 | 609.8 | 22.43 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 156.146.38.167 |
| 81.49 | shadowsocks | 251.1 | 636.7 | 21.97 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 156.146.38.169 |
| 81.11 | shadowsocks | 267.5 | 680.6 | 21.59 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 156.146.38.168 |
| 80.19 | shadowsocks | 304.1 | 751.2 | 20.74 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 37.19.198.244 |
| 79.52 | shadowsocks | 314.3 | 771.4 | 20.5 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 64.74.163.69 |
| 79.4 | shadowsocks | 301.1 | 754.0 | 20.81 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 37.19.198.236 |
| 79.18 | vless | 290.2 | 583.7 | 21.06 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 45.32.69.110 |
| 78.76 | vless | 299.8 | 594.6 | 20.84 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 144.202.126.147 |
| 78.62 | vless | 318.3 | 595.1 | 20.41 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 195.123.240.65 |
| 78.41 | vless | 423.4 | 1053.0 | 17.98 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 185.95.231.156 |
| 78.33 | vless | 347.9 | 791.6 | 19.72 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 169.40.42.16 |
| 78.22 | vless | 399.6 | 954.8 | 18.53 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 159.89.87.21 |
| 78.14 | shadowsocks | 366.0 | 933.4 | 19.3 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 37.19.198.160 |
| 78.07 | vless | 325.6 | 703.2 | 20.24 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 167.17.69.171 |
| 77.72 | shadowsocks | 309.8 | 765.2 | 20.61 | 0.0 | 10.0 | 14.06 | 19.46 | Au1rxx-base64 | 37.19.198.243 |
| 77.72 | vless | 353.0 | 834.4 | 19.61 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 169.40.42.182 |
| 77.66 | vless | 370.9 | 831.1 | 19.19 | 0.0 | 10.0 | 12.61 | 19.46 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.946 | 0.877 | 326 | 1771 | prefer |
| Surfboard-tg-mixed | 0.899 | 0.829 | 70 | 7113 | prefer |
| mheidari-all | 0.457 | 0.376 | 189 | 24076 | observe |
| DeltaKronecker-all | 0.397 | 0.417 | 12 | 5076 | observe |
| ermaozi-get_subscribe | 0.349 | 0.316 | 38 | 598 | observe |
| zhangkai | 0.311 | 0.5 | 8 | 144 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5086 | observe |
| Epodonios-all | 0.255 | None | 0 | 7613 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9825 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5621 | observe |
| barry-far-vless | 0.255 | None | 0 | 5866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 78 |
| 204 | ProxyError | - | 23 |
| geo | ClientOSError | - | 22 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyConnectionError | - | 14 |
| 204 | TimeoutError | - | 11 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
