# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-15 18:41:52 |
| 运行耗时 | 335.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 78636 |
| 去重后节点 | 22463 |
| TCP 可达 | 3000 |
| 真实可用 | 1052 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22463 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.9 |
| geo | 0.9 |
| tcp | 33.8 |
| probe | 70.3 |
| real_test | 188.7 |
| generate | 32.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43064 |
| trojan | 13402 |
| vmess | 10700 |
| shadowsocks | 10037 |
| hysteria2 | 1069 |
| http | 189 |
| socks | 82 |
| shadowsocksr | 76 |
| tuic | 10 |
| hysteria | 7 |

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
| 85.06 | hysteria2 | 229.2 | 543.5 | 22.47 | 0.0 | 9.34 | 14.25 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 84.3 | trojan | 241.0 | 560.0 | 22.2 | 0.0 | 10.0 | 14.6 | 20.0 | Au1rxx-base64 | 35.88.120.18 |
| 84.28 | trojan | 241.8 | 562.3 | 22.18 | 0.0 | 10.0 | 14.6 | 20.0 | Au1rxx-base64 | 35.88.210.26 |
| 83.65 | trojan | 248.1 | 578.5 | 22.03 | 0.0 | 9.52 | 14.6 | 20.0 | Au1rxx-base64 | 54.245.126.186 |
| 83.57 | trojan | 235.6 | 535.5 | 22.33 | 0.0 | 9.52 | 14.6 | 20.0 | Au1rxx-base64 | 54.244.169.225 |
| 82.8 | vless | 251.6 | 675.5 | 21.95 | 0.0 | 9.33 | 11.52 | 20.0 | Au1rxx-base64 | 70.39.198.183 |
| 82.74 | trojan | 290.7 | 704.2 | 21.05 | 0.0 | 10.0 | 14.6 | 20.0 | Au1rxx-base64 | 100.22.163.167 |
| 82.73 | trojan | 232.4 | 536.2 | 22.4 | 0.0 | 8.23 | 14.6 | 20.0 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 82.57 | trojan | 238.2 | 536.2 | 22.26 | 0.0 | 8.35 | 14.6 | 20.0 | Au1rxx-base64 | arriving-colt.rooster465.autos |
| 82.55 | trojan | 230.5 | 511.6 | 22.44 | 0.0 | 9.51 | 14.6 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 82.53 | trojan | 247.4 | 580.3 | 22.05 | 0.0 | 8.38 | 14.6 | 20.0 | Au1rxx-base64 | moral-cow.rooster465.autos |
| 82.49 | trojan | 254.8 | 593.6 | 21.88 | 0.0 | 9.5 | 14.6 | 20.0 | Au1rxx-base64 | 54.188.176.255 |
| 82.47 | vless | 266.0 | 706.1 | 21.62 | 0.0 | 9.33 | 11.52 | 20.0 | Au1rxx-base64 | 70.39.197.13 |
| 82.44 | trojan | 241.3 | 540.5 | 22.19 | 0.0 | 8.15 | 14.6 | 20.0 | Au1rxx-base64 | liked-serval.rooster465.autos |
| 82.28 | trojan | 243.8 | 542.8 | 22.13 | 0.0 | 9.52 | 14.6 | 20.0 | Au1rxx-base64 | 44.243.85.47 |
| 82.2 | trojan | 241.9 | 557.7 | 22.18 | 0.0 | 10.0 | 14.6 | 20.0 | mheidari-all | 35.92.245.6 |
| 81.99 | trojan | 264.0 | 629.9 | 21.67 | 0.0 | 8.22 | 14.6 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 81.77 | trojan | 236.3 | 547.1 | 22.31 | 0.0 | 7.36 | 14.6 | 20.0 | Au1rxx-base64 | bright-baboon.rooster465.autos |
| 81.65 | trojan | 243.1 | 566.2 | 22.15 | 0.0 | 7.4 | 14.6 | 20.0 | Au1rxx-base64 | dear-hermit.rooster465.autos |
| 81.42 | shadowsocks | 226.1 | 535.8 | 22.54 | 0.0 | 10.0 | 12.88 | 20.0 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.96 | 693 | 1997 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.93 | 0.854 | 198 | 16339 | prefer |
| Surfboard-tg-mixed | 0.882 | 0.808 | 104 | 5684 | prefer |
| nscl5-all | 0.438 | 1.0 | 3 | 2081 | observe |
| Surfboard-tg-vless | 0.335 | 1.0 | 1 | 4350 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 160 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5113 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1997 | observe |
| Epodonios-all | 0.255 | None | 0 | 6266 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7464 | observe |
| barry-far-vless | 0.255 | None | 0 | 4694 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3935 | observe |
| DeltaKronecker-all | 0.249 | 0.2 | 10 | 5773 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 14 |
| speed | TimeoutError | - | 13 |
| geo | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 6 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
