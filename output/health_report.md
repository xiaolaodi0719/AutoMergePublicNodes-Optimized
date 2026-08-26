# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 07:01:06 |
| 运行耗时 | 277.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 77824 |
| 去重后节点 | 22072 |
| TCP 可达 | 3000 |
| 真实可用 | 592 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22072 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.4 |
| tcp | 34.8 |
| probe | 56.5 |
| real_test | 139.9 |
| generate | 38.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48969 |
| vmess | 10276 |
| shadowsocks | 10258 |
| trojan | 6581 |
| hysteria2 | 1362 |
| http | 172 |
| shadowsocksr | 128 |
| socks | 68 |
| hysteria | 7 |
| tuic | 3 |

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
| 80.06 | shadowsocks | 270.3 | 625.6 | 21.52 | 0.0 | 10.0 | 14.14 | 18.4 | Surfboard-tg-mixed | 156.146.38.167 |
| 77.95 | vless | 268.7 | 669.4 | 21.56 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 216.152.147.28 |
| 77.54 | vless | 286.2 | 688.9 | 21.15 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.184 |
| 77.37 | vless | 293.8 | 749.1 | 20.98 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 198.251.78.29 |
| 77.34 | vless | 294.8 | 739.3 | 20.95 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 47.89.186.170 |
| 76.83 | vless | 292.9 | 704.3 | 21.0 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 167.17.69.171 |
| 76.81 | shadowsocks | 389.1 | 1045.3 | 18.77 | 0.0 | 10.0 | 14.14 | 18.4 | Surfboard-tg-mixed | 15.204.246.132 |
| 76.7 | vless | 301.1 | 728.1 | 20.81 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 137.184.218.169 |
| 76.64 | shadowsocks | 418.0 | 1113.5 | 18.1 | 0.0 | 10.0 | 14.14 | 18.4 | Surfboard-tg-mixed | 142.4.216.225 |
| 76.02 | vless | 319.2 | 649.6 | 20.39 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.35 |
| 75.66 | vless | 359.6 | 786.8 | 19.45 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.182 |
| 75.42 | vless | 310.2 | 724.6 | 20.6 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 66.70.179.198 |
| 75.3 | vless | 383.2 | 972.9 | 18.91 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.15 |
| 75.28 | hysteria2 | 382.8 | 694.5 | 18.92 | 0.0 | 9.9 | 14.0 | 19.42 | Au1rxx-base64 | 89.125.156.80 |
| 75.21 | vless | 386.9 | 929.6 | 18.82 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.52 |
| 75.17 | vless | 291.4 | 703.3 | 21.03 | 0.0 | 8.99 | 6.97 | 19.42 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 74.85 | vless | 371.2 | 882.1 | 19.19 | 0.0 | 10.0 | 6.97 | 19.42 | Au1rxx-base64 | 169.40.42.232 |
| 74.48 | hysteria2 | 414.5 | 760.4 | 18.18 | 0.0 | 9.86 | 14.0 | 19.42 | Au1rxx-base64 | 217.60.33.215 |
| 74.39 | shadowsocks | 314.6 | 636.6 | 20.49 | 0.0 | 10.0 | 14.14 | 18.4 | Surfboard-tg-mixed | 94.72.127.58 |
| 73.64 | hysteria2 | 405.6 | 743.1 | 18.39 | 0.0 | 9.85 | 14.0 | 18.4 | Surfboard-tg-mixed | 45.192.12.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.905 | 0.828 | 377 | 1986 | prefer |
| Surfboard-tg-mixed | 0.757 | 0.679 | 165 | 6380 | prefer |
| DeltaKronecker-all | 0.7 | 0.622 | 98 | 6107 | prefer |
| mheidari-all | 0.691 | 0.613 | 124 | 14091 | observe |
| nscl5-all | 0.402 | 0.8 | 5 | 887 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 4825 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 206 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1990 | observe |
| Epodonios-all | 0.255 | None | 0 | 6845 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6976 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5270 | observe |
| barry-far-vless | 0.255 | None | 0 | 5518 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3981 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 56 |
| geo | TimeoutError | - | 54 |
| cn-block | TimeoutError | - | 24 |
| geo | ClientOSError | - | 20 |
| speed | ClientOSError | - | 17 |
| 204 | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
