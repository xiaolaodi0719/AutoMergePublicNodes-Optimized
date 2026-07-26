# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 19:24:58 |
| 运行耗时 | 373.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83998 |
| 去重后节点 | 22074 |
| TCP 可达 | 3000 |
| 真实可用 | 792 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22074 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.3 |
| tcp | 31.5 |
| probe | 81.1 |
| real_test | 214.7 |
| generate | 40.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46653 |
| trojan | 16134 |
| shadowsocks | 10273 |
| vmess | 10066 |
| hysteria2 | 567 |
| shadowsocksr | 106 |
| http | 83 |
| socks | 70 |
| anytls | 21 |
| hysteria | 15 |
| tuic | 10 |

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
| 81.42 | shadowsocks | 218.1 | 514.2 | 22.73 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 149.22.95.183 |
| 80.68 | shadowsocks | 228.5 | 563.3 | 22.49 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 108.181.0.177 |
| 79.17 | shadowsocks | 293.7 | 769.7 | 20.98 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 108.181.118.10 |
| 78.73 | shadowsocks | 204.7 | 520.6 | 23.04 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 173.244.56.6 |
| 77.04 | shadowsocks | 291.6 | 660.4 | 21.03 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 156.146.38.167 |
| 76.8 | shadowsocks | 289.8 | 655.4 | 21.07 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 156.146.38.170 |
| 76.75 | shadowsocks | 291.1 | 654.5 | 21.04 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 156.146.38.168 |
| 76.69 | shadowsocks | 206.4 | 522.6 | 23.0 | 0.0 | 10.0 | 12.79 | 19.9 | Au1rxx-base64 | 173.244.56.9 |
| 76.23 | trojan | 328.9 | 333.1 | 20.16 | 2.51 | 9.94 | 13.62 | 19.9 | Au1rxx-base64 | 95.85.94.17 |
| 76.11 | trojan | 327.9 | 335.6 | 20.19 | 2.41 | 9.88 | 13.62 | 19.9 | Au1rxx-base64 | 31.223.184.164 |
| 76.09 | trojan | 324.4 | 330.9 | 20.27 | 2.59 | 9.57 | 13.62 | 19.9 | Au1rxx-base64 | inspired-hound.rooster465.autos |
| 76.07 | trojan | 326.8 | 338.0 | 20.21 | 2.33 | 9.94 | 13.62 | 19.9 | Au1rxx-base64 | 31.223.184.125 |
| 75.92 | trojan | 324.7 | 332.4 | 20.26 | 2.53 | 9.55 | 13.62 | 19.9 | Au1rxx-base64 | next-ringtail.rooster465.autos |
| 75.22 | trojan | 326.2 | 333.8 | 20.23 | 2.48 | 9.89 | 13.62 | 19.9 | Au1rxx-base64 | 31.223.184.218 |
| 74.94 | trojan | 378.9 | 754.6 | 19.01 | 0.0 | 10.0 | 13.62 | 19.9 | Au1rxx-base64 | 64.94.95.114 |
| 74.62 | trojan | 343.6 | 771.6 | 19.82 | 0.0 | 10.0 | 13.62 | 19.9 | Au1rxx-base64 | 64.94.95.118 |
| 74.4 | shadowsocks | 294.9 | 346.6 | 20.95 | 2.0 | 9.94 | 12.79 | 19.9 | Au1rxx-base64 | 149.22.87.240 |
| 74.31 | vless | 163.1 | 461.8 | 24.0 | 0.0 | 10.0 | 5.41 | 19.9 | Au1rxx-base64 | 173.249.200.68 |
| 74.22 | trojan | 326.4 | 334.0 | 20.22 | 2.47 | 9.89 | 13.62 | 19.9 | Au1rxx-base64 | 31.223.184.58 |
| 73.93 | trojan | 382.4 | 360.5 | 18.93 | 1.48 | 9.94 | 13.62 | 19.9 | Au1rxx-base64 | 31.223.184.178 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 78 | 86 | prefer |
| Au1rxx-base64 | 0.959 | 0.901 | 453 | 1507 | prefer |
| mheidari-all | 0.787 | 0.71 | 162 | 19379 | prefer |
| Surfboard-tg-mixed | 0.654 | 0.577 | 52 | 5487 | observe |
| xiaoji235-airport-v2ray-all | 0.519 | 1.0 | 5 | 3959 | observe |
| tg-oneclickvpnkeys | 0.495 | 0.875 | 8 | 164 | observe |
| DeltaKronecker-all | 0.364 | 0.284 | 522 | 4320 | observe |
| Surfboard-tg-vless | 0.287 | 0.5 | 2 | 4238 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6631 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6557 | observe |
| barry-far-vless | 0.255 | None | 0 | 4894 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5003 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 139 |
| geo | TimeoutError | - | 109 |
| 204 | ProxyError | - | 65 |
| 204 | TimeoutError | - | 65 |
| geo | ClientOSError | - | 41 |
| cn-block | TimeoutError | - | 34 |
| cn-block | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
