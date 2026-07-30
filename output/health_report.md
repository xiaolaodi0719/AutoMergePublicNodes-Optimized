# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 14:18:30 |
| 运行耗时 | 246.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78835 |
| 去重后节点 | 22975 |
| TCP 可达 | 3000 |
| 真实可用 | 442 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22975 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.4 |
| tcp | 32.4 |
| probe | 53.2 |
| real_test | 108.5 |
| generate | 43.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46027 |
| vmess | 11321 |
| shadowsocks | 10321 |
| trojan | 10267 |
| hysteria2 | 587 |
| http | 116 |
| shadowsocksr | 77 |
| socks | 59 |
| anytls | 26 |
| tuic | 20 |
| hysteria | 14 |

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
| 80.9 | http | 290.3 | 761.5 | 21.06 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.196 |
| 79.21 | shadowsocks | 190.6 | 471.7 | 23.37 | 0.0 | 10.0 | 12.5 | 17.84 | Au1rxx-base64 | 108.181.118.10 |
| 79.07 | shadowsocks | 196.6 | 480.4 | 23.23 | 0.0 | 10.0 | 12.5 | 17.84 | Au1rxx-base64 | 108.181.0.177 |
| 78.94 | shadowsocks | 223.6 | 533.3 | 22.6 | 0.0 | 10.0 | 12.5 | 17.84 | Au1rxx-base64 | 173.244.56.9 |
| 78.45 | shadowsocks | 244.9 | 606.7 | 22.11 | 0.0 | 10.0 | 12.5 | 17.84 | Au1rxx-base64 | 173.244.56.6 |
| 78.2 | http | 277.3 | 745.2 | 21.36 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.215 |
| 78.18 | http | 278.2 | 749.9 | 21.34 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.206 |
| 78.14 | http | 280.0 | 744.1 | 21.3 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.213 |
| 77.97 | http | 287.0 | 749.7 | 21.13 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.199 |
| 77.94 | http | 288.4 | 756.8 | 21.1 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.210 |
| 77.92 | http | 289.3 | 764.2 | 21.08 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.217 |
| 77.92 | http | 289.3 | 763.0 | 21.08 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.220 |
| 77.88 | http | 290.9 | 765.1 | 21.04 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.218 |
| 77.88 | http | 291.1 | 768.5 | 21.04 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.197 |
| 77.85 | http | 292.2 | 776.7 | 21.01 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.208 |
| 77.85 | http | 292.4 | 776.4 | 21.01 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.211 |
| 77.8 | http | 294.7 | 757.1 | 20.96 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.202 |
| 77.72 | http | 297.9 | 776.6 | 20.88 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.207 |
| 77.66 | http | 300.7 | 783.2 | 20.82 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.204 |
| 77.65 | http | 300.9 | 792.4 | 20.81 | 0.0 | 10.0 | 14.88 | 19.96 | zhangkai | 138.199.35.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.889 | 0.833 | 275 | 1460 | prefer |
| DeltaKronecker-all | 0.822 | 0.759 | 29 | 5759 | prefer |
| mheidari-all | 0.734 | 0.667 | 24 | 16526 | prefer |
| Surfboard-tg-mixed | 0.663 | 0.584 | 101 | 5443 | observe |
| Surfboard-tg-vless | 0.335 | 1.0 | 1 | 4288 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6193 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6515 | observe |
| barry-far-vless | 0.255 | None | 0 | 4667 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5029 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 25 |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 10 |
| geo | ClientOSError | - | 9 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
