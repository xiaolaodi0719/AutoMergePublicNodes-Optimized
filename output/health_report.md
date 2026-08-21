# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 18:48:48 |
| 运行耗时 | 367.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 93362 |
| 去重后节点 | 23312 |
| TCP 可达 | 3000 |
| 真实可用 | 1165 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23312 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 0.6 |
| tcp | 38.5 |
| probe | 69.0 |
| real_test | 216.9 |
| generate | 35.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51623 |
| trojan | 18701 |
| shadowsocks | 10587 |
| vmess | 10282 |
| hysteria2 | 1604 |
| shadowsocksr | 206 |
| http | 167 |
| socks | 132 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 81.65 | shadowsocks | 226.1 | 623.9 | 22.54 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 81.06 | shadowsocks | 251.7 | 705.2 | 21.95 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.0 | vless | 313.1 | 874.7 | 20.53 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 80.97 | vless | 314.3 | 845.6 | 20.5 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 80.7 | vless | 326.2 | 595.6 | 20.23 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 79.84 | vless | 363.1 | 938.5 | 19.37 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 169.40.42.202 |
| 79.83 | vless | 271.8 | 623.8 | 21.49 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 79.78 | shadowsocks | 296.3 | 783.2 | 20.92 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 79.42 | shadowsocks | 301.1 | 790.4 | 20.81 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 38.180.135.156 |
| 79.17 | vless | 262.6 | 706.6 | 21.7 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 179.255.185.74 |
| 79.11 | vless | 328.2 | 756.8 | 20.18 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 107.151.201.59 |
| 78.38 | vless | 292.6 | 808.5 | 21.01 | 0.0 | 10.0 | 10.47 | 16.9 | mheidari-all | 79.127.243.217 |
| 78.23 | shadowsocks | 295.5 | 649.9 | 20.94 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 78.12 | shadowsocks | 244.6 | 678.6 | 22.11 | 0.0 | 10.0 | 13.11 | 16.9 | mheidari-all | 37.19.198.243 |
| 77.1 | hysteria2 | 286.9 | 544.4 | 21.14 | 0.0 | 10.0 | 12.95 | 16.9 | mheidari-all | 150.241.102.127 |
| 77.08 | vless | 371.6 | 947.6 | 19.18 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 77.07 | vless | 322.5 | 870.5 | 20.31 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 169.40.42.52 |
| 76.93 | shadowsocks | 293.8 | 653.6 | 20.98 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 76.79 | shadowsocks | 297.1 | 639.2 | 20.9 | 0.0 | 10.0 | 13.11 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 76.77 | vless | 463.1 | 1230.1 | 17.06 | 0.0 | 10.0 | 10.47 | 20.0 | Au1rxx-base64 | 158.69.112.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.985 | 687 | 1933 | prefer |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| Surfboard-tg-mixed | 0.921 | 0.85 | 80 | 6488 | prefer |
| mheidari-all | 0.866 | 0.787 | 385 | 21956 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| roosterkid-openproxylist-v2ray | 0.317 | 1.0 | 2 | 150 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7155 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7163 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5287 | observe |
| barry-far-vless | 0.255 | None | 0 | 5535 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4091 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 37 |
| geo | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 11 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
