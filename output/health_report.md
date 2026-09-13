# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-13 04:25:50 |
| 运行耗时 | 1004.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 94343 |
| 去重后节点 | 25322 |
| TCP 可达 | 3000 |
| 真实可用 | 550 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25322 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| geo | 1.4 |
| tcp | 41.7 |
| probe | 327.2 |
| real_test | 545.8 |
| generate | 81.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57573 |
| vmess | 13632 |
| shadowsocks | 11015 |
| trojan | 9033 |
| hysteria2 | 2192 |
| http | 669 |
| shadowsocksr | 124 |
| socks | 64 |
| hysteria | 15 |
| anytls | 14 |
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
| 81.93 | vless | 234.3 | 609.1 | 22.35 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 195.123.235.177 |
| 81.31 | vless | 261.2 | 730.3 | 21.73 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 47.89.186.170 |
| 80.97 | vless | 275.9 | 738.2 | 21.39 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.16 |
| 80.7 | vless | 287.6 | 765.6 | 21.12 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.90 |
| 80.52 | vless | 295.5 | 736.6 | 20.94 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.133 |
| 80.47 | vless | 297.6 | 807.3 | 20.89 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.163 |
| 80.42 | vless | 299.6 | 802.5 | 20.84 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.182 |
| 80.34 | vless | 303.2 | 844.2 | 20.76 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 137.184.218.169 |
| 80.25 | vless | 306.9 | 824.2 | 20.67 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.179 |
| 80.15 | vless | 311.4 | 718.1 | 20.57 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.212 |
| 80.05 | shadowsocks | 222.5 | 605.9 | 22.63 | 0.0 | 10.0 | 13.1 | 18.32 | Au1rxx-base64 | 198.98.53.130 |
| 79.92 | vless | 321.4 | 870.3 | 20.34 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.168 |
| 79.84 | vless | 324.9 | 814.7 | 20.26 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.202 |
| 79.81 | vless | 239.6 | 654.7 | 22.23 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 159.89.87.21 |
| 79.8 | vless | 326.7 | 888.0 | 20.22 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.104 |
| 79.29 | vless | 348.5 | 930.2 | 19.71 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.173 |
| 79.13 | vless | 355.5 | 983.7 | 19.55 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 185.95.231.156 |
| 79.04 | vless | 260.5 | 681.8 | 21.75 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.15 |
| 78.82 | vless | 265.2 | 698.5 | 21.64 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.35 |
| 78.79 | vless | 273.6 | 668.4 | 21.44 | 0.0 | 10.0 | 11.26 | 18.32 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | 0.86 | 372 | 1653 | prefer |
| ermaozi | 0.777 | 0.783 | 23 | 436 | prefer |
| Surfboard-tg-mixed | 0.701 | 0.624 | 93 | 7432 | prefer |
| mheidari-all | 0.344 | 0.264 | 569 | 20709 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 141 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4793 | observe |
| Epodonios-all | 0.255 | None | 0 | 7895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8736 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6027 | observe |
| barry-far-vless | 0.255 | None | 0 | 6259 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1653 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 165 |
| geo | ClientOSError | - | 100 |
| speed | TimeoutError | - | 81 |
| speed | ClientOSError | - | 66 |
| cn-block | ClientOSError | - | 39 |
| 204 | ProxyError | - | 33 |
| 204 | TimeoutError | - | 31 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | exit-country | CN | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
