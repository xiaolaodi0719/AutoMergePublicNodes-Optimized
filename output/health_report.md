# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 13:04:42 |
| 运行耗时 | 250.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85362 |
| 去重后节点 | 23924 |
| TCP 可达 | 3000 |
| 真实可用 | 480 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23924 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 35.9 |
| probe | 48.1 |
| real_test | 113.8 |
| generate | 46.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51087 |
| vmess | 13122 |
| trojan | 9932 |
| shadowsocks | 9544 |
| hysteria2 | 1439 |
| socks | 75 |
| shadowsocksr | 70 |
| http | 39 |
| anytls | 26 |
| hysteria | 16 |
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
| 82.13 | hysteria2 | 274.2 | 671.6 | 21.43 | 0.0 | 8.59 | 13.33 | 19.88 | Au1rxx-base64 | 159.223.157.129 |
| 81.08 | shadowsocks | 240.7 | 596.0 | 22.2 | 0.0 | 8.79 | 14.21 | 19.88 | Au1rxx-base64 | 156.146.38.167 |
| 80.85 | shadowsocks | 248.4 | 615.1 | 22.03 | 0.0 | 8.73 | 14.21 | 19.88 | Au1rxx-base64 | 156.146.38.168 |
| 80.81 | shadowsocks | 255.6 | 645.8 | 21.86 | 0.0 | 8.86 | 14.21 | 19.88 | Au1rxx-base64 | 156.146.38.169 |
| 80.8 | hysteria2 | 338.3 | 869.0 | 19.95 | 0.0 | 8.64 | 13.33 | 19.88 | Au1rxx-base64 | 138.124.68.188 |
| 80.78 | shadowsocks | 251.3 | 649.7 | 21.96 | 0.0 | 8.73 | 14.21 | 19.88 | Au1rxx-base64 | 156.146.38.170 |
| 80.23 | hysteria2 | 325.2 | 825.4 | 20.25 | 0.0 | 7.77 | 13.33 | 19.88 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 79.1 | trojan | 427.1 | 1055.6 | 17.89 | 0.0 | 10.0 | 14.33 | 19.88 | Au1rxx-base64 | 64.94.95.117 |
| 77.7 | http | 282.5 | 570.4 | 21.24 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.217 |
| 77.66 | http | 286.8 | 579.8 | 21.14 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.207 |
| 77.44 | http | 286.1 | 579.4 | 21.15 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.214 |
| 77.42 | trojan | 499.8 | 1342.4 | 16.21 | 0.0 | 10.0 | 14.33 | 19.88 | Au1rxx-base64 | 64.94.95.115 |
| 77.0 | http | 290.6 | 586.7 | 21.05 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.199 |
| 76.92 | trojan | 521.4 | 1435.9 | 15.71 | 0.0 | 10.0 | 14.33 | 19.88 | Au1rxx-base64 | 64.94.95.118 |
| 76.84 | vless | 371.0 | 901.1 | 19.19 | 0.0 | 8.56 | 9.21 | 19.88 | Au1rxx-base64 | 216.152.147.28 |
| 76.57 | vless | 282.0 | 555.5 | 21.25 | 0.0 | 10.0 | 9.21 | 19.88 | Au1rxx-base64 | 179.255.148.66 |
| 76.57 | shadowsocks | 354.9 | 881.7 | 19.56 | 0.0 | 8.86 | 14.21 | 19.88 | Au1rxx-base64 | 37.19.198.244 |
| 76.34 | trojan | 546.5 | 1488.3 | 15.13 | 0.0 | 10.0 | 14.33 | 19.88 | Au1rxx-base64 | 64.94.95.114 |
| 76.12 | shadowsocks | 287.2 | 702.6 | 21.13 | 0.0 | 8.79 | 14.21 | 19.88 | Au1rxx-base64 | 37.19.198.243 |
| 76.04 | vless | 251.6 | 638.3 | 21.95 | 0.0 | 10.0 | 9.21 | 19.88 | Au1rxx-base64 | 193.233.205.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.973 | 0.907 | 410 | 1704 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.772 | 0.695 | 105 | 6480 | prefer |
| mheidari-all | 0.286 | 0.197 | 66 | 20170 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 77 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7128 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7369 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5320 | observe |
| barry-far-vless | 0.255 | None | 0 | 5659 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5130 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1704 | observe |
| nscl5-all | 0.235 | None | 0 | 1506 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| speed | TimeoutError | - | 27 |
| 204 | TimeoutError | - | 16 |
| cn-block | TimeoutError | - | 13 |
| geo | TimeoutError | - | 12 |
| 204 | ProxyError | - | 11 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
