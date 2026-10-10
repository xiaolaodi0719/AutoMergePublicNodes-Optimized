# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 12:25:54 |
| 运行耗时 | 814.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97803 |
| 去重后节点 | 27173 |
| TCP 可达 | 3000 |
| 真实可用 | 499 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27173 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.0 |
| tcp | 46.9 |
| probe | 315.1 |
| real_test | 368.5 |
| generate | 77.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57316 |
| vmess | 15803 |
| shadowsocks | 11808 |
| trojan | 10476 |
| hysteria2 | 1561 |
| http | 548 |
| shadowsocksr | 167 |
| socks | 71 |
| anytls | 28 |
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
| 84.51 | hysteria2 | 227.2 | 226.4 | 22.52 | 6.51 | 9.91 | 13.93 | 19.54 | Au1rxx-base64 | 45.32.10.7 |
| 83.1 | hysteria2 | 226.5 | 228.5 | 22.54 | 6.43 | 9.51 | 13.93 | 19.54 | Au1rxx-base64 | vp3.yysyy.online |
| 80.83 | shadowsocks | 256.5 | 631.5 | 21.84 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 156.146.38.169 |
| 80.79 | shadowsocks | 258.2 | 630.9 | 21.8 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 156.146.38.168 |
| 80.74 | shadowsocks | 260.5 | 641.8 | 21.75 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 156.146.38.170 |
| 80.73 | shadowsocks | 260.7 | 642.7 | 21.74 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 156.146.38.167 |
| 80.11 | shadowsocks | 241.5 | 561.1 | 22.19 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 5.78.51.123 |
| 79.35 | hysteria2 | 321.5 | 752.1 | 20.34 | 0.0 | 10.0 | 13.93 | 19.54 | Au1rxx-base64 | 129.213.91.185 |
| 79.04 | vless | 237.3 | 638.1 | 22.28 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 107.173.237.146 |
| 78.78 | hysteria2 | 288.5 | 357.1 | 21.1 | 1.61 | 9.79 | 13.93 | 19.54 | Au1rxx-base64 | 158.101.148.79 |
| 78.44 | vless | 212.7 | 504.3 | 22.85 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 47.251.108.158 |
| 76.7 | shadowsocks | 294.8 | 640.3 | 20.95 | 0.0 | 10.0 | 13.45 | 19.54 | Au1rxx-base64 | 149.22.95.183 |
| 76.58 | vless | 214.4 | 509.2 | 22.82 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 137.175.82.40 |
| 76.52 | vless | 266.8 | 588.3 | 21.6 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 15.204.97.216 |
| 76.34 | vless | 296.7 | 530.9 | 20.91 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 23.95.222.127 |
| 76.29 | vless | 313.2 | 799.2 | 20.53 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 104.17.98.5 |
| 75.9 | trojan | 288.5 | 615.4 | 21.1 | 0.0 | 9.08 | 14.02 | 19.54 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 75.77 | trojan | 292.8 | 624.4 | 21.0 | 0.0 | 9.04 | 14.02 | 19.54 | Au1rxx-base64 | alert-titmouse.rooster465.autos |
| 75.5 | vless | 271.8 | 598.5 | 21.49 | 0.0 | 10.0 | 7.22 | 19.54 | Au1rxx-base64 | 15.204.97.197 |
| 75.08 | hysteria2 | 286.3 | 359.2 | 21.15 | 1.53 | 6.46 | 13.93 | 19.54 | Au1rxx-base64 | open.2ml.bid |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.958 | 0.888 | 365 | 1820 | prefer |
| DeltaKronecker-all | 0.847 | 0.786 | 28 | 5009 | prefer |
| mheidari-all | 0.846 | 0.778 | 45 | 23754 | prefer |
| Surfboard-tg-mixed | 0.744 | 0.667 | 135 | 7103 | prefer |
| ermaozi-get_subscribe | 0.426 | 1.0 | 4 | 653 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7579 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9335 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5620 | observe |
| barry-far-vless | 0.255 | None | 0 | 5861 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4347 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 24 |
| speed | TimeoutError | - | 11 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 8 |
| 204 | ClientOSError | - | 7 |
| geo | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
