# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 02:25:52 |
| 运行耗时 | 289.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 80730 |
| 去重后节点 | 22951 |
| TCP 可达 | 3000 |
| 真实可用 | 702 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22951 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.2 |
| tcp | 34.5 |
| probe | 58.7 |
| real_test | 166.3 |
| generate | 24.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46023 |
| vmess | 13158 |
| trojan | 10399 |
| shadowsocks | 9621 |
| hysteria2 | 1203 |
| http | 159 |
| shadowsocksr | 75 |
| socks | 67 |
| tuic | 15 |
| hysteria | 10 |

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
| 85.15 | http | 193.7 | 491.5 | 23.29 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.11 | http | 195.7 | 486.9 | 23.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.09 | http | 196.5 | 505.9 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.09 | http | 196.6 | 506.8 | 23.23 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 85.08 | http | 196.8 | 501.1 | 23.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.08 | http | 196.8 | 506.8 | 23.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.03 | http | 199.3 | 509.1 | 23.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 84.99 | http | 200.7 | 515.7 | 23.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.97 | http | 201.5 | 504.2 | 23.11 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 84.93 | http | 203.5 | 516.4 | 23.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 84.93 | http | 203.5 | 535.1 | 23.07 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.87 | http | 205.9 | 522.1 | 23.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 84.85 | http | 206.9 | 519.6 | 22.99 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 84.46 | http | 223.7 | 590.9 | 22.6 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 83.23 | vless | 188.0 | 482.0 | 23.43 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 179.255.148.66 |
| 83.09 | vless | 193.8 | 491.6 | 23.29 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 179.253.240.24 |
| 82.91 | vless | 186.8 | 466.0 | 23.45 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 70.39.198.183 |
| 81.48 | vless | 263.4 | 617.7 | 21.68 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 70.39.178.231 |
| 80.89 | vless | 288.7 | 779.7 | 21.09 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 107.173.237.146 |
| 80.85 | vless | 290.5 | 721.3 | 21.05 | 0.0 | 10.0 | 10.86 | 18.94 | Au1rxx-base64 | 186.241.106.97 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.914 | 0.849 | 451 | 1650 | prefer |
| Surfboard-tg-mixed | 0.749 | 0.671 | 161 | 5950 | prefer |
| mheidari-all | 0.452 | 0.37 | 189 | 16697 | observe |
| nscl5-all | 0.314 | 1.0 | 1 | 1481 | observe |
| Epodonios-all | 0.255 | None | 0 | 6635 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7586 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4851 | observe |
| barry-far-vless | 0.255 | None | 0 | 5220 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1650 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| DeltaKronecker-all | 0.217 | 0.129 | 93 | 5522 | downweight |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 97 |
| speed | TimeoutError | - | 70 |
| geo | ClientOSError | - | 55 |
| cn-block | TimeoutError | - | 38 |
| speed | ClientOSError | - | 28 |
| 204 | TimeoutError | - | 16 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
