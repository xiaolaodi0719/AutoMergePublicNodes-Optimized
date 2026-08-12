# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-12 07:44:34 |
| 运行耗时 | 298.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 88266 |
| 去重后节点 | 23638 |
| TCP 可达 | 3000 |
| 真实可用 | 606 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23638 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.2 |
| tcp | 35.4 |
| probe | 61.7 |
| real_test | 152.2 |
| generate | 40.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51864 |
| vmess | 13955 |
| trojan | 10556 |
| shadowsocks | 10066 |
| hysteria2 | 1448 |
| http | 159 |
| socks | 100 |
| shadowsocksr | 72 |
| tuic | 18 |
| hysteria | 16 |
| anytls | 12 |

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
| 81.66 | hysteria2 | 273.6 | 674.8 | 21.44 | 0.0 | 10.0 | 13.04 | 18.28 | Au1rxx-base64 | 159.223.157.129 |
| 80.07 | hysteria2 | 297.6 | 747.0 | 20.89 | 0.0 | 10.0 | 13.04 | 18.28 | Au1rxx-base64 | 138.124.68.188 |
| 79.82 | http | 334.8 | 756.8 | 20.03 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.25 |
| 79.5 | hysteria2 | 292.3 | 711.8 | 21.01 | 0.0 | 8.17 | 13.04 | 18.28 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 79.01 | http | 321.4 | 715.7 | 20.34 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.33 |
| 78.9 | http | 282.0 | 571.5 | 21.25 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.220 |
| 78.88 | http | 284.2 | 560.4 | 21.2 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.213 |
| 78.81 | http | 285.3 | 570.5 | 21.17 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.204 |
| 78.81 | http | 290.4 | 576.4 | 21.05 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.212 |
| 78.8 | http | 330.7 | 723.9 | 20.12 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.8 |
| 78.77 | http | 283.8 | 573.0 | 21.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.214 |
| 78.71 | http | 285.7 | 576.9 | 21.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.206 |
| 78.7 | http | 283.7 | 571.7 | 21.21 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.195 |
| 78.65 | http | 286.2 | 582.6 | 21.15 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 78.42 | http | 308.4 | 648.6 | 20.64 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |
| 78.11 | http | 328.1 | 760.5 | 20.18 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.41 |
| 78.09 | http | 344.6 | 793.4 | 19.8 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.5 |
| 78.08 | http | 320.2 | 678.8 | 20.36 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.208 |
| 78.03 | http | 318.7 | 673.0 | 20.4 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.209 |
| 77.97 | http | 349.6 | 769.9 | 19.69 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 156.146.59.23 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | 1.0 | 128 | 159 | prefer |
| Au1rxx-base64 | 0.91 | 0.846 | 422 | 1632 | prefer |
| Surfboard-tg-mixed | 0.604 | 0.524 | 103 | 5943 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4568 | observe |
| DeltaKronecker-all | 0.318 | 0.235 | 17 | 4975 | observe |
| mheidari-all | 0.313 | 0.231 | 255 | 20330 | observe |
| tg-shadowproxy66 | 0.312 | 1.0 | 2 | 12 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5328 | observe |
| Epodonios-all | 0.255 | None | 0 | 6602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7652 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4919 | observe |
| barry-far-vless | 0.255 | None | 0 | 5267 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1632 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 98 |
| geo | ClientOSError | - | 91 |
| speed | TimeoutError | - | 50 |
| speed | ClientOSError | - | 33 |
| 204 | ProxyError | - | 20 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
