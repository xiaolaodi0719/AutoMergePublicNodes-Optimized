# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-27 22:07:17 |
| 运行耗时 | 220.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 87058 |
| 去重后节点 | 23525 |
| TCP 可达 | 3000 |
| 真实可用 | 474 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23525 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.9 |
| geo | 1.5 |
| tcp | 38.8 |
| probe | 47.1 |
| real_test | 87.8 |
| generate | 34.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53670 |
| shadowsocks | 11824 |
| vmess | 11576 |
| trojan | 7616 |
| hysteria2 | 1951 |
| http | 164 |
| shadowsocksr | 141 |
| socks | 75 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 5 |

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
| 83.37 | hysteria2 | 294.3 | 817.7 | 20.97 | 0.0 | 10.0 | 13.64 | 19.86 | Au1rxx-base64 | 159.223.157.129 |
| 82.38 | shadowsocks | 237.8 | 647.2 | 22.27 | 0.0 | 10.0 | 14.25 | 19.86 | Au1rxx-base64 | 37.19.198.236 |
| 81.47 | shadowsocks | 277.1 | 762.3 | 21.36 | 0.0 | 10.0 | 14.25 | 19.86 | Au1rxx-base64 | 198.98.53.130 |
| 81.22 | vless | 260.6 | 629.5 | 21.75 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 195.211.99.49 |
| 81.15 | vless | 263.5 | 640.2 | 21.68 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 195.211.99.45 |
| 81.11 | vless | 265.1 | 702.9 | 21.64 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.235 |
| 80.95 | vless | 271.9 | 714.4 | 21.48 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.74 |
| 80.85 | vless | 276.4 | 734.8 | 21.38 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 167.17.69.171 |
| 80.76 | vless | 280.5 | 621.1 | 21.29 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.225 |
| 80.46 | vless | 254.8 | 683.2 | 21.88 | 0.0 | 9.11 | 9.61 | 19.86 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 80.39 | vless | 296.4 | 819.8 | 20.92 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 137.184.218.169 |
| 80.32 | shadowsocks | 231.9 | 633.7 | 22.41 | 0.0 | 10.0 | 14.25 | 17.66 | Surfboard-tg-mixed | 37.19.198.243 |
| 80.14 | shadowsocks | 239.8 | 658.5 | 22.23 | 0.0 | 10.0 | 14.25 | 17.66 | Surfboard-tg-mixed | 37.19.198.244 |
| 79.93 | shadowsocks | 322.1 | 927.2 | 20.32 | 0.0 | 10.0 | 14.25 | 19.86 | Au1rxx-base64 | 15.204.247.175 |
| 79.63 | vless | 329.1 | 895.5 | 20.16 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 79.127.243.217 |
| 79.6 | vless | 287.1 | 705.7 | 21.13 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 216.152.147.28 |
| 79.57 | vless | 331.5 | 845.9 | 20.1 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.173 |
| 79.39 | vless | 339.3 | 803.8 | 19.92 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.229 |
| 79.25 | vless | 345.4 | 935.1 | 19.78 | 0.0 | 10.0 | 9.61 | 19.86 | Au1rxx-base64 | 169.40.42.95 |
| 79.15 | shadowsocks | 269.3 | 765.6 | 21.54 | 0.0 | 10.0 | 14.25 | 19.86 | Au1rxx-base64 | 15.204.247.124 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.945 | 307 | 1622 | prefer |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.835 | 0.759 | 141 | 6577 | prefer |
| mheidari-all | 0.623 | 0.544 | 90 | 19755 | observe |
| DeltaKronecker-all | 0.4 | 0.75 | 4 | 4318 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5418 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4783 | observe |
| Epodonios-all | 0.255 | None | 0 | 6955 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3991 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7129 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5393 | observe |
| barry-far-vless | 0.255 | None | 0 | 5568 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4019 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1622 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 35 |
| 204 | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 5 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
