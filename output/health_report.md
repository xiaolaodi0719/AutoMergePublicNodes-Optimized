# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 13:01:37 |
| 运行耗时 | 236.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83600 |
| 去重后节点 | 23665 |
| TCP 可达 | 3000 |
| 真实可用 | 404 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23665 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.3 |
| tcp | 35.5 |
| probe | 49.6 |
| real_test | 95.0 |
| generate | 48.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49034 |
| vmess | 12921 |
| trojan | 10527 |
| shadowsocks | 9607 |
| hysteria2 | 1313 |
| shadowsocksr | 75 |
| socks | 63 |
| http | 36 |
| hysteria | 13 |
| tuic | 10 |
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
| 84.67 | trojan | 200.0 | 476.6 | 23.15 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 82.95 | shadowsocks | 186.8 | 496.1 | 23.45 | 0.0 | 10.0 | 13.5 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.65 | trojan | 287.3 | 736.3 | 21.13 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 82.56 | trojan | 291.0 | 752.8 | 21.04 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 82.3 | trojan | 302.5 | 782.6 | 20.78 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 44.242.235.129 |
| 79.77 | trojan | 193.0 | 458.0 | 23.31 | 0.0 | 4.94 | 14.02 | 20.0 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 79.37 | trojan | 213.7 | 523.0 | 22.83 | 0.0 | 5.02 | 14.02 | 20.0 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 79.12 | http | 256.7 | 543.1 | 21.84 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 79.03 | http | 254.9 | 541.8 | 21.88 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 78.98 | trojan | 313.5 | 807.3 | 20.52 | 0.0 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 78.81 | hysteria2 | 331.0 | 726.7 | 20.12 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 78.77 | http | 260.9 | 560.8 | 21.74 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 78.48 | http | 287.3 | 634.0 | 21.13 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 78.07 | trojan | 346.4 | 288.2 | 19.76 | 4.19 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 43.207.89.29 |
| 77.87 | trojan | 354.2 | 287.9 | 19.58 | 4.2 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 43.207.140.98 |
| 77.77 | hysteria2 | 351.6 | 742.2 | 19.64 | 0.0 | 10.0 | 13.33 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 77.75 | trojan | 310.2 | 318.7 | 20.6 | 3.05 | 9.99 | 14.02 | 20.0 | Au1rxx-base64 | 57.180.27.225 |
| 77.7 | trojan | 311.8 | 319.6 | 20.56 | 3.02 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 52.196.121.8 |
| 77.7 | trojan | 313.2 | 319.9 | 20.53 | 3.01 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 18.181.164.216 |
| 77.7 | trojan | 316.8 | 316.6 | 20.45 | 3.13 | 10.0 | 14.02 | 20.0 | Au1rxx-base64 | 3.112.238.99 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.947 | 341 | 1488 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.68 | 0.603 | 78 | 6570 | observe |
| mheidari-all | 0.461 | 0.545 | 11 | 17827 | observe |
| DeltaKronecker-all | 0.376 | 0.28 | 25 | 5347 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5450 | observe |
| Epodonios-all | 0.255 | None | 0 | 7203 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7636 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5374 | observe |
| barry-far-vless | 0.255 | None | 0 | 5686 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5162 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.241 | None | 0 | 1643 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 13 |
| speed | TimeoutError | - | 8 |
| geo | ClientOSError | - | 6 |
| 204 | ProxyError | - | 6 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
