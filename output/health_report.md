# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-05 19:46:19 |
| 运行耗时 | 248.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87804 |
| 去重后节点 | 24105 |
| TCP 可达 | 3000 |
| 真实可用 | 461 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24105 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.5 |
| geo | 1.4 |
| tcp | 36.5 |
| probe | 49.9 |
| real_test | 109.5 |
| generate | 36.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51991 |
| vmess | 13181 |
| trojan | 10747 |
| shadowsocks | 10302 |
| hysteria2 | 1361 |
| socks | 74 |
| shadowsocksr | 70 |
| http | 24 |
| anytls | 21 |
| hysteria | 19 |
| tuic | 14 |

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
| 82.95 | vless | 190.4 | 473.1 | 23.37 | 0.0 | 10.0 | 9.76 | 19.82 | Au1rxx-base64 | 176.122.164.194 |
| 82.88 | vless | 193.2 | 499.1 | 23.3 | 0.0 | 10.0 | 9.76 | 19.82 | Au1rxx-base64 | 167.17.68.205 |
| 81.35 | shadowsocks | 211.7 | 497.5 | 22.88 | 0.0 | 9.74 | 13.91 | 19.82 | Au1rxx-base64 | 173.244.56.9 |
| 80.83 | vless | 282.1 | 734.0 | 21.25 | 0.0 | 10.0 | 9.76 | 19.82 | Au1rxx-base64 | 70.39.178.231 |
| 80.46 | hysteria2 | 330.8 | 746.9 | 20.12 | 0.0 | 9.69 | 14.25 | 19.82 | Au1rxx-base64 | 138.124.68.188 |
| 79.65 | http | 370.2 | 1034.0 | 19.21 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 79.58 | http | 373.0 | 1031.6 | 19.14 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 79.58 | http | 373.3 | 1035.9 | 19.14 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 79.43 | trojan | 258.3 | 520.2 | 21.8 | 0.0 | 9.2 | 14.44 | 19.82 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 79.35 | http | 382.9 | 1060.5 | 18.91 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 78.53 | vless | 358.5 | 871.9 | 19.48 | 0.0 | 10.0 | 9.76 | 19.82 | Au1rxx-base64 | 64.49.38.6 |
| 78.52 | trojan | 281.4 | 579.5 | 21.26 | 0.0 | 9.19 | 14.44 | 19.82 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 78.47 | trojan | 264.2 | 538.3 | 21.66 | 0.0 | 9.61 | 14.44 | 19.82 | Au1rxx-base64 | 44.246.163.102 |
| 78.29 | shadowsocks | 201.8 | 508.5 | 23.11 | 0.0 | 9.74 | 13.91 | 19.82 | Au1rxx-base64 | 173.244.56.6 |
| 78.21 | trojan | 269.0 | 548.1 | 21.55 | 0.0 | 9.16 | 14.44 | 19.82 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 78.21 | trojan | 282.9 | 628.5 | 21.23 | 0.0 | 9.95 | 14.44 | 19.82 | Au1rxx-base64 | 64.94.95.117 |
| 78.09 | trojan | 293.7 | 525.9 | 20.98 | 0.0 | 9.95 | 14.44 | 19.82 | Au1rxx-base64 | 35.91.251.124 |
| 78.04 | trojan | 281.6 | 586.6 | 21.26 | 0.0 | 9.64 | 14.44 | 19.82 | Au1rxx-base64 | 44.242.235.129 |
| 77.97 | vless | 209.6 | 472.6 | 22.93 | 0.0 | 10.0 | 9.76 | 19.82 | Au1rxx-base64 | 70.39.198.183 |
| 77.89 | trojan | 326.2 | 719.0 | 20.23 | 0.0 | 9.19 | 14.44 | 19.82 | Au1rxx-base64 | pet-ghost.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.94 | 400 | 1563 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.52 | 0.439 | 82 | 5930 | observe |
| mheidari-all | 0.457 | 0.373 | 75 | 20396 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5260 | observe |
| Epodonios-all | 0.255 | None | 0 | 6540 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7160 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4758 | observe |
| barry-far-vless | 0.255 | None | 0 | 5072 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5206 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 4655 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.239 | None | 0 | 1594 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 35 |
| geo | ClientOSError | - | 31 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 4 |
| speed | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
