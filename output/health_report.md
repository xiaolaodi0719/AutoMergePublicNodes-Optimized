# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-20 15:54:30 |
| 运行耗时 | 478.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 84264 |
| 去重后节点 | 23485 |
| TCP 可达 | 3000 |
| 真实可用 | 446 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23485 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.5 |
| tcp | 38.6 |
| probe | 172.3 |
| real_test | 175.0 |
| generate | 84.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50854 |
| vmess | 13539 |
| shadowsocks | 9836 |
| trojan | 8203 |
| hysteria2 | 1049 |
| http | 576 |
| shadowsocksr | 122 |
| socks | 70 |
| hysteria | 11 |
| tuic | 3 |
| anytls | 1 |

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
| 82.33 | vless | 270.2 | 717.4 | 21.52 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 81.93 | vless | 284.3 | 718.6 | 21.2 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 79.141.172.154 |
| 81.49 | vless | 306.8 | 689.0 | 20.68 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 81.36 | shadowsocks | 268.6 | 688.0 | 21.56 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.04 | hysteria2 | 278.1 | 710.7 | 21.34 | 0.0 | 10.0 | 12.0 | 18.8 | mheidari-all | 159.223.157.129 |
| 80.92 | vless | 331.2 | 853.6 | 20.11 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 80.45 | shadowsocks | 307.9 | 809.6 | 20.65 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.33 | vless | 329.2 | 684.8 | 20.16 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.173 |
| 80.29 | shadowsocks | 256.0 | 646.9 | 21.85 | 0.0 | 10.0 | 13.8 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 78.82 | vless | 378.0 | 901.0 | 19.03 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.163 |
| 78.41 | vless | 322.1 | 780.5 | 20.32 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 77.85 | vless | 271.2 | 639.9 | 21.5 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 195.211.98.43 |
| 77.77 | vless | 467.2 | 1240.5 | 16.96 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 158.69.112.254 |
| 77.66 | vless | 294.5 | 710.2 | 20.96 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 77.63 | vless | 321.2 | 696.9 | 20.34 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 138.124.60.146 |
| 77.53 | vless | 295.4 | 724.8 | 20.94 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.74 |
| 77.32 | vless | 460.2 | 1203.2 | 17.13 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.223 |
| 77.29 | vless | 307.6 | 762.8 | 20.66 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 77.2 | vless | 361.0 | 844.0 | 19.42 | 0.0 | 10.0 | 10.81 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 76.96 | shadowsocks | 240.9 | 604.7 | 22.2 | 0.0 | 10.0 | 13.8 | 14.96 | Surfboard-tg-mixed | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | 0.899 | 277 | 1617 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.655 | 206 | 7133 | prefer |
| mheidari-all | 0.683 | 0.607 | 61 | 16459 | observe |
| ermaozi | 0.679 | 0.68 | 25 | 314 | observe |
| DeltaKronecker-all | 0.352 | 0.364 | 11 | 6092 | observe |
| 10ium-ScrapeCategorize-Vless | 0.349 | 0.667 | 3 | 5238 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 103 | observe |
| Epodonios-all | 0.255 | None | 0 | 7577 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9286 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5703 | observe |
| barry-far-vless | 0.255 | None | 0 | 5918 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1617 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 39 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 14 |
| geo | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 10 |
| speed | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
