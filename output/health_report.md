# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 16:14:22 |
| 运行耗时 | 293.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82139 |
| 去重后节点 | 22600 |
| TCP 可达 | 3000 |
| 真实可用 | 584 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22600 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.7 |
| tcp | 37.0 |
| probe | 86.9 |
| real_test | 126.7 |
| generate | 34.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51267 |
| vmess | 11466 |
| shadowsocks | 9822 |
| trojan | 7614 |
| hysteria2 | 1603 |
| http | 140 |
| shadowsocksr | 130 |
| socks | 75 |
| tuic | 11 |
| hysteria | 10 |
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
| 85.66 | vless | 166.2 | 461.7 | 23.93 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 45.79.103.108 |
| 85.55 | vless | 171.2 | 471.8 | 23.82 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 45.33.107.237 |
| 85.54 | vless | 171.3 | 469.8 | 23.81 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 45.33.62.166 |
| 85.46 | vless | 175.0 | 482.4 | 23.73 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 192.155.87.188 |
| 85.0 | vless | 194.5 | 500.8 | 23.27 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.236.252.35 |
| 85.0 | vless | 194.7 | 505.6 | 23.27 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.233.139.46 |
| 84.96 | vless | 196.5 | 512.3 | 23.23 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.239.67.156 |
| 84.95 | vless | 196.8 | 484.7 | 23.22 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 50.116.9.184 |
| 84.89 | vless | 199.5 | 509.5 | 23.16 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.239.67.231 |
| 84.77 | vless | 204.8 | 572.1 | 23.04 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 74.207.245.124 |
| 84.56 | vless | 213.8 | 497.8 | 22.83 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 31.58.50.200 |
| 84.37 | vless | 221.8 | 512.4 | 22.64 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.235.43.210 |
| 84.35 | vless | 222.8 | 504.9 | 22.62 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.235.38.85 |
| 84.13 | vless | 232.3 | 534.2 | 22.4 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.233.156.123 |
| 83.74 | vless | 249.3 | 459.2 | 22.01 | 0.0 | 10.0 | 12.25 | 19.48 | Au1rxx-base64 | 172.233.156.118 |
| 83.27 | http | 219.9 | 488.9 | 22.69 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.216 |
| 83.13 | hysteria2 | 231.4 | 542.4 | 22.42 | 0.0 | 10.0 | 14.21 | 19.48 | Au1rxx-base64 | 66.94.121.46 |
| 82.58 | http | 251.3 | 617.8 | 21.96 | 0.0 | 10.0 | 14.38 | 19.24 | zhangkai | 138.199.35.198 |
| 81.57 | shadowsocks | 249.7 | 597.6 | 22.0 | 0.0 | 10.0 | 14.09 | 19.48 | Au1rxx-base64 | 149.22.95.183 |
| 80.8 | shadowsocks | 282.8 | 611.6 | 21.23 | 0.0 | 10.0 | 14.09 | 19.48 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.952 | 330 | 1770 | prefer |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| mheidari-all | 0.871 | 0.796 | 108 | 15770 | prefer |
| DeltaKronecker-all | 0.864 | 0.8 | 35 | 6335 | prefer |
| Surfboard-tg-mixed | 0.817 | 0.74 | 173 | 7139 | prefer |
| tg-oneclickvpnkeys | 0.445 | 1.0 | 5 | 145 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4671 | observe |
| Epodonios-all | 0.255 | None | 0 | 7586 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7991 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6006 | observe |
| barry-far-vless | 0.255 | None | 0 | 6219 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 22 |
| geo | ClientOSError | - | 21 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
