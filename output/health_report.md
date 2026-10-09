# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-09 05:48:16 |
| 运行耗时 | 1111.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98040 |
| 去重后节点 | 27748 |
| TCP 可达 | 3000 |
| 真实可用 | 502 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27748 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 47.4 |
| probe | 402.0 |
| real_test | 566.4 |
| generate | 86.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57640 |
| vmess | 15607 |
| shadowsocks | 12058 |
| trojan | 10515 |
| hysteria2 | 1416 |
| http | 480 |
| shadowsocksr | 174 |
| socks | 90 |
| anytls | 31 |
| hysteria | 17 |
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
| 81.47 | shadowsocks | 251.2 | 636.1 | 21.96 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 156.146.38.169 |
| 81.44 | hysteria2 | 283.1 | 712.5 | 21.23 | 0.0 | 10.0 | 12.19 | 19.52 | Au1rxx-base64 | 129.213.91.185 |
| 81.21 | shadowsocks | 261.1 | 627.4 | 21.73 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 156.146.38.168 |
| 79.53 | vless | 273.4 | 546.7 | 21.45 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 47.251.108.158 |
| 79.45 | shadowsocks | 297.5 | 739.0 | 20.89 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 37.19.198.244 |
| 79.33 | shadowsocks | 296.8 | 732.7 | 20.91 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 37.19.198.243 |
| 79.17 | vless | 347.6 | 678.2 | 19.73 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 169.40.42.173 |
| 79.15 | vless | 379.5 | 777.1 | 18.99 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 169.40.42.90 |
| 79.0 | hysteria2 | 293.4 | 279.6 | 20.99 | 4.51 | 9.63 | 12.19 | 19.52 | Au1rxx-base64 | 158.101.148.79 |
| 78.92 | shadowsocks | 303.7 | 751.7 | 20.75 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 37.19.198.236 |
| 78.86 | shadowsocks | 234.6 | 596.3 | 22.35 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 156.146.38.170 |
| 78.73 | hysteria2 | 281.1 | 277.3 | 21.27 | 4.6 | 9.01 | 12.19 | 19.52 | Au1rxx-base64 | open.2ml.bid |
| 78.65 | vless | 346.8 | 752.9 | 19.75 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 66.70.179.198 |
| 78.26 | vless | 375.4 | 841.4 | 19.09 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 2.24.124.64 |
| 78.17 | shadowsocks | 319.0 | 678.1 | 20.39 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 140.82.63.79 |
| 77.9 | vless | 398.8 | 945.6 | 18.55 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 137.184.218.169 |
| 77.71 | shadowsocks | 284.1 | 744.4 | 21.2 | 0.0 | 10.0 | 13.99 | 19.52 | Au1rxx-base64 | 156.146.38.167 |
| 77.65 | vless | 418.0 | 888.0 | 18.1 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 169.40.42.202 |
| 77.56 | vless | 355.1 | 786.4 | 19.56 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 107.173.237.146 |
| 77.41 | vless | 332.1 | 754.2 | 20.09 | 0.0 | 10.0 | 12.51 | 19.52 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.979 | 0.911 | 360 | 1761 | prefer |
| Surfboard-tg-mixed | 0.83 | 0.759 | 54 | 7069 | prefer |
| ermaozi-get_subscribe | 0.564 | 0.542 | 48 | 607 | observe |
| zhangkai | 0.555 | 1.0 | 8 | 144 | observe |
| DeltaKronecker-all | 0.376 | 0.333 | 15 | 5197 | observe |
| mheidari-all | 0.332 | 0.251 | 367 | 23125 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7569 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9901 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5581 | observe |
| barry-far-vless | 0.255 | None | 0 | 5823 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 166 |
| speed | TimeoutError | - | 60 |
| geo | ClientOSError | - | 30 |
| 204 | ProxyError | - | 27 |
| speed | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyConnectionError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
