# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 12:55:01 |
| 运行耗时 | 328.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 77897 |
| 去重后节点 | 21437 |
| TCP 可达 | 3000 |
| 真实可用 | 777 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21437 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.5 |
| tcp | 34.9 |
| probe | 62.8 |
| real_test | 183.3 |
| generate | 39.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47983 |
| shadowsocks | 10300 |
| vmess | 10246 |
| trojan | 7809 |
| hysteria2 | 1163 |
| http | 164 |
| shadowsocksr | 127 |
| socks | 96 |
| hysteria | 7 |
| tuic | 2 |

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
| 81.71 | vless | 282.5 | 660.5 | 21.24 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 198.251.78.29 |
| 79.99 | shadowsocks | 290.0 | 676.6 | 21.06 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 37.19.198.243 |
| 79.61 | vless | 299.1 | 661.7 | 20.85 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 154.40.137.160 |
| 79.12 | vless | 394.5 | 661.9 | 18.65 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 38.180.242.205 |
| 79.06 | shadowsocks | 254.9 | 600.8 | 21.88 | 0.0 | 10.0 | 14.2 | 17.82 | Surfboard-tg-mixed | 23.150.248.20 |
| 78.95 | shadowsocks | 252.8 | 594.5 | 21.93 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 156.146.38.167 |
| 78.89 | http | 287.1 | 580.5 | 21.13 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |
| 78.69 | http | 296.8 | 606.6 | 20.91 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.216 |
| 77.81 | vless | 340.4 | 730.8 | 19.9 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 167.17.69.171 |
| 77.65 | vless | 410.5 | 1080.9 | 18.28 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 45.138.100.226 |
| 77.53 | shadowsocks | 285.5 | 622.3 | 21.17 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 94.72.127.55 |
| 77.29 | vless | 315.7 | 674.7 | 20.47 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 38.244.20.113 |
| 76.9 | shadowsocks | 288.6 | 610.4 | 21.1 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 94.72.127.58 |
| 76.56 | vless | 391.9 | 942.9 | 18.71 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 216.152.147.28 |
| 76.47 | vless | 418.6 | 997.8 | 18.09 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 130.107.73.148 |
| 76.44 | trojan | 322.6 | 673.9 | 20.31 | 0.0 | 10.0 | 13.78 | 19.82 | Au1rxx-base64 | 14.1.28.76 |
| 76.3 | trojan | 317.0 | 597.4 | 20.44 | 0.0 | 10.0 | 13.78 | 19.82 | Au1rxx-base64 | 44.251.158.80 |
| 75.87 | shadowsocks | 366.9 | 777.7 | 19.28 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 173.244.56.9 |
| 75.82 | shadowsocks | 352.6 | 856.1 | 19.62 | 0.0 | 10.0 | 14.2 | 19.82 | Au1rxx-base64 | 142.4.216.225 |
| 75.76 | vless | 317.1 | 648.0 | 20.44 | 0.0 | 10.0 | 10.65 | 19.82 | Au1rxx-base64 | 15.204.97.197 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Au1rxx-base64 | 0.964 | 0.896 | 431 | 1745 | prefer |
| mheidari-all | 0.964 | 0.902 | 41 | 14522 | prefer |
| Surfboard-tg-mixed | 0.826 | 0.75 | 128 | 6399 | prefer |
| DeltaKronecker-all | 0.642 | 0.562 | 256 | 5415 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6941 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6992 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5266 | observe |
| barry-far-vless | 0.255 | None | 0 | 5469 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4094 | observe |
| nscl5-all | 0.251 | 0.5 | 2 | 1082 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1746 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| cn-block | TimeoutError | - | 38 |
| 204 | TimeoutError | - | 28 |
| geo | ClientOSError | - | 22 |
| speed | TimeoutError | - | 14 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
