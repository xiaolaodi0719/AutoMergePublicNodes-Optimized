# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 20:54:55 |
| 运行耗时 | 287.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82593 |
| 去重后节点 | 23713 |
| TCP 可达 | 3000 |
| 真实可用 | 554 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23713 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 37.2 |
| probe | 83.6 |
| real_test | 121.8 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51944 |
| vmess | 11157 |
| shadowsocks | 9828 |
| trojan | 7776 |
| hysteria2 | 1514 |
| http | 144 |
| shadowsocksr | 128 |
| socks | 84 |
| tuic | 11 |
| hysteria | 7 |

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
| 85.48 | vless | 180.1 | 506.3 | 23.61 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 45.79.103.108 |
| 85.25 | vless | 189.8 | 536.0 | 23.38 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 45.33.62.166 |
| 85.17 | vless | 193.4 | 539.4 | 23.3 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 192.155.87.188 |
| 85.1 | hysteria2 | 219.4 | 536.8 | 22.7 | 0.0 | 10.0 | 14.0 | 19.4 | Au1rxx-base64 | 66.94.121.46 |
| 84.97 | vless | 202.1 | 560.7 | 23.1 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 50.116.9.184 |
| 84.95 | vless | 203.0 | 533.7 | 23.08 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.233.139.46 |
| 84.91 | vless | 204.6 | 513.7 | 23.04 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.236.252.35 |
| 84.89 | vless | 205.7 | 577.3 | 23.02 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 74.207.245.124 |
| 84.84 | vless | 207.9 | 535.6 | 22.97 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.233.156.123 |
| 84.73 | vless | 212.3 | 538.2 | 22.86 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.235.38.85 |
| 84.52 | vless | 221.3 | 583.5 | 22.65 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.239.67.156 |
| 84.4 | vless | 226.7 | 594.8 | 22.53 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.233.156.118 |
| 84.37 | vless | 228.1 | 603.9 | 22.5 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.239.67.231 |
| 84.18 | vless | 236.4 | 620.4 | 22.31 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 172.235.43.210 |
| 83.82 | vless | 251.8 | 512.6 | 21.95 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 173.255.242.56 |
| 82.82 | vless | 215.0 | 553.7 | 22.8 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 104.223.73.149 |
| 81.19 | trojan | 270.7 | 739.9 | 21.51 | 0.0 | 10.0 | 13.2 | 18.98 | mheidari-all | 34.94.125.227 |
| 80.51 | vless | 200.3 | 534.1 | 23.14 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 204.44.127.222 |
| 80.41 | shadowsocks | 252.5 | 623.1 | 21.93 | 0.0 | 10.0 | 13.08 | 19.4 | Au1rxx-base64 | 149.22.95.183 |
| 79.99 | vless | 201.3 | 537.8 | 23.12 | 0.0 | 10.0 | 12.47 | 19.4 | Au1rxx-base64 | 31.58.50.200 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.97 | 0.901 | 343 | 1798 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.88 | 0.805 | 118 | 15504 | prefer |
| Surfboard-tg-mixed | 0.85 | 0.773 | 150 | 7091 | prefer |
| DeltaKronecker-all | 0.629 | 1.0 | 8 | 7295 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7530 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7745 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6013 | observe |
| barry-far-vless | 0.255 | None | 0 | 6223 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 20 |
| geo | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 5 |
| speed | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
