# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 03:20:03 |
| 运行耗时 | 329.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80289 |
| 去重后节点 | 22839 |
| TCP 可达 | 3000 |
| 真实可用 | 731 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22839 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 32.7 |
| probe | 70.5 |
| real_test | 197.2 |
| generate | 22.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45418 |
| trojan | 14277 |
| vmess | 10175 |
| shadowsocks | 9843 |
| hysteria2 | 345 |
| socks | 87 |
| shadowsocksr | 73 |
| http | 50 |
| hysteria | 15 |
| tuic | 5 |
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
| 75.44 | vless | 198.8 | 477.8 | 23.18 | 0.0 | 10.0 | 4.56 | 18.7 | mheidari-all | 198.41.209.87 |
| 75.31 | vless | 204.4 | 479.3 | 23.05 | 0.0 | 10.0 | 4.56 | 18.7 | mheidari-all | 104.16.9.20 |
| 73.75 | trojan | 345.5 | 328.7 | 19.78 | 2.68 | 9.84 | 12.74 | 18.7 | mheidari-all | 31.223.184.43 |
| 73.68 | trojan | 342.1 | 333.8 | 19.86 | 2.48 | 9.9 | 12.74 | 18.7 | mheidari-all | 31.223.184.125 |
| 73.66 | trojan | 340.6 | 335.0 | 19.89 | 2.44 | 9.91 | 12.74 | 18.7 | mheidari-all | 31.223.184.82 |
| 73.52 | trojan | 339.5 | 337.4 | 19.92 | 2.35 | 9.85 | 12.74 | 18.7 | mheidari-all | 31.223.184.149 |
| 73.12 | trojan | 344.8 | 342.6 | 19.8 | 2.15 | 9.87 | 12.74 | 18.7 | mheidari-all | 95.85.94.165 |
| 73.01 | trojan | 349.7 | 339.3 | 19.68 | 2.28 | 9.9 | 12.74 | 18.7 | mheidari-all | 31.223.184.164 |
| 72.4 | trojan | 451.3 | 1096.3 | 17.33 | 0.0 | 10.0 | 12.74 | 18.7 | mheidari-all | 163.245.196.68 |
| 71.68 | trojan | 341.1 | 358.2 | 19.88 | 1.57 | 9.91 | 12.74 | 18.7 | mheidari-all | 31.223.184.109 |
| 71.31 | vless | 226.0 | 600.1 | 22.55 | 0.0 | 10.0 | 4.56 | 18.7 | mheidari-all | 182.16.61.3 |
| 70.67 | vless | 253.4 | 672.7 | 21.91 | 0.0 | 10.0 | 4.56 | 18.7 | mheidari-all | 182.16.61.2 |
| 70.53 | trojan | 368.0 | 427.7 | 19.26 | 0.0 | 9.85 | 12.74 | 18.7 | mheidari-all | 31.223.184.238 |
| 70.51 | trojan | 358.7 | 409.6 | 19.47 | 0.0 | 9.89 | 12.74 | 18.7 | mheidari-all | 95.85.94.199 |
| 70.43 | trojan | 369.3 | 424.0 | 19.23 | 0.0 | 9.85 | 12.74 | 18.7 | mheidari-all | 95.85.94.148 |
| 70.04 | trojan | 384.8 | 472.1 | 18.87 | 0.0 | 9.9 | 12.74 | 18.7 | mheidari-all | 95.85.94.90 |
| 69.12 | trojan | 386.5 | 458.2 | 18.83 | 0.0 | 9.85 | 12.74 | 18.7 | mheidari-all | 95.85.94.112 |
| 68.08 | vless | 195.2 | 502.3 | 23.26 | 0.0 | 10.0 | 4.56 | 17.76 | Surfboard-tg-mixed | 59.152.127.76 |
| 67.59 | vless | 321.6 | 520.1 | 20.33 | 0.0 | 10.0 | 4.56 | 18.7 | mheidari-all | 104.16.72.110 |
| 67.59 | trojan | 446.1 | 519.7 | 17.45 | 0.0 | 9.91 | 12.74 | 18.7 | mheidari-all | 95.85.94.17 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.945 | 0.97 | 33 | 61 | prefer |
| Surfboard-tg-mixed | 0.765 | 0.686 | 255 | 5472 | prefer |
| mheidari-all | 0.647 | 0.567 | 880 | 19397 | observe |
| DeltaKronecker-all | 0.383 | 0.297 | 74 | 5559 | observe |
| Au1rxx-base64 | 0.329 | 1.0 | 2 | 432 | observe |
| tg-ConfigV2rayNG | 0.263 | 1.0 | 1 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4588 | observe |
| Epodonios-all | 0.255 | None | 0 | 6656 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6389 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4180 | observe |
| barry-far-vless | 0.255 | None | 0 | 4847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5027 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 190 |
| geo | TimeoutError | - | 165 |
| speed | TimeoutError | - | 56 |
| geo | ClientOSError | - | 44 |
| cn-block | TimeoutError | - | 43 |
| 204 | TimeoutError | - | 7 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
