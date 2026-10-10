# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 21:36:56 |
| 运行耗时 | 767.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98061 |
| 去重后节点 | 27327 |
| TCP 可达 | 3000 |
| 真实可用 | 437 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27327 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.2 |
| tcp | 47.0 |
| probe | 304.6 |
| real_test | 314.8 |
| generate | 90.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57878 |
| vmess | 15839 |
| shadowsocks | 11746 |
| trojan | 10236 |
| hysteria2 | 1543 |
| http | 521 |
| shadowsocksr | 171 |
| socks | 72 |
| anytls | 32 |
| hysteria | 16 |
| tuic | 7 |

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
| 83.75 | hysteria2 | 256.6 | 228.7 | 21.84 | 6.42 | 9.76 | 13.5 | 19.16 | Au1rxx-base64 | 158.101.148.79 |
| 83.36 | http | 222.1 | 552.9 | 22.64 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.198 |
| 82.7 | vless | 214.7 | 512.0 | 22.81 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 47.251.108.158 |
| 82.22 | vless | 192.3 | 503.9 | 23.33 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 45.32.69.110 |
| 81.76 | vless | 212.0 | 534.0 | 22.87 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 154.9.241.170 |
| 81.48 | http | 216.7 | 517.0 | 22.76 | 0.0 | 10.0 | 14.4 | 19.32 | zhangkai | 138.199.35.216 |
| 80.78 | vless | 211.2 | 534.3 | 22.89 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 154.29.145.196 |
| 80.7 | vless | 214.6 | 506.8 | 22.81 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 137.175.82.40 |
| 80.6 | vless | 305.5 | 834.9 | 20.71 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 107.173.237.146 |
| 80.54 | vless | 221.4 | 547.1 | 22.65 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 154.12.38.159 |
| 79.79 | shadowsocks | 259.5 | 633.8 | 21.77 | 0.0 | 10.0 | 12.88 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 79.76 | shadowsocks | 261.5 | 637.0 | 21.72 | 0.0 | 10.0 | 12.88 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 79.73 | vless | 270.9 | 589.9 | 21.51 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 15.204.97.197 |
| 79.27 | shadowsocks | 239.9 | 555.3 | 22.22 | 0.0 | 10.0 | 12.88 | 19.16 | Au1rxx-base64 | 5.78.51.123 |
| 78.77 | shadowsocks | 260.2 | 635.3 | 21.75 | 0.0 | 10.0 | 12.88 | 19.16 | Au1rxx-base64 | 156.146.38.167 |
| 78.75 | hysteria2 | 336.2 | 736.3 | 20.0 | 0.0 | 10.0 | 13.5 | 19.16 | Au1rxx-base64 | 129.213.91.185 |
| 77.95 | hysteria2 | 387.0 | 704.3 | 18.82 | 0.0 | 10.0 | 13.5 | 19.16 | Au1rxx-base64 | 66.94.121.46 |
| 76.28 | vless | 233.0 | 541.0 | 22.39 | 0.0 | 10.0 | 10.73 | 19.16 | Au1rxx-base64 | 188.114.97.6 |
| 76.22 | shadowsocks | 289.4 | 618.5 | 21.08 | 0.0 | 10.0 | 12.88 | 19.16 | Au1rxx-base64 | 149.22.95.183 |
| 76.21 | shadowsocks | 281.0 | 287.1 | 21.27 | 4.23 | 9.91 | 12.88 | 19.16 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | 0.889 | 351 | 1850 | prefer |
| mheidari-all | 0.88 | 0.811 | 53 | 23925 | prefer |
| zhangkai | 0.726 | 0.739 | 23 | 144 | prefer |
| DeltaKronecker-all | 0.619 | 0.54 | 113 | 5009 | observe |
| Surfboard-tg-mixed | 0.438 | 1.0 | 3 | 7118 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7597 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9340 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5677 | observe |
| barry-far-vless | 0.255 | None | 0 | 5914 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4347 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1850 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 18 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyConnectionError | - | 11 |
| 204 | ProxyError | - | 11 |
| geo | ClientOSError | - | 11 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
