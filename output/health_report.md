# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-21 07:01:14 |
| 运行耗时 | 367.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 94141 |
| 去重后节点 | 24585 |
| TCP 可达 | 3000 |
| 真实可用 | 1172 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24585 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 0.9 |
| tcp | 38.4 |
| probe | 69.8 |
| real_test | 207.1 |
| generate | 45.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52087 |
| trojan | 18264 |
| vmess | 10862 |
| shadowsocks | 10751 |
| hysteria2 | 1626 |
| shadowsocksr | 201 |
| http | 166 |
| socks | 125 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 84.81 | trojan | 216.9 | 486.8 | 22.76 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 35.91.98.35 |
| 84.79 | trojan | 217.3 | 489.8 | 22.75 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 35.88.120.18 |
| 84.74 | trojan | 219.9 | 499.4 | 22.69 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 35.91.138.234 |
| 84.73 | trojan | 220.2 | 498.1 | 22.68 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 35.92.245.6 |
| 84.41 | trojan | 234.0 | 533.6 | 22.36 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 34.223.2.163 |
| 84.31 | trojan | 238.3 | 545.5 | 22.26 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 35.90.27.143 |
| 84.25 | trojan | 226.6 | 517.2 | 22.53 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 44.255.190.116 |
| 84.23 | trojan | 227.5 | 514.1 | 22.51 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 44.251.158.80 |
| 84.17 | shadowsocks | 167.0 | 435.8 | 23.91 | 0.0 | 10.0 | 14.51 | 20.0 | Au1rxx-base64 | 209.38.142.23 |
| 83.65 | trojan | 266.7 | 639.3 | 21.6 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 34.220.224.252 |
| 83.55 | trojan | 271.2 | 652.7 | 21.5 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 54.244.169.225 |
| 83.22 | shadowsocks | 197.5 | 490.1 | 23.21 | 0.0 | 10.0 | 14.51 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 83.18 | trojan | 278.9 | 672.7 | 21.32 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 34.210.213.17 |
| 83.15 | trojan | 288.6 | 702.3 | 21.1 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 54.245.126.186 |
| 82.74 | shadowsocks | 239.5 | 522.6 | 22.23 | 0.0 | 10.0 | 14.51 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 82.65 | shadowsocks | 243.6 | 595.2 | 22.14 | 0.0 | 10.0 | 14.51 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 82.6 | trojan | 305.4 | 750.9 | 20.71 | 0.0 | 10.0 | 14.55 | 20.0 | Surfboard-tg-mixed | 54.188.176.255 |
| 82.41 | trojan | 234.1 | 535.5 | 22.36 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 35.160.249.189 |
| 81.42 | trojan | 233.6 | 535.1 | 22.37 | 0.0 | 10.0 | 14.55 | 20.0 | Au1rxx-base64 | 34.221.30.108 |
| 80.53 | hysteria2 | 311.7 | 299.2 | 20.56 | 3.78 | 9.9 | 14.58 | 20.0 | Au1rxx-base64 | 45.32.252.144 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.958 | 641 | 1607 | prefer |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| mheidari-all | 0.922 | 0.844 | 295 | 21864 | prefer |
| Surfboard-tg-mixed | 0.855 | 0.777 | 242 | 6368 | prefer |
| nscl5-all | 0.391 | 1.0 | 2 | 3031 | observe |
| DeltaKronecker-all | 0.366 | 0.269 | 26 | 6250 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5148 | observe |
| Epodonios-all | 0.255 | None | 0 | 7077 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7024 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5051 | observe |
| barry-far-vless | 0.255 | None | 0 | 5415 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4647 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 45 |
| speed | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 15 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
