# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-29 22:11:49 |
| 运行耗时 | 454.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96969 |
| 去重后节点 | 27167 |
| TCP 可达 | 3000 |
| 真实可用 | 359 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27167 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 44.5 |
| probe | 219.6 |
| real_test | 137.1 |
| generate | 43.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59108 |
| vmess | 15092 |
| shadowsocks | 11359 |
| trojan | 9150 |
| hysteria2 | 1388 |
| http | 584 |
| shadowsocksr | 168 |
| socks | 73 |
| anytls | 24 |
| hysteria | 15 |
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
| 80.52 | hysteria2 | 272.1 | 737.4 | 21.48 | 0.0 | 10.0 | 14.4 | 18.74 | mheidari-all | 159.223.157.129 |
| 79.99 | vless | 239.1 | 688.6 | 22.24 | 0.0 | 8.88 | 10.61 | 18.26 | Au1rxx-base64 | 79.141.172.154 |
| 79.68 | vless | 256.6 | 696.1 | 21.84 | 0.0 | 8.97 | 10.61 | 18.26 | Au1rxx-base64 | 137.184.218.169 |
| 79.37 | shadowsocks | 261.9 | 686.2 | 21.71 | 0.0 | 10.0 | 13.42 | 18.74 | mheidari-all | 140.82.63.79 |
| 79.27 | vless | 269.1 | 659.5 | 21.55 | 0.0 | 8.85 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.133 |
| 79.24 | vless | 320.1 | 877.5 | 20.37 | 0.0 | 10.0 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.173 |
| 79.21 | vless | 277.4 | 618.0 | 21.36 | 0.0 | 8.98 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.52 |
| 79.17 | vless | 260.1 | 687.2 | 21.76 | 0.0 | 8.85 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.232 |
| 79.06 | vless | 286.5 | 724.1 | 21.15 | 0.0 | 9.04 | 10.61 | 18.26 | Au1rxx-base64 | 66.70.179.198 |
| 79.02 | vless | 279.8 | 693.8 | 21.3 | 0.0 | 8.85 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.212 |
| 78.46 | shadowsocks | 252.0 | 699.6 | 21.94 | 0.0 | 8.84 | 13.42 | 18.26 | Au1rxx-base64 | 37.19.198.243 |
| 78.35 | shadowsocks | 256.6 | 708.5 | 21.84 | 0.0 | 8.83 | 13.42 | 18.26 | Au1rxx-base64 | 37.19.198.236 |
| 78.33 | vless | 307.7 | 842.1 | 20.66 | 0.0 | 8.8 | 10.61 | 18.26 | Au1rxx-base64 | 159.89.87.21 |
| 78.06 | vless | 327.0 | 878.2 | 20.21 | 0.0 | 8.98 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.16 |
| 77.89 | vless | 290.8 | 777.3 | 21.05 | 0.0 | 8.97 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.231 |
| 77.81 | vless | 331.0 | 901.4 | 20.12 | 0.0 | 8.82 | 10.61 | 18.26 | Au1rxx-base64 | 185.95.231.233 |
| 77.46 | vless | 266.3 | 720.4 | 21.61 | 0.0 | 8.98 | 10.61 | 18.26 | Au1rxx-base64 | 136.0.213.120 |
| 77.42 | vless | 354.1 | 945.7 | 19.58 | 0.0 | 8.97 | 10.61 | 18.26 | Au1rxx-base64 | 169.40.42.104 |
| 77.4 | shadowsocks | 240.3 | 682.1 | 22.22 | 0.0 | 10.0 | 13.42 | 18.26 | Au1rxx-base64 | 47.90.153.88 |
| 77.33 | shadowsocks | 297.8 | 789.4 | 20.89 | 0.0 | 8.76 | 13.42 | 18.26 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.892 | 0.823 | 288 | 1792 | prefer |
| mheidari-all | 0.862 | 0.787 | 122 | 22763 | prefer |
| ermaozi | 0.605 | 0.6 | 30 | 291 | observe |
| tg-oneclickvpnkeys | 0.36 | 1.0 | 3 | 62 | observe |
| ermaozi-get_subscribe | 0.323 | 1.0 | 2 | 293 | observe |
| Surfboard-tg-mixed | 0.32 | 0.5 | 4 | 7082 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5314 | observe |
| Epodonios-all | 0.255 | None | 0 | 7556 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9172 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5695 | observe |
| barry-far-vless | 0.255 | None | 0 | 5942 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1792 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 31 |
| speed | TimeoutError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| 204 | ProxyConnectionError | - | 13 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
