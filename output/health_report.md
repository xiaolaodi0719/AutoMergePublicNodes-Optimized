# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-18 01:33:02 |
| 运行耗时 | 351.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 80389 |
| 去重后节点 | 22945 |
| TCP 可达 | 3000 |
| 真实可用 | 1290 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22945 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 35.7 |
| probe | 68.3 |
| real_test | 212.3 |
| generate | 27.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45541 |
| trojan | 13650 |
| shadowsocks | 10079 |
| vmess | 8511 |
| hysteria2 | 2187 |
| http | 193 |
| socks | 123 |
| shadowsocksr | 81 |
| tuic | 15 |
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
| 85.29 | http | 187.8 | 487.8 | 23.43 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 85.27 | http | 188.8 | 482.9 | 23.41 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 85.23 | http | 190.5 | 492.6 | 23.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 85.22 | http | 190.7 | 485.3 | 23.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.211 |
| 85.19 | http | 191.9 | 494.8 | 23.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 85.19 | http | 192.0 | 493.8 | 23.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 85.19 | http | 192.2 | 499.0 | 23.33 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 85.14 | http | 194.3 | 503.8 | 23.28 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 85.12 | http | 195.3 | 505.4 | 23.26 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 85.08 | http | 196.8 | 507.3 | 23.22 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 85.07 | http | 197.3 | 499.7 | 23.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 85.05 | http | 198.0 | 513.6 | 23.19 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.215 |
| 84.99 | http | 200.7 | 513.5 | 23.13 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 84.98 | http | 201.2 | 501.3 | 23.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 81.4 | shadowsocks | 190.4 | 461.1 | 23.37 | 0.0 | 10.0 | 13.11 | 19.42 | Au1rxx-base64 | 108.181.0.177 |
| 81.19 | shadowsocks | 199.5 | 463.1 | 23.16 | 0.0 | 10.0 | 13.11 | 19.42 | Au1rxx-base64 | 108.181.118.10 |
| 80.63 | trojan | 271.9 | 563.2 | 21.48 | 0.0 | 10.0 | 14.87 | 20.0 | mheidari-all | 44.247.89.62 |
| 80.51 | trojan | 272.0 | 556.0 | 21.48 | 0.0 | 10.0 | 14.87 | 20.0 | mheidari-all | 44.246.163.102 |
| 80.33 | trojan | 281.3 | 588.5 | 21.27 | 0.0 | 10.0 | 14.87 | 20.0 | mheidari-all | 54.245.126.186 |
| 80.14 | trojan | 278.6 | 583.7 | 21.33 | 0.0 | 10.0 | 14.87 | 20.0 | mheidari-all | 54.185.164.73 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.966 | 526 | 1475 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| mheidari-all | 0.941 | 0.862 | 669 | 16056 | prefer |
| Surfboard-tg-mixed | 0.747 | 0.67 | 94 | 6128 | prefer |
| DeltaKronecker-all | 0.297 | 0.207 | 58 | 6368 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 179 | observe |
| Pawdroid | 0.256 | 1.0 | 1 | 20 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5085 | observe |
| Epodonios-all | 0.255 | None | 0 | 6777 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6971 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4797 | observe |
| barry-far-vless | 0.255 | None | 0 | 5128 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4027 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 74 |
| speed | TimeoutError | - | 42 |
| geo | ClientOSError | - | 23 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
