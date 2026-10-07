# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-07 23:03:35 |
| 运行耗时 | 471.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98461 |
| 去重后节点 | 27482 |
| TCP 可达 | 3000 |
| 真实可用 | 448 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27482 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 46.7 |
| probe | 188.7 |
| real_test | 160.4 |
| generate | 69.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58111 |
| vmess | 15548 |
| shadowsocks | 11720 |
| trojan | 10668 |
| hysteria2 | 1522 |
| http | 561 |
| shadowsocksr | 171 |
| socks | 100 |
| anytls | 34 |
| hysteria | 17 |
| tuic | 9 |

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
| 81.01 | shadowsocks | 247.8 | 625.1 | 22.04 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 80.96 | shadowsocks | 249.9 | 623.1 | 21.99 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 156.146.38.167 |
| 80.66 | shadowsocks | 244.8 | 630.6 | 22.11 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 80.16 | hysteria2 | 287.9 | 727.3 | 21.11 | 0.0 | 10.0 | 11.25 | 19.3 | Au1rxx-base64 | 129.213.91.185 |
| 78.84 | vless | 332.4 | 709.0 | 20.08 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 169.40.42.229 |
| 78.56 | shadowsocks | 312.1 | 758.3 | 20.55 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 37.19.198.236 |
| 78.02 | shadowsocks | 308.8 | 752.1 | 20.63 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 37.19.198.244 |
| 77.86 | vless | 311.3 | 703.1 | 20.57 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 169.40.42.16 |
| 77.6 | shadowsocks | 306.1 | 750.2 | 20.69 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 37.19.198.160 |
| 77.58 | vless | 327.4 | 745.6 | 20.2 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 137.184.218.169 |
| 77.25 | shadowsocks | 310.7 | 760.4 | 20.59 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 37.19.198.243 |
| 77.16 | vless | 279.3 | 553.5 | 21.31 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 47.251.108.158 |
| 76.4 | vless | 434.8 | 957.4 | 17.71 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 169.40.42.104 |
| 76.21 | hysteria2 | 300.3 | 296.6 | 20.83 | 3.88 | 8.67 | 11.25 | 19.3 | Au1rxx-base64 | open.2ml.bid |
| 76.19 | vless | 295.5 | 650.1 | 20.94 | 0.0 | 10.0 | 11.09 | 17.24 | mheidari-all | 216.227.161.95 |
| 76.18 | vless | 396.5 | 923.2 | 18.6 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 159.89.87.21 |
| 76.16 | hysteria2 | 295.2 | 318.1 | 20.94 | 3.07 | 9.31 | 11.25 | 19.3 | Au1rxx-base64 | open.w2m.ink |
| 76.1 | vless | 299.0 | 605.5 | 20.86 | 0.0 | 10.0 | 11.09 | 19.3 | Au1rxx-base64 | 107.173.237.146 |
| 76.1 | hysteria2 | 346.7 | 879.9 | 19.75 | 0.0 | 10.0 | 11.25 | 19.3 | Au1rxx-base64 | 159.223.157.129 |
| 76.02 | shadowsocks | 315.0 | 724.3 | 20.49 | 0.0 | 10.0 | 13.67 | 19.3 | Au1rxx-base64 | 140.82.63.79 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.944 | 0.881 | 42 | 7189 | prefer |
| Au1rxx-base64 | 0.943 | 0.872 | 345 | 1824 | prefer |
| mheidari-all | 0.925 | 0.853 | 95 | 23169 | prefer |
| ermaozi | 0.636 | 0.615 | 39 | 664 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5138 | observe |
| Epodonios-all | 0.255 | None | 0 | 7553 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9262 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5706 | observe |
| barry-far-vless | 0.255 | None | 0 | 5859 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4431 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1824 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| speed | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 11 |
| speed | TimeoutError | - | 8 |
| geo | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 6 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
