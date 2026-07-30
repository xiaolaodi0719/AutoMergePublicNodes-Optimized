# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-30 19:45:47 |
| 运行耗时 | 314.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78433 |
| 去重后节点 | 23046 |
| TCP 可达 | 3000 |
| 真实可用 | 529 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23046 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 33.3 |
| probe | 64.3 |
| real_test | 162.0 |
| generate | 47.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45636 |
| vmess | 11424 |
| shadowsocks | 10249 |
| trojan | 10213 |
| hysteria2 | 606 |
| http | 116 |
| shadowsocksr | 73 |
| socks | 56 |
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
| 79.19 | shadowsocks | 218.2 | 521.0 | 22.73 | 0.0 | 10.0 | 12.68 | 17.78 | Au1rxx-base64 | 173.244.56.6 |
| 79.15 | shadowsocks | 198.2 | 488.7 | 23.19 | 0.0 | 10.0 | 12.68 | 17.78 | Au1rxx-base64 | 108.181.0.177 |
| 78.97 | http | 414.7 | 1135.3 | 18.18 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.196 |
| 78.26 | shadowsocks | 236.7 | 600.3 | 22.3 | 0.0 | 10.0 | 12.68 | 17.78 | Au1rxx-base64 | 108.181.118.10 |
| 77.33 | vless | 327.9 | 808.7 | 20.19 | 0.0 | 10.0 | 10.43 | 17.78 | Au1rxx-base64 | 52.43.158.158 |
| 77.32 | http | 399.5 | 1107.3 | 18.53 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.218 |
| 77.18 | http | 405.3 | 1126.9 | 18.39 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.202 |
| 77.12 | http | 408.0 | 1133.7 | 18.33 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.206 |
| 77.11 | http | 408.6 | 1121.7 | 18.32 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.210 |
| 77.06 | http | 410.8 | 1133.2 | 18.27 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.214 |
| 76.98 | shadowsocks | 237.1 | 559.8 | 22.29 | 0.0 | 10.0 | 12.68 | 17.78 | Au1rxx-base64 | 149.22.95.183 |
| 76.98 | http | 414.1 | 1129.6 | 18.19 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.217 |
| 76.97 | hysteria2 | 241.4 | 536.5 | 22.19 | 0.0 | 10.0 | 13.0 | 17.78 | Au1rxx-base64 | 150.241.102.127 |
| 76.97 | http | 414.5 | 1139.8 | 18.18 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.207 |
| 76.93 | http | 416.2 | 1145.3 | 18.14 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.216 |
| 76.92 | http | 416.8 | 1146.8 | 18.13 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.213 |
| 76.89 | shadowsocks | 228.4 | 512.8 | 22.49 | 0.0 | 10.0 | 12.68 | 17.78 | Au1rxx-base64 | 173.244.56.9 |
| 76.89 | http | 418.3 | 1141.3 | 18.1 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.204 |
| 76.81 | http | 421.7 | 1141.8 | 18.02 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.200 |
| 76.81 | http | 421.7 | 1146.4 | 18.02 | 0.0 | 10.0 | 14.87 | 19.92 | zhangkai | 138.199.35.215 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | 1.0 | 113 | 129 | prefer |
| Au1rxx-base64 | 0.833 | 0.778 | 266 | 1430 | prefer |
| DeltaKronecker-all | 0.582 | 0.502 | 400 | 5759 | observe |
| mheidari-all | 0.4 | 0.75 | 4 | 16222 | observe |
| Surfboard-tg-mixed | 0.385 | 0.5 | 8 | 5387 | observe |
| xiaoji235-airport-v2ray-all | 0.329 | 1.0 | 1 | 1861 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5342 | observe |
| Epodonios-all | 0.255 | None | 0 | 6090 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6594 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4264 | observe |
| barry-far-vless | 0.255 | None | 0 | 4589 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5047 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.232 | None | 0 | 1430 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 86 |
| geo | TimeoutError | - | 40 |
| 204 | ProxyError | - | 40 |
| 204 | TimeoutError | - | 26 |
| geo | ClientOSError | - | 22 |
| speed | TimeoutError | - | 16 |
| speed | ClientOSError | - | 12 |
| cn-block | ProxyError | - | 7 |
| speed | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
