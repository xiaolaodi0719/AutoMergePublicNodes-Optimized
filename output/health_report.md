# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 13:21:28 |
| 运行耗时 | 283.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81447 |
| 去重后节点 | 23220 |
| TCP 可达 | 3000 |
| 真实可用 | 853 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23220 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.1 |
| tcp | 36.2 |
| probe | 59.1 |
| real_test | 149.6 |
| generate | 32.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44632 |
| vmess | 13653 |
| trojan | 11962 |
| shadowsocks | 9853 |
| hysteria2 | 1026 |
| http | 156 |
| socks | 76 |
| shadowsocksr | 70 |
| tuic | 10 |
| hysteria | 7 |
| anytls | 2 |

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
| 83.96 | hysteria2 | 247.5 | 505.1 | 22.05 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 150.241.102.127 |
| 82.56 | http | 245.7 | 545.0 | 22.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 82.42 | http | 249.5 | 554.3 | 22.0 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 82.25 | http | 246.4 | 556.7 | 22.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 82.24 | http | 256.1 | 577.5 | 21.85 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 82.16 | http | 245.0 | 544.2 | 22.11 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 82.15 | http | 255.8 | 547.9 | 21.86 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 82.12 | http | 256.7 | 579.0 | 21.84 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 82.1 | http | 256.5 | 569.3 | 21.84 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 82.07 | shadowsocks | 240.4 | 613.8 | 22.21 | 0.0 | 10.0 | 13.86 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 82.0 | http | 270.7 | 619.9 | 21.51 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 81.86 | http | 249.2 | 554.5 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 81.77 | http | 243.3 | 542.6 | 22.14 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 81.67 | http | 251.7 | 565.1 | 21.95 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 81.67 | http | 262.5 | 593.8 | 21.7 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 81.37 | http | 254.4 | 563.2 | 21.89 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 80.98 | shadowsocks | 287.7 | 744.8 | 21.12 | 0.0 | 10.0 | 13.86 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 80.87 | hysteria2 | 315.4 | 736.9 | 20.48 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 79.62 | hysteria2 | 337.4 | 749.6 | 19.97 | 0.0 | 10.0 | 14.12 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 79.4 | trojan | 281.5 | 571.4 | 21.26 | 0.0 | 10.0 | 14.39 | 20.0 | Au1rxx-base64 | 44.246.163.102 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.931 | 651 | 1959 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.937 | 0.875 | 40 | 17030 | prefer |
| Surfboard-tg-mixed | 0.771 | 0.695 | 95 | 5728 | prefer |
| DeltaKronecker-all | 0.674 | 0.6 | 30 | 5969 | observe |
| nscl5-all | 0.326 | 1.0 | 1 | 1768 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5157 | observe |
| Epodonios-all | 0.255 | None | 0 | 6515 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7682 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4474 | observe |
| barry-far-vless | 0.255 | None | 0 | 4931 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5332 | observe |
| Au1rxx-clash | 0.253 | None | 0 | 1959 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 22 |
| speed | ClientOSError | - | 16 |
| speed | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| geo | TimeoutError | - | 11 |
| geo | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
