# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 20:39:12 |
| 运行耗时 | 284.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84231 |
| 去重后节点 | 23539 |
| TCP 可达 | 3000 |
| 真实可用 | 596 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23539 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.3 |
| tcp | 38.7 |
| probe | 67.6 |
| real_test | 129.4 |
| generate | 42.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53343 |
| vmess | 11496 |
| shadowsocks | 9658 |
| trojan | 7965 |
| hysteria2 | 1359 |
| http | 192 |
| shadowsocksr | 125 |
| socks | 67 |
| tuic | 15 |
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
| 84.49 | hysteria2 | 222.4 | 605.3 | 22.63 | 0.0 | 10.0 | 13.12 | 19.74 | Au1rxx-base64 | 66.94.121.46 |
| 82.78 | vless | 307.5 | 844.3 | 20.66 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 15.204.97.216 |
| 82.69 | vless | 311.5 | 852.7 | 20.57 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 15.204.97.197 |
| 81.76 | shadowsocks | 216.5 | 581.1 | 22.77 | 0.0 | 10.0 | 13.25 | 19.74 | Au1rxx-base64 | 149.22.95.183 |
| 81.26 | vless | 282.8 | 597.8 | 21.23 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 31.58.50.200 |
| 80.85 | vless | 390.7 | 1075.4 | 18.73 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 51.81.203.63 |
| 80.81 | vless | 275.3 | 582.2 | 21.41 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 38.127.121.44 |
| 80.6 | vless | 268.9 | 578.6 | 21.55 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 172.233.139.46 |
| 80.25 | vless | 225.9 | 267.7 | 22.55 | 4.96 | 10.0 | 12.38 | 17.12 | Surfboard-tg-mixed | 31.76.91.72 |
| 79.03 | vless | 276.7 | 566.0 | 21.37 | 0.0 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 172.235.38.85 |
| 78.8 | vless | 364.1 | 274.4 | 19.35 | 4.71 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 13.114.124.85 |
| 78.62 | vless | 293.8 | 308.3 | 20.98 | 3.44 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 162.141.131.102 |
| 78.6 | vless | 307.3 | 318.4 | 20.66 | 3.06 | 9.96 | 12.38 | 19.74 | Au1rxx-base64 | 154.31.114.248 |
| 78.49 | vless | 377.2 | 275.9 | 19.05 | 4.65 | 9.99 | 12.38 | 19.74 | Au1rxx-base64 | 54.249.200.131 |
| 78.48 | vless | 361.4 | 284.6 | 19.41 | 4.33 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 18.183.215.124 |
| 78.28 | vless | 364.6 | 287.7 | 19.34 | 4.21 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 52.194.211.43 |
| 78.26 | vless | 366.0 | 289.9 | 19.3 | 4.13 | 10.0 | 12.38 | 19.74 | Au1rxx-base64 | 13.231.19.51 |
| 78.11 | vless | 318.2 | 322.2 | 20.41 | 2.92 | 9.99 | 12.38 | 19.74 | Au1rxx-base64 | 54.238.241.88 |
| 78.05 | vless | 316.8 | 323.3 | 20.44 | 2.88 | 9.99 | 12.38 | 19.74 | Au1rxx-base64 | 13.230.222.139 |
| 77.97 | shadowsocks | 251.9 | 506.7 | 21.95 | 0.0 | 10.0 | 13.25 | 19.74 | Au1rxx-base64 | 108.181.0.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Au1rxx-base64 | 0.946 | 0.878 | 337 | 1756 | prefer |
| mheidari-all | 0.904 | 0.829 | 117 | 16096 | prefer |
| DeltaKronecker-all | 0.869 | 0.806 | 36 | 7089 | prefer |
| Surfboard-tg-mixed | 0.845 | 0.768 | 185 | 7342 | prefer |
| tg-oneclickvpnkeys | 0.589 | 1.0 | 9 | 118 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| Epodonios-all | 0.255 | None | 0 | 7798 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8118 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6159 | observe |
| barry-far-vless | 0.255 | None | 0 | 6376 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1756 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 16 |
| geo | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 12 |
| speed | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 5 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
