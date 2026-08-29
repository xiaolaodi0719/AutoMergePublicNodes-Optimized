# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-29 20:49:28 |
| 运行耗时 | 299.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79290 |
| 去重后节点 | 21340 |
| TCP 可达 | 3000 |
| 真实可用 | 642 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21340 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 34.8 |
| probe | 62.9 |
| real_test | 147.9 |
| generate | 47.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49800 |
| vmess | 10940 |
| shadowsocks | 10529 |
| trojan | 6094 |
| hysteria2 | 1547 |
| http | 173 |
| shadowsocksr | 133 |
| socks | 57 |
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
| 87.17 | vless | 163.0 | 456.4 | 24.0 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 64.23.229.123 |
| 85.11 | vless | 166.0 | 464.4 | 23.94 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 74.207.245.124 |
| 85.03 | vless | 169.2 | 475.9 | 23.86 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 45.33.62.226 |
| 84.83 | vless | 177.7 | 490.7 | 23.66 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 45.33.107.237 |
| 84.78 | vless | 179.9 | 504.9 | 23.61 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 192.155.87.188 |
| 84.71 | vless | 183.3 | 490.4 | 23.54 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 173.255.242.235 |
| 84.58 | vless | 188.9 | 492.9 | 23.41 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.233.156.123 |
| 84.41 | vless | 196.1 | 499.8 | 23.24 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 84.2 | vless | 205.0 | 488.2 | 23.03 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 84.17 | vless | 206.2 | 535.3 | 23.0 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 83.98 | vless | 171.5 | 479.7 | 23.81 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 50.116.13.24 |
| 83.96 | vless | 301.9 | 792.8 | 20.79 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 15.204.97.206 |
| 83.9 | vless | 174.8 | 475.9 | 23.73 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 50.116.9.184 |
| 83.88 | vless | 305.4 | 799.4 | 20.71 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 15.204.97.209 |
| 83.79 | vless | 179.6 | 500.6 | 23.62 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 192.81.131.225 |
| 83.63 | vless | 316.3 | 834.4 | 20.46 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 83.62 | vless | 316.8 | 828.0 | 20.45 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 15.204.97.195 |
| 83.5 | vless | 322.0 | 845.1 | 20.33 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 83.39 | vless | 196.9 | 513.2 | 23.22 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 83.23 | vless | 204.0 | 524.3 | 23.06 | 0.0 | 10.0 | 13.17 | 20.0 | Au1rxx-base64 | 172.236.252.35 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.897 | 360 | 1753 | prefer |
| zhangkai | 0.926 | 0.957 | 23 | 144 | prefer |
| mheidari-all | 0.897 | 0.824 | 91 | 14908 | prefer |
| DeltaKronecker-all | 0.865 | 0.789 | 128 | 4926 | prefer |
| Surfboard-tg-mixed | 0.825 | 0.748 | 155 | 6924 | prefer |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 155 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7291 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7802 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5706 | observe |
| barry-far-vless | 0.255 | None | 0 | 5901 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 34 |
| cn-block | TimeoutError | - | 22 |
| geo | TimeoutError | - | 14 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
