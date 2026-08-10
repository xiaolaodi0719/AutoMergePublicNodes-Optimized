# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-10 07:54:16 |
| 运行耗时 | 245.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 87298 |
| 去重后节点 | 24721 |
| TCP 可达 | 3000 |
| 真实可用 | 469 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24721 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 0.9 |
| tcp | 34.8 |
| probe | 60.7 |
| real_test | 109.6 |
| generate | 31.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52267 |
| vmess | 13132 |
| trojan | 10539 |
| shadowsocks | 9727 |
| hysteria2 | 1405 |
| shadowsocksr | 73 |
| socks | 68 |
| http | 40 |
| anytls | 26 |
| hysteria | 14 |
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
| 81.65 | hysteria2 | 239.7 | 668.7 | 22.23 | 0.0 | 9.08 | 12.5 | 18.94 | Au1rxx-base64 | 159.223.157.129 |
| 81.37 | hysteria2 | 256.0 | 712.5 | 21.85 | 0.0 | 9.08 | 12.5 | 18.94 | Au1rxx-base64 | 138.124.68.188 |
| 81.36 | hysteria2 | 248.7 | 695.8 | 22.02 | 0.0 | 8.9 | 12.5 | 18.94 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 81.31 | shadowsocks | 229.3 | 631.8 | 22.47 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 37.19.198.243 |
| 81.11 | shadowsocks | 237.8 | 662.8 | 22.27 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 37.19.198.244 |
| 79.54 | shadowsocks | 305.9 | 865.3 | 20.7 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 37.19.198.236 |
| 77.23 | shadowsocks | 327.7 | 582.8 | 20.19 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 156.146.38.167 |
| 77.13 | shadowsocks | 314.2 | 738.7 | 20.5 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 156.146.38.168 |
| 76.7 | vless | 263.7 | 686.7 | 21.67 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 167.17.69.171 |
| 76.4 | shadowsocks | 318.4 | 752.6 | 20.41 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 156.146.38.170 |
| 76.23 | shadowsocks | 327.5 | 784.7 | 20.2 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 156.146.38.169 |
| 75.4 | vless | 277.0 | 685.9 | 21.37 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 169.40.42.182 |
| 75.17 | shadowsocks | 473.1 | 1353.8 | 16.83 | 0.0 | 10.0 | 13.9 | 18.94 | Au1rxx-base64 | 68.168.222.210 |
| 74.96 | vless | 338.9 | 804.8 | 19.93 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 169.40.42.133 |
| 74.95 | vless | 339.5 | 865.3 | 19.92 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 169.40.42.15 |
| 74.85 | vless | 344.0 | 874.7 | 19.82 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 216.152.147.28 |
| 74.55 | hysteria2 | 357.5 | 670.1 | 19.5 | 0.0 | 10.0 | 12.5 | 18.94 | Au1rxx-base64 | 31.76.113.32 |
| 74.15 | vless | 374.0 | 905.1 | 19.12 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 169.40.42.192 |
| 73.96 | http | 349.2 | 615.4 | 19.69 | 0.0 | 10.0 | 14.42 | 19.12 | zhangkai | 138.199.35.217 |
| 73.89 | vless | 310.7 | 731.2 | 20.59 | 0.0 | 10.0 | 6.09 | 18.94 | Au1rxx-base64 | 128.254.207.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Au1rxx-base64 | 0.886 | 0.818 | 440 | 1742 | prefer |
| Surfboard-tg-mixed | 0.716 | 0.638 | 105 | 6647 | prefer |
| DeltaKronecker-all | 0.439 | 0.351 | 37 | 5881 | observe |
| nscl5-all | 0.313 | 1.0 | 1 | 1442 | observe |
| mheidari-all | 0.289 | 0.195 | 41 | 20373 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7338 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3994 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7807 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5394 | observe |
| barry-far-vless | 0.255 | None | 0 | 5713 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5191 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1742 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 45 |
| geo | TimeoutError | - | 38 |
| 204 | TimeoutError | - | 27 |
| geo | ClientOSError | - | 16 |
| 204 | ProxyError | - | 16 |
| speed | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
