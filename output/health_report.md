# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 16:29:02 |
| 运行耗时 | 285.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 79920 |
| 去重后节点 | 21856 |
| TCP 可达 | 3000 |
| 真实可用 | 583 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21856 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.5 |
| tcp | 35.0 |
| probe | 56.8 |
| real_test | 145.0 |
| generate | 41.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50290 |
| vmess | 10877 |
| shadowsocks | 10241 |
| trojan | 6614 |
| hysteria2 | 1511 |
| http | 170 |
| shadowsocksr | 123 |
| socks | 78 |
| tuic | 8 |
| hysteria | 7 |
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
| 84.73 | vless | 223.3 | 513.0 | 22.61 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 45.33.107.237 |
| 84.43 | vless | 226.0 | 514.3 | 22.55 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 74.207.245.124 |
| 84.38 | vless | 235.4 | 546.0 | 22.33 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 45.33.62.166 |
| 84.23 | vless | 231.5 | 523.9 | 22.42 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 192.155.87.188 |
| 83.95 | vless | 234.5 | 531.9 | 22.35 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 173.255.242.56 |
| 83.94 | vless | 242.3 | 557.7 | 22.17 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 50.116.9.184 |
| 83.93 | vless | 240.7 | 554.6 | 22.21 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 192.81.131.225 |
| 83.75 | vless | 273.9 | 750.2 | 21.44 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 15.204.97.216 |
| 83.4 | vless | 289.0 | 797.4 | 21.09 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 15.204.97.206 |
| 83.3 | vless | 293.4 | 810.6 | 20.99 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 15.204.97.209 |
| 83.19 | vless | 234.5 | 529.9 | 22.35 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 50.116.13.24 |
| 82.72 | shadowsocks | 206.8 | 562.9 | 22.99 | 0.0 | 10.0 | 13.73 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.62 | vless | 255.6 | 542.0 | 21.86 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 31.58.50.200 |
| 82.41 | vless | 331.8 | 916.4 | 20.1 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 82.39 | vless | 243.7 | 521.8 | 22.14 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 45.33.62.226 |
| 82.06 | vless | 261.9 | 562.1 | 21.71 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 172.233.156.123 |
| 82.04 | hysteria2 | 202.7 | 561.7 | 23.09 | 0.0 | 10.0 | 12.95 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 82.04 | vless | 251.2 | 544.0 | 21.96 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 172.236.252.35 |
| 82.01 | vless | 280.6 | 638.6 | 21.28 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 81.91 | vless | 244.3 | 520.4 | 22.12 | 0.0 | 10.0 | 12.31 | 20.0 | Au1rxx-base64 | 216.167.94.71 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.955 | 0.885 | 339 | 1804 | prefer |
| DeltaKronecker-all | 0.814 | 0.737 | 175 | 5576 | prefer |
| Surfboard-tg-mixed | 0.812 | 0.735 | 162 | 7004 | prefer |
| mheidari-all | 0.699 | 1.0 | 10 | 15115 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7409 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7601 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5872 | observe |
| barry-far-vless | 0.255 | None | 0 | 6056 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3949 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 34 |
| geo | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| 204 | ProxyError | - | 13 |
| speed | ClientOSError | - | 11 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
