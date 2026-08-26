# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 01:46:03 |
| 运行耗时 | 379.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 79196 |
| 去重后节点 | 22564 |
| TCP 可达 | 3000 |
| 真实可用 | 753 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22564 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 36.3 |
| probe | 74.6 |
| real_test | 219.2 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49697 |
| shadowsocks | 10719 |
| vmess | 10475 |
| trojan | 6549 |
| hysteria2 | 1387 |
| http | 167 |
| shadowsocksr | 124 |
| socks | 68 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.98 | http | 195.3 | 499.3 | 23.26 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 83.86 | http | 200.2 | 511.2 | 23.14 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 82.79 | trojan | 194.4 | 499.0 | 23.28 | 0.0 | 10.0 | 14.21 | 18.3 | Au1rxx-base64 | 14.1.28.76 |
| 81.29 | trojan | 215.7 | 550.7 | 22.78 | 0.0 | 10.0 | 14.21 | 18.3 | Au1rxx-base64 | us01.duotg.top |
| 79.84 | shadowsocks | 255.2 | 628.3 | 21.87 | 0.0 | 10.0 | 13.67 | 18.3 | Au1rxx-base64 | 156.146.38.170 |
| 79.14 | vless | 214.8 | 557.5 | 22.8 | 0.0 | 10.0 | 10.92 | 17.42 | DeltaKronecker-all | 166.88.186.151 |
| 78.59 | vless | 290.2 | 671.3 | 21.06 | 0.0 | 10.0 | 10.92 | 18.3 | Au1rxx-base64 | 15.204.97.216 |
| 78.45 | vless | 291.5 | 676.7 | 21.03 | 0.0 | 10.0 | 10.92 | 18.3 | Au1rxx-base64 | 15.204.97.195 |
| 78.44 | shadowsocks | 253.6 | 619.2 | 21.91 | 0.0 | 10.0 | 13.67 | 18.3 | Au1rxx-base64 | 156.146.38.167 |
| 78.36 | vless | 270.9 | 610.1 | 21.51 | 0.0 | 10.0 | 10.92 | 17.42 | DeltaKronecker-all | 15.204.97.209 |
| 78.16 | vless | 235.6 | 612.7 | 22.32 | 0.0 | 10.0 | 10.92 | 18.3 | Au1rxx-base64 | 69.63.193.78 |
| 78.15 | hysteria2 | 340.5 | 753.6 | 19.9 | 0.0 | 10.0 | 14.4 | 18.3 | Au1rxx-base64 | 159.223.157.129 |
| 77.72 | shadowsocks | 209.2 | 499.3 | 22.93 | 0.0 | 10.0 | 13.67 | 15.62 | Surfboard-tg-mixed | 108.181.0.177 |
| 77.7 | shadowsocks | 204.3 | 476.2 | 23.05 | 0.0 | 10.0 | 13.67 | 15.48 | mheidari-all | 108.181.118.10 |
| 77.61 | shadowsocks | 229.8 | 511.1 | 22.46 | 0.0 | 10.0 | 13.67 | 15.48 | mheidari-all | 173.244.56.6 |
| 77.51 | trojan | 206.3 | 535.0 | 23.0 | 0.0 | 10.0 | 14.21 | 18.3 | Au1rxx-base64 | 107.150.105.84 |
| 76.91 | trojan | 361.9 | 850.5 | 19.4 | 0.0 | 10.0 | 14.21 | 17.42 | DeltaKronecker-all | 69.164.205.61 |
| 76.83 | shadowsocks | 255.4 | 572.5 | 21.87 | 0.0 | 10.0 | 13.67 | 18.3 | Au1rxx-base64 | 154.12.240.141 |
| 76.67 | trojan | 285.0 | 556.6 | 21.18 | 0.0 | 10.0 | 14.21 | 18.3 | Au1rxx-base64 | 35.91.251.124 |
| 76.17 | shadowsocks | 291.8 | 705.7 | 21.02 | 0.0 | 10.0 | 13.67 | 15.48 | mheidari-all | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | 0.895 | 475 | 1944 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.92 | 0.87 | 23 | 6470 | prefer |
| mheidari-all | 0.523 | 0.533 | 15 | 14587 | observe |
| DeltaKronecker-all | 0.395 | 0.314 | 875 | 6340 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 191 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 7017 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7048 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5307 | observe |
| barry-far-vless | 0.255 | None | 0 | 5579 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| Au1rxx-clash | 0.253 | None | 0 | 1946 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 362 |
| speed | ClientOSError | - | 121 |
| geo | ClientOSError | - | 81 |
| speed | TimeoutError | - | 37 |
| cn-block | TimeoutError | - | 20 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 4 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
