# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 02:26:16 |
| 运行耗时 | 339.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79423 |
| 去重后节点 | 21337 |
| TCP 可达 | 3000 |
| 真实可用 | 993 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21337 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.3 |
| tcp | 33.6 |
| probe | 61.4 |
| real_test | 209.5 |
| generate | 28.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43960 |
| vmess | 13622 |
| trojan | 10757 |
| shadowsocks | 9705 |
| hysteria2 | 1066 |
| http | 149 |
| socks | 80 |
| shadowsocksr | 68 |
| tuic | 8 |
| hysteria | 7 |
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
| 84.94 | trojan | 219.0 | 528.6 | 22.71 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 44.242.235.129 |
| 83.95 | trojan | 261.6 | 472.8 | 21.72 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 44.244.3.114 |
| 83.87 | trojan | 265.1 | 667.2 | 21.64 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 44.246.163.102 |
| 82.96 | vless | 235.5 | 511.3 | 22.33 | 0.0 | 10.0 | 11.65 | 19.96 | Au1rxx-base64 | 66.175.217.170 |
| 82.23 | trojan | 206.5 | 490.7 | 23.0 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 44.243.85.47 |
| 81.9 | trojan | 270.1 | 669.5 | 21.53 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 35.86.90.51 |
| 81.53 | trojan | 236.6 | 581.5 | 22.3 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 54.188.176.255 |
| 81.38 | trojan | 215.0 | 523.1 | 22.8 | 0.0 | 6.35 | 14.77 | 19.96 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 80.97 | vless | 250.6 | 539.9 | 21.98 | 0.0 | 10.0 | 11.65 | 19.96 | Au1rxx-base64 | 179.253.240.24 |
| 80.58 | trojan | 277.7 | 708.9 | 21.35 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 35.88.210.26 |
| 80.47 | vless | 246.8 | 499.5 | 22.06 | 0.0 | 10.0 | 11.65 | 19.96 | Au1rxx-base64 | 70.39.198.183 |
| 80.35 | trojan | 220.6 | 539.4 | 22.67 | 0.0 | 7.45 | 14.77 | 19.96 | Au1rxx-base64 | dear-hermit.rooster465.autos |
| 80.26 | vless | 234.7 | 203.5 | 22.34 | 7.37 | 10.0 | 11.65 | 19.96 | Au1rxx-base64 | 35.77.70.195 |
| 80.21 | trojan | 257.3 | 642.3 | 21.82 | 0.0 | 6.16 | 14.77 | 19.96 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 80.05 | shadowsocks | 213.8 | 553.4 | 22.83 | 0.0 | 10.0 | 13.62 | 17.6 | mheidari-all | 149.22.95.183 |
| 79.04 | trojan | 257.6 | 649.2 | 21.81 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 35.88.120.18 |
| 78.91 | trojan | 263.4 | 667.4 | 21.68 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 54.245.126.186 |
| 78.9 | trojan | 264.0 | 669.6 | 21.67 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 35.160.249.189 |
| 78.73 | trojan | 271.2 | 687.3 | 21.5 | 0.0 | 10.0 | 14.77 | 19.96 | Au1rxx-base64 | 100.22.163.167 |
| 78.52 | trojan | 319.6 | 310.6 | 20.38 | 3.35 | 9.99 | 14.77 | 19.96 | Au1rxx-base64 | 18.181.194.227 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.945 | 712 | 1965 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Surfboard-tg-mixed | 0.92 | 0.846 | 104 | 5918 | prefer |
| DeltaKronecker-all | 0.863 | 0.795 | 44 | 3656 | prefer |
| mheidari-all | 0.464 | 0.382 | 170 | 16929 | observe |
| 10ium-ScrapeCategorize-Vless | 0.352 | 0.5 | 6 | 5203 | observe |
| nscl5-all | 0.278 | 0.5 | 2 | 1768 | observe |
| Epodonios-all | 0.255 | None | 0 | 6600 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7655 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4638 | observe |
| barry-far-vless | 0.255 | None | 0 | 5003 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| Au1rxx-clash | 0.254 | None | 0 | 1965 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 49 |
| speed | TimeoutError | - | 42 |
| cn-block | TimeoutError | - | 27 |
| geo | ClientOSError | - | 17 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
