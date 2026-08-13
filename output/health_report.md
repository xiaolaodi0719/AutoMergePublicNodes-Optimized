# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 07:46:53 |
| 运行耗时 | 323.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79301 |
| 去重后节点 | 22373 |
| TCP 可达 | 3000 |
| 真实可用 | 733 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22373 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.3 |
| geo | 1.2 |
| tcp | 33.2 |
| probe | 60.2 |
| real_test | 181.7 |
| generate | 35.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44303 |
| vmess | 13367 |
| trojan | 10432 |
| shadowsocks | 9733 |
| hysteria2 | 1136 |
| http | 160 |
| socks | 77 |
| shadowsocksr | 74 |
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
| 85.11 | http | 195.5 | 515.0 | 23.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 85.11 | http | 195.6 | 511.7 | 23.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.06 | http | 197.5 | 504.2 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 85.06 | http | 197.9 | 517.8 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.01 | http | 199.8 | 519.2 | 23.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 84.98 | http | 201.0 | 523.3 | 23.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 84.98 | http | 201.1 | 521.4 | 23.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 84.97 | http | 201.7 | 522.0 | 23.11 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 84.96 | http | 202.2 | 523.9 | 23.1 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 84.91 | http | 204.1 | 528.8 | 23.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.89 | http | 204.9 | 527.3 | 23.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.89 | http | 204.9 | 533.6 | 23.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 84.88 | http | 205.4 | 535.0 | 23.02 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 84.83 | http | 207.6 | 544.0 | 22.97 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 81.87 | shadowsocks | 189.8 | 464.5 | 23.38 | 0.0 | 10.0 | 14.05 | 18.94 | Au1rxx-base64 | 108.181.0.177 |
| 80.78 | shadowsocks | 258.5 | 620.0 | 21.79 | 0.0 | 10.0 | 14.05 | 18.94 | Au1rxx-base64 | 173.244.56.6 |
| 79.58 | shadowsocks | 193.3 | 459.6 | 23.3 | 0.0 | 10.0 | 14.05 | 18.94 | Au1rxx-base64 | 108.181.118.10 |
| 79.34 | shadowsocks | 320.7 | 815.8 | 20.35 | 0.0 | 10.0 | 14.05 | 18.94 | Au1rxx-base64 | 156.146.38.168 |
| 78.74 | shadowsocks | 260.3 | 633.7 | 21.75 | 0.0 | 10.0 | 14.05 | 18.94 | Au1rxx-base64 | 173.244.56.9 |
| 77.55 | trojan | 278.2 | 588.2 | 21.34 | 0.0 | 10.0 | 12.91 | 18.94 | Au1rxx-base64 | 44.244.3.114 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.954 | 461 | 1501 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Surfboard-tg-mixed | 0.792 | 0.715 | 137 | 5801 | prefer |
| mheidari-all | 0.55 | 0.469 | 113 | 16910 | observe |
| DeltaKronecker-all | 0.405 | 0.316 | 38 | 4975 | observe |
| nscl5-all | 0.377 | 1.0 | 2 | 1654 | observe |
| Epodonios-all | 0.255 | None | 0 | 6457 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7624 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4621 | observe |
| barry-far-vless | 0.255 | None | 0 | 4989 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1501 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 45 |
| speed | TimeoutError | - | 26 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 7 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
