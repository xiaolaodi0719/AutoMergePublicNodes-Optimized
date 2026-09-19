# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 10:47:06 |
| 运行耗时 | 564.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87584 |
| 去重后节点 | 25144 |
| TCP 可达 | 3000 |
| 真实可用 | 484 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25144 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 41.1 |
| probe | 224.1 |
| real_test | 217.3 |
| generate | 76.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52412 |
| vmess | 13840 |
| shadowsocks | 10531 |
| trojan | 8672 |
| hysteria2 | 1262 |
| http | 656 |
| shadowsocksr | 127 |
| socks | 67 |
| hysteria | 9 |
| tuic | 4 |
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
| 83.8 | hysteria2 | 245.0 | 563.1 | 22.11 | 0.0 | 10.0 | 14.12 | 19.26 | Au1rxx-base64 | 66.94.121.46 |
| 81.37 | shadowsocks | 258.1 | 631.5 | 21.8 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 156.146.38.167 |
| 81.3 | shadowsocks | 261.1 | 644.3 | 21.73 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 156.146.38.170 |
| 80.97 | shadowsocks | 275.7 | 662.7 | 21.4 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 173.244.56.6 |
| 80.95 | shadowsocks | 276.5 | 705.7 | 21.38 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 173.244.56.9 |
| 80.86 | shadowsocks | 280.3 | 695.3 | 21.29 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 156.146.38.169 |
| 80.73 | vless | 231.3 | 569.4 | 22.42 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 198.200.42.129 |
| 80.4 | shadowsocks | 278.4 | 644.9 | 21.33 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 23.150.248.20 |
| 78.01 | shadowsocks | 269.1 | 571.3 | 21.55 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 149.22.95.183 |
| 77.5 | vless | 356.5 | 901.8 | 19.52 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 31.58.50.200 |
| 77.24 | shadowsocks | 307.2 | 785.6 | 20.67 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 107.174.88.128 |
| 76.98 | vless | 210.0 | 539.4 | 22.92 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 162.159.48.32 |
| 76.71 | trojan | 217.1 | 503.2 | 22.75 | 0.0 | 10.0 | 10.2 | 19.26 | Au1rxx-base64 | 43.173.90.202 |
| 76.32 | shadowsocks | 258.6 | 632.0 | 21.79 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 156.146.38.168 |
| 76.11 | trojan | 370.1 | 924.6 | 19.21 | 0.0 | 10.0 | 10.2 | 19.26 | Au1rxx-base64 | 100.42.228.109 |
| 75.87 | vless | 350.3 | 837.4 | 19.67 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 15.204.97.216 |
| 75.71 | vless | 334.2 | 766.1 | 20.04 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 79.141.172.154 |
| 74.93 | shadowsocks | 335.5 | 716.3 | 20.01 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 37.19.198.243 |
| 74.55 | shadowsocks | 352.9 | 764.6 | 19.61 | 0.0 | 10.0 | 14.31 | 19.26 | Au1rxx-base64 | 37.19.198.160 |
| 74.13 | vless | 336.3 | 662.9 | 19.99 | 0.0 | 10.0 | 9.05 | 19.26 | Au1rxx-base64 | 150.241.102.181 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | 0.844 | 307 | 1569 | prefer |
| ermaozi | 0.764 | 0.76 | 50 | 358 | prefer |
| DeltaKronecker-all | 0.716 | 0.645 | 31 | 6421 | prefer |
| Surfboard-tg-mixed | 0.691 | 0.612 | 206 | 7474 | observe |
| mheidari-all | 0.568 | 0.487 | 80 | 19088 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8837 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 5996 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1569 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| cn-block | ClientOSError | - | 32 |
| geo | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 21 |
| 204 | ProxyError | - | 20 |
| speed | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| speed | ClientOSError | - | 13 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
