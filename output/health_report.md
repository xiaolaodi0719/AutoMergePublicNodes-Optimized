# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 03:33:30 |
| 运行耗时 | 324.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81081 |
| 去重后节点 | 22635 |
| TCP 可达 | 3000 |
| 真实可用 | 852 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22635 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 35.0 |
| probe | 59.7 |
| real_test | 190.4 |
| generate | 32.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49594 |
| vmess | 12591 |
| shadowsocks | 10270 |
| trojan | 7554 |
| hysteria2 | 727 |
| http | 176 |
| shadowsocksr | 76 |
| socks | 69 |
| hysteria | 12 |
| anytls | 7 |
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
| 85.31 | http | 188.7 | 486.2 | 23.41 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.217 |
| 85.19 | http | 193.7 | 495.6 | 23.29 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.210 |
| 85.14 | http | 195.8 | 500.2 | 23.24 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.211 |
| 85.13 | http | 196.3 | 498.5 | 23.23 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.212 |
| 85.1 | http | 197.8 | 501.5 | 23.2 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.200 |
| 85.08 | http | 198.7 | 504.7 | 23.18 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.204 |
| 85.06 | http | 199.3 | 514.8 | 23.16 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.214 |
| 85.01 | http | 201.8 | 520.5 | 23.11 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.206 |
| 84.8 | http | 210.5 | 547.3 | 22.9 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.209 |
| 84.58 | http | 220.2 | 570.5 | 22.68 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.202 |
| 84.57 | http | 220.6 | 579.7 | 22.67 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 84.51 | http | 223.2 | 535.1 | 22.61 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.205 |
| 83.98 | http | 197.0 | 491.8 | 23.22 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |
| 83.76 | http | 255.7 | 652.1 | 21.86 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.220 |
| 78.74 | http | 472.5 | 1336.0 | 16.84 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.198 |
| 78.54 | http | 481.0 | 1358.3 | 16.64 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.215 |
| 78.54 | http | 481.1 | 1363.3 | 16.64 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.208 |
| 78.54 | http | 481.3 | 1355.7 | 16.64 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.207 |
| 78.53 | http | 481.5 | 1345.7 | 16.63 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.218 |
| 78.47 | http | 484.0 | 1363.2 | 16.57 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.195 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 144 | 344 | prefer |
| Au1rxx-base64 | 0.894 | 0.829 | 598 | 1632 | prefer |
| Surfboard-tg-mixed | 0.619 | 0.54 | 87 | 5182 | observe |
| DeltaKronecker-all | 0.61 | 0.53 | 283 | 3437 | observe |
| mheidari-all | 0.373 | 0.282 | 39 | 18808 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 56 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5849 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6871 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4109 | observe |
| barry-far-vless | 0.255 | None | 0 | 4560 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5208 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 96 |
| geo | TimeoutError | - | 92 |
| speed | TimeoutError | - | 54 |
| speed | ClientOSError | - | 29 |
| geo | ClientOSError | - | 15 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
