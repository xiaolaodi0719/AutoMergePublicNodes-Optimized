# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-03 03:55:51 |
| 运行耗时 | 329.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83558 |
| 去重后节点 | 23576 |
| TCP 可达 | 3000 |
| 真实可用 | 692 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23576 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 38.0 |
| probe | 91.0 |
| real_test | 155.5 |
| generate | 36.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52392 |
| vmess | 11307 |
| shadowsocks | 10021 |
| trojan | 7896 |
| hysteria2 | 1573 |
| http | 143 |
| shadowsocksr | 123 |
| socks | 82 |
| tuic | 11 |
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
| 84.9 | vless | 199.2 | 514.0 | 23.17 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.239.67.231 |
| 84.89 | vless | 199.3 | 523.7 | 23.16 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.233.156.123 |
| 84.86 | vless | 201.0 | 520.2 | 23.13 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.236.252.35 |
| 84.86 | vless | 201.0 | 524.4 | 23.13 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.235.38.85 |
| 84.41 | vless | 220.2 | 578.3 | 22.68 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.233.156.118 |
| 84.38 | vless | 221.6 | 574.4 | 22.65 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 108.186.202.51 |
| 84.23 | vless | 228.1 | 548.6 | 22.5 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 45.79.103.108 |
| 84.15 | hysteria2 | 235.0 | 550.3 | 22.34 | 0.0 | 10.0 | 14.17 | 19.4 | Au1rxx-base64 | 66.94.121.46 |
| 84.14 | vless | 222.1 | 527.5 | 22.64 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 45.33.107.237 |
| 84.06 | vless | 222.5 | 515.3 | 22.63 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 173.255.242.56 |
| 83.98 | http | 196.2 | 507.9 | 23.24 | 0.0 | 10.0 | 14.42 | 19.32 | zhangkai | 138.199.35.216 |
| 83.86 | http | 201.2 | 513.9 | 23.12 | 0.0 | 10.0 | 14.42 | 19.32 | zhangkai | 138.199.35.198 |
| 83.86 | vless | 243.9 | 654.6 | 22.13 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 172.239.67.156 |
| 83.2 | vless | 223.5 | 531.0 | 22.6 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 50.116.9.184 |
| 82.97 | vless | 226.9 | 538.7 | 22.53 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 74.207.245.124 |
| 82.96 | vless | 248.6 | 551.5 | 22.02 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 31.58.50.200 |
| 82.75 | vless | 214.2 | 512.9 | 22.82 | 0.0 | 10.0 | 12.33 | 17.6 | mheidari-all | 45.33.107.60 |
| 82.43 | vless | 227.8 | 531.5 | 22.5 | 0.0 | 10.0 | 12.33 | 17.6 | mheidari-all | 173.255.242.235 |
| 82.09 | vless | 212.7 | 499.1 | 22.85 | 0.0 | 10.0 | 12.33 | 19.4 | Au1rxx-base64 | 45.33.62.166 |
| 81.78 | vless | 230.0 | 604.3 | 22.45 | 0.0 | 10.0 | 12.33 | 17.0 | Surfboard-tg-mixed | 172.233.156.42 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.981 | 0.909 | 372 | 1874 | prefer |
| Surfboard-tg-mixed | 0.867 | 0.789 | 209 | 7080 | prefer |
| zhangkai | 0.846 | 0.87 | 23 | 144 | prefer |
| mheidari-all | 0.557 | 0.477 | 348 | 16261 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7558 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7927 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5956 | observe |
| barry-far-vless | 0.255 | None | 0 | 6145 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |
| Au1rxx-clash | 0.25 | None | 0 | 1874 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 120 |
| speed | TimeoutError | - | 60 |
| speed | ClientOSError | - | 41 |
| geo | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyConnectionError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
