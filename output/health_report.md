# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 12:39:44 |
| 运行耗时 | 628.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96889 |
| 去重后节点 | 26969 |
| TCP 可达 | 3000 |
| 真实可用 | 467 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26969 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.5 |
| tcp | 45.0 |
| probe | 280.0 |
| real_test | 208.4 |
| generate | 88.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59092 |
| vmess | 14821 |
| shadowsocks | 11452 |
| trojan | 9245 |
| hysteria2 | 1405 |
| http | 583 |
| shadowsocksr | 165 |
| socks | 79 |
| anytls | 24 |
| hysteria | 15 |
| tuic | 8 |

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
| 83.39 | hysteria2 | 195.6 | 513.5 | 23.25 | 0.0 | 9.4 | 14.44 | 17.3 | Au1rxx-base64 | 192.255.128.123 |
| 77.34 | vless | 198.5 | 524.3 | 23.18 | 0.0 | 10.0 | 6.86 | 17.3 | Au1rxx-base64 | 172.233.139.46 |
| 77.32 | vless | 199.3 | 529.6 | 23.16 | 0.0 | 10.0 | 6.86 | 17.3 | Au1rxx-base64 | 172.235.38.85 |
| 76.2 | shadowsocks | 260.0 | 638.1 | 21.76 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 156.146.38.170 |
| 76.13 | shadowsocks | 260.2 | 636.2 | 21.75 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 156.146.38.168 |
| 75.73 | shadowsocks | 257.3 | 633.8 | 21.82 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 156.146.38.169 |
| 73.92 | shadowsocks | 265.6 | 695.2 | 21.63 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 108.181.0.177 |
| 73.35 | shadowsocks | 268.4 | 618.5 | 21.56 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 5.78.51.123 |
| 72.69 | shadowsocks | 253.3 | 693.8 | 21.91 | 0.0 | 9.42 | 13.06 | 17.3 | Au1rxx-base64 | 173.244.56.9 |
| 72.68 | shadowsocks | 264.1 | 642.6 | 21.66 | 0.0 | 10.0 | 13.06 | 15.38 | Surfboard-tg-mixed | 156.146.38.167 |
| 72.58 | vless | 271.4 | 601.3 | 21.5 | 0.0 | 9.22 | 6.86 | 17.3 | Au1rxx-base64 | 15.204.97.216 |
| 72.55 | vless | 336.1 | 841.4 | 20.0 | 0.0 | 9.25 | 6.86 | 17.3 | Au1rxx-base64 | 23.95.222.127 |
| 72.4 | shadowsocks | 281.8 | 289.4 | 21.25 | 4.15 | 9.91 | 13.06 | 15.38 | Surfboard-tg-mixed | 149.22.87.241 |
| 72.38 | hysteria2 | 289.0 | 360.0 | 21.09 | 1.5 | 7.89 | 14.44 | 17.3 | Au1rxx-base64 | open.2ml.bid |
| 71.81 | vless | 213.3 | 485.5 | 22.84 | 0.0 | 9.31 | 6.86 | 17.3 | Au1rxx-base64 | 172.64.32.108 |
| 71.09 | hysteria2 | 284.1 | 395.7 | 21.2 | 0.16 | 5.08 | 14.44 | 17.3 | Au1rxx-base64 | open.w2m.ink |
| 70.45 | vless | 333.7 | 745.8 | 20.05 | 0.0 | 9.21 | 6.86 | 17.3 | Au1rxx-base64 | 79.141.172.154 |
| 69.8 | http | 207.9 | 487.9 | 22.97 | 0.0 | 10.0 | 10.29 | 14.48 | ermaozi | 154.81.36.92 |
| 69.75 | vless | 195.5 | 511.1 | 23.25 | 0.0 | 10.0 | 6.86 | 9.64 | DeltaKronecker-all | 107.173.237.146 |
| 69.65 | vless | 288.7 | 502.5 | 21.1 | 0.0 | 9.39 | 6.86 | 17.3 | Au1rxx-base64 | 141.193.154.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | 0.87 | 54 | 22883 | prefer |
| Au1rxx-base64 | 0.913 | 0.852 | 330 | 1598 | prefer |
| ermaozi | 0.822 | 0.829 | 35 | 291 | prefer |
| Surfboard-tg-mixed | 0.668 | 0.59 | 134 | 7053 | observe |
| DeltaKronecker-all | 0.58 | 0.5 | 56 | 5528 | observe |
| ermaozi-get_subscribe | 0.323 | 1.0 | 2 | 293 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7502 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9548 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5690 | observe |
| barry-far-vless | 0.255 | None | 0 | 5869 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1598 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 41 |
| speed | ClientOSError | - | 29 |
| cn-block | TimeoutError | - | 22 |
| geo | TimeoutError | - | 18 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
