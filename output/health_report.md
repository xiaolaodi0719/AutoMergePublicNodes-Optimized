# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 03:55:01 |
| 运行耗时 | 312.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84344 |
| 去重后节点 | 23684 |
| TCP 可达 | 3000 |
| 真实可用 | 531 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23684 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 38.3 |
| probe | 90.0 |
| real_test | 132.3 |
| generate | 43.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53157 |
| vmess | 11487 |
| shadowsocks | 9882 |
| trojan | 8065 |
| hysteria2 | 1401 |
| http | 149 |
| shadowsocksr | 126 |
| socks | 52 |
| tuic | 14 |
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
| 84.34 | vless | 188.9 | 487.0 | 23.41 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 172.233.139.46 |
| 84.33 | vless | 189.1 | 489.6 | 23.4 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 172.235.38.85 |
| 84.22 | vless | 194.1 | 495.8 | 23.29 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 31.58.50.200 |
| 83.24 | vless | 236.2 | 591.7 | 22.31 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 38.127.121.44 |
| 80.79 | shadowsocks | 224.5 | 532.6 | 22.58 | 0.0 | 10.0 | 13.29 | 18.92 | Au1rxx-base64 | 149.22.95.183 |
| 80.78 | shadowsocks | 203.4 | 521.6 | 23.07 | 0.0 | 10.0 | 13.29 | 18.92 | Au1rxx-base64 | 108.181.0.177 |
| 80.61 | shadowsocks | 210.6 | 510.7 | 22.9 | 0.0 | 10.0 | 13.29 | 18.92 | Au1rxx-base64 | 108.181.118.10 |
| 80.07 | trojan | 225.5 | 599.6 | 22.56 | 0.0 | 10.0 | 13.59 | 18.92 | Au1rxx-base64 | 107.150.105.84 |
| 79.74 | shadowsocks | 270.0 | 667.2 | 21.53 | 0.0 | 10.0 | 13.29 | 18.92 | Au1rxx-base64 | 173.244.56.9 |
| 79.58 | hysteria2 | 397.7 | 1028.6 | 18.57 | 0.0 | 10.0 | 13.93 | 18.08 | mheidari-all | 66.94.121.46 |
| 79.48 | vless | 204.1 | 528.0 | 23.05 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 204.44.127.222 |
| 78.9 | vless | 207.8 | 483.9 | 22.97 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 38.150.33.232 |
| 78.81 | vless | 211.8 | 529.7 | 22.88 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 23.94.227.94 |
| 78.8 | trojan | 198.1 | 510.7 | 23.19 | 0.0 | 6.1 | 13.59 | 18.92 | Au1rxx-base64 | us01.duotg.top |
| 78.68 | http | 427.7 | 1193.7 | 17.88 | 0.0 | 10.0 | 14.52 | 19.28 | zhangkai | 138.199.35.216 |
| 76.64 | vless | 276.1 | 668.3 | 21.39 | 0.0 | 10.0 | 12.01 | 18.08 | mheidari-all | 104.21.91.142 |
| 76.62 | vless | 522.3 | 1395.6 | 15.69 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 51.81.203.63 |
| 76.49 | vless | 203.7 | 505.9 | 23.06 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 192.220.11.234 |
| 75.81 | vless | 215.9 | 498.8 | 22.78 | 0.0 | 10.0 | 12.01 | 18.92 | Au1rxx-base64 | 172.64.154.8 |
| 75.78 | vless | 282.7 | 212.2 | 21.23 | 7.04 | 8.87 | 12.01 | 18.92 | Au1rxx-base64 | hk2-r.link-t7.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | 0.911 | 380 | 1796 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| mheidari-all | 0.69 | 0.611 | 193 | 16194 | observe |
| tg-oneclickvpnkeys | 0.554 | 1.0 | 8 | 135 | observe |
| Surfboard-tg-mixed | 0.53 | 0.7 | 10 | 7291 | observe |
| DeltaKronecker-all | 0.393 | 0.309 | 97 | 7089 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 4810 | observe |
| Epodonios-all | 0.255 | None | 0 | 7727 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8350 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6083 | observe |
| barry-far-vless | 0.255 | None | 0 | 6282 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1796 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 85 |
| speed | TimeoutError | - | 39 |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| speed | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
