# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-13 13:27:10 |
| 运行耗时 | 318.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79794 |
| 去重后节点 | 22452 |
| TCP 可达 | 3000 |
| 真实可用 | 781 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22452 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.3 |
| geo | 1.1 |
| tcp | 32.8 |
| probe | 59.6 |
| real_test | 188.6 |
| generate | 25.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43806 |
| vmess | 13394 |
| trojan | 11261 |
| shadowsocks | 9866 |
| hysteria2 | 1141 |
| http | 160 |
| socks | 77 |
| shadowsocksr | 72 |
| tuic | 8 |
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
| 85.18 | http | 192.7 | 498.2 | 23.32 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 85.07 | http | 197.2 | 516.2 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 85.06 | http | 197.7 | 514.9 | 23.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 84.95 | http | 202.4 | 528.4 | 23.09 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 84.8 | http | 208.9 | 538.9 | 22.94 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 84.74 | http | 211.7 | 554.7 | 22.88 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 84.55 | http | 219.8 | 579.6 | 22.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 84.55 | http | 220.0 | 581.9 | 22.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 84.54 | http | 220.1 | 574.3 | 22.68 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 84.43 | http | 224.9 | 598.2 | 22.57 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 84.33 | trojan | 229.1 | 515.2 | 22.47 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 84.25 | http | 232.7 | 617.3 | 22.39 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 84.17 | http | 236.2 | 620.8 | 22.31 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 84.07 | http | 240.5 | 641.7 | 22.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 83.87 | http | 249.0 | 660.4 | 22.01 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 82.62 | shadowsocks | 188.6 | 462.4 | 23.41 | 0.0 | 10.0 | 13.71 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.98 | vless | 224.3 | 628.1 | 22.58 | 0.0 | 10.0 | 9.4 | 20.0 | Au1rxx-base64 | 66.175.217.170 |
| 81.62 | shadowsocks | 253.4 | 544.5 | 21.91 | 0.0 | 10.0 | 13.71 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 81.47 | trojan | 338.9 | 708.9 | 19.93 | 0.0 | 10.0 | 14.36 | 20.0 | Au1rxx-base64 | 44.246.163.102 |
| 80.06 | shadowsocks | 320.9 | 769.4 | 20.35 | 0.0 | 10.0 | 13.71 | 20.0 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.957 | 541 | 1591 | prefer |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.739 | 115 | 5967 | prefer |
| mheidari-all | 0.655 | 0.577 | 78 | 17032 | observe |
| DeltaKronecker-all | 0.291 | 0.25 | 12 | 4878 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5203 | observe |
| Epodonios-all | 0.255 | None | 0 | 6610 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7410 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4695 | observe |
| barry-far-vless | 0.255 | None | 0 | 5031 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5197 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 17 |
| geo | TimeoutError | - | 15 |
| speed | TimeoutError | - | 10 |
| geo | ClientOSError | - | 9 |
| 204 | ProxyError | - | 9 |
| speed | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
