# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 04:00:00 |
| 运行耗时 | 356.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 97417 |
| 去重后节点 | 25568 |
| TCP 可达 | 3000 |
| 真实可用 | 634 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25568 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 41.9 |
| probe | 94.2 |
| real_test | 175.0 |
| generate | 36.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62163 |
| vmess | 12656 |
| shadowsocks | 11035 |
| trojan | 9206 |
| hysteria2 | 1953 |
| http | 144 |
| shadowsocksr | 125 |
| socks | 65 |
| anytls | 38 |
| hysteria | 18 |
| tuic | 14 |

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
| 79.53 | vless | 268.7 | 696.4 | 21.56 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 216.152.147.28 |
| 79.45 | shadowsocks | 260.8 | 651.5 | 21.74 | 0.0 | 10.0 | 13.99 | 17.72 | Au1rxx-base64 | 37.19.198.244 |
| 79.04 | shadowsocks | 278.4 | 713.0 | 21.33 | 0.0 | 10.0 | 13.99 | 17.72 | Au1rxx-base64 | 37.19.198.160 |
| 79.03 | shadowsocks | 258.8 | 620.7 | 21.79 | 0.0 | 10.0 | 13.99 | 17.54 | Surfboard-tg-mixed | 156.146.38.168 |
| 78.59 | vless | 301.9 | 735.4 | 20.79 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.74 |
| 78.18 | shadowsocks | 307.8 | 781.3 | 20.65 | 0.0 | 10.0 | 13.99 | 17.54 | Surfboard-tg-mixed | 156.146.38.170 |
| 78.06 | shadowsocks | 252.4 | 623.5 | 21.94 | 0.0 | 8.93 | 13.99 | 17.72 | Au1rxx-base64 | 156.146.38.169 |
| 77.87 | vless | 296.2 | 708.0 | 20.92 | 0.0 | 8.98 | 10.25 | 17.72 | Au1rxx-base64 | 204.48.20.223 |
| 77.34 | vless | 304.9 | 724.5 | 20.72 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 66.70.179.198 |
| 76.81 | vless | 310.3 | 709.5 | 20.6 | 0.0 | 8.98 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.182 |
| 76.73 | vless | 276.0 | 268.1 | 21.39 | 4.94 | 9.63 | 10.25 | 17.54 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.59 | shadowsocks | 320.8 | 835.6 | 20.35 | 0.0 | 9.03 | 13.99 | 17.72 | Au1rxx-base64 | 38.180.135.156 |
| 76.48 | shadowsocks | 317.9 | 753.1 | 20.42 | 0.0 | 8.86 | 13.99 | 17.72 | Au1rxx-base64 | 156.146.38.167 |
| 76.34 | vless | 388.4 | 862.3 | 18.79 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.104 |
| 76.09 | vless | 315.7 | 769.8 | 20.47 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.232 |
| 75.93 | vless | 361.3 | 847.3 | 19.41 | 0.0 | 9.05 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.225 |
| 75.61 | shadowsocks | 397.2 | 1062.9 | 18.58 | 0.0 | 10.0 | 13.99 | 17.54 | Surfboard-tg-mixed | 15.204.246.108 |
| 75.34 | vless | 342.7 | 792.9 | 19.85 | 0.0 | 10.0 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.212 |
| 75.18 | vless | 320.2 | 732.3 | 20.37 | 0.0 | 9.02 | 10.25 | 17.72 | Au1rxx-base64 | 169.40.42.163 |
| 75.14 | vless | 415.9 | 1082.6 | 18.15 | 0.0 | 9.02 | 10.25 | 17.72 | Au1rxx-base64 | 185.95.231.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Au1rxx-base64 | 0.939 | 0.868 | 318 | 1827 | prefer |
| Surfboard-tg-mixed | 0.851 | 0.773 | 203 | 7381 | prefer |
| tg-oneclickvpnkeys | 0.482 | 1.0 | 6 | 132 | observe |
| mheidari-all | 0.372 | 0.292 | 583 | 22409 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 6965 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4887 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8608 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6075 | observe |
| barry-far-vless | 0.255 | None | 0 | 6398 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4087 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1827 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 189 |
| geo | ClientOSError | - | 82 |
| cn-block | ClientOSError | - | 78 |
| speed | TimeoutError | - | 56 |
| speed | ClientOSError | - | 38 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 17 |
| 204 | ProxyConnectionError | - | 15 |
| 204 | ProxyError | - | 12 |
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
