# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 22:08:18 |
| 运行耗时 | 464.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98974 |
| 去重后节点 | 27178 |
| TCP 可达 | 3000 |
| 真实可用 | 423 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27178 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 48.2 |
| probe | 210.1 |
| real_test | 156.8 |
| generate | 42.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60741 |
| vmess | 15480 |
| shadowsocks | 11436 |
| trojan | 8931 |
| hysteria2 | 1566 |
| http | 522 |
| shadowsocksr | 166 |
| socks | 67 |
| anytls | 40 |
| hysteria | 17 |
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
| 79.07 | hysteria2 | 273.3 | 546.1 | 21.45 | 0.0 | 10.0 | 14.35 | 18.08 | Au1rxx-base64 | 192.255.128.123 |
| 78.92 | shadowsocks | 259.4 | 627.8 | 21.77 | 0.0 | 10.0 | 13.07 | 18.08 | Au1rxx-base64 | 156.146.38.167 |
| 77.11 | shadowsocks | 266.1 | 635.0 | 21.62 | 0.0 | 10.0 | 13.07 | 16.42 | Surfboard-tg-mixed | 156.146.38.170 |
| 76.44 | vless | 304.7 | 581.2 | 20.72 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 185.47.254.251 |
| 76.21 | hysteria2 | 286.1 | 272.3 | 21.16 | 4.79 | 5.57 | 14.35 | 18.08 | Au1rxx-base64 | open.w2m.ink |
| 76.05 | hysteria2 | 336.1 | 735.5 | 20.0 | 0.0 | 10.0 | 14.35 | 17.26 | mheidari-all | 159.223.157.129 |
| 75.57 | shadowsocks | 259.7 | 638.9 | 21.77 | 0.0 | 10.0 | 13.07 | 18.08 | Au1rxx-base64 | 156.146.38.168 |
| 75.49 | vless | 335.5 | 755.5 | 20.01 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 79.141.172.154 |
| 74.96 | vless | 296.3 | 634.6 | 20.92 | 0.0 | 10.0 | 11.39 | 17.26 | mheidari-all | 216.227.161.95 |
| 74.9 | vless | 311.1 | 602.0 | 20.58 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 172.235.38.85 |
| 74.84 | vless | 319.6 | 634.7 | 20.38 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 172.235.43.210 |
| 74.34 | vless | 329.2 | 667.8 | 20.16 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 172.233.139.46 |
| 74.12 | vless | 303.8 | 573.1 | 20.74 | 0.0 | 10.0 | 11.39 | 17.26 | mheidari-all | 47.251.108.158 |
| 73.47 | vless | 371.8 | 563.6 | 19.17 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 195.123.240.65 |
| 73.06 | vless | 349.8 | 638.9 | 19.68 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 23.95.222.127 |
| 72.76 | vless | 368.3 | 695.6 | 19.25 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 137.175.82.40 |
| 72.62 | vless | 283.9 | 639.0 | 21.21 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 140.150.227.51 |
| 72.06 | vless | 402.8 | 772.8 | 18.45 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 198.251.78.29 |
| 71.69 | vless | 393.7 | 700.1 | 18.66 | 0.0 | 10.0 | 11.39 | 18.08 | Au1rxx-base64 | 15.204.97.216 |
| 71.62 | vless | 308.5 | 585.1 | 20.64 | 0.0 | 10.0 | 11.39 | 16.42 | Surfboard-tg-mixed | 2.27.160.4 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.964 | 0.896 | 270 | 1771 | prefer |
| Surfboard-tg-mixed | 0.957 | 0.889 | 63 | 7321 | prefer |
| mheidari-all | 0.956 | 0.883 | 111 | 23213 | prefer |
| ermaozi | 0.914 | 0.92 | 25 | 620 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5276 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 4981 | observe |
| Epodonios-all | 0.255 | None | 0 | 7814 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9326 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5999 | observe |
| barry-far-vless | 0.255 | None | 0 | 6241 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4357 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1771 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 8 |
| speed | ClientOSError | - | 7 |
| speed | TimeoutError | - | 7 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
