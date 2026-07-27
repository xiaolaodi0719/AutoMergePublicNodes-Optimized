# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 19:47:31 |
| 运行耗时 | 323.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85905 |
| 去重后节点 | 22931 |
| TCP 可达 | 3000 |
| 真实可用 | 771 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22931 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 31.6 |
| probe | 65.9 |
| real_test | 182.5 |
| generate | 35.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49138 |
| trojan | 15528 |
| vmess | 10394 |
| shadowsocks | 9897 |
| hysteria2 | 680 |
| shadowsocksr | 105 |
| socks | 66 |
| http | 63 |
| hysteria | 15 |
| anytls | 11 |
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
| 81.32 | hysteria2 | 258.7 | 653.0 | 21.79 | 0.0 | 10.0 | 12.69 | 19.94 | Au1rxx-base64 | 159.223.157.129 |
| 80.92 | shadowsocks | 258.5 | 629.5 | 21.79 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 37.19.198.244 |
| 80.8 | shadowsocks | 255.0 | 617.6 | 21.87 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 156.146.38.167 |
| 80.64 | shadowsocks | 270.8 | 677.9 | 21.51 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 37.19.198.160 |
| 79.71 | trojan | 287.4 | 645.2 | 21.12 | 0.0 | 10.0 | 13.59 | 19.94 | Au1rxx-base64 | 163.245.196.68 |
| 79.58 | shadowsocks | 316.6 | 817.5 | 20.45 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 37.19.198.243 |
| 78.74 | shadowsocks | 266.6 | 672.8 | 21.61 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 37.19.198.236 |
| 77.0 | trojan | 488.5 | 1380.0 | 16.47 | 0.0 | 10.0 | 13.59 | 19.94 | Au1rxx-base64 | 148.72.168.35 |
| 75.6 | trojan | 509.9 | 1356.9 | 15.98 | 0.0 | 10.0 | 13.59 | 19.94 | Au1rxx-base64 | 153.75.250.171 |
| 75.59 | shadowsocks | 251.4 | 673.1 | 21.96 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 50.114.177.134 |
| 75.45 | shadowsocks | 287.4 | 530.3 | 21.12 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 108.181.0.177 |
| 75.02 | shadowsocks | 300.8 | 558.0 | 20.82 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 173.244.56.9 |
| 75.01 | trojan | 352.5 | 874.4 | 19.62 | 0.0 | 10.0 | 13.59 | 14.88 | DeltaKronecker-all | 64.74.163.118 |
| 74.44 | shadowsocks | 336.7 | 726.4 | 19.98 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 108.181.57.93 |
| 74.24 | shadowsocks | 299.0 | 558.7 | 20.86 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 173.244.56.6 |
| 74.14 | hysteria2 | 387.7 | 715.1 | 18.8 | 0.0 | 9.91 | 12.69 | 19.94 | Au1rxx-base64 | 62.210.124.146 |
| 73.83 | shadowsocks | 317.8 | 588.3 | 20.42 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 108.181.118.10 |
| 73.36 | shadowsocks | 563.7 | 1544.0 | 14.73 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 185.196.61.82 |
| 72.41 | shadowsocks | 244.3 | 605.2 | 22.12 | 0.0 | 10.0 | 13.19 | 19.94 | Au1rxx-base64 | 198.98.53.130 |
| 72.35 | hysteria2 | 431.2 | 1168.4 | 17.8 | 0.0 | 7.92 | 12.69 | 19.94 | Au1rxx-base64 | usa1.spectrumproxy.shop |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.995 | 0.921 | 139 | 19371 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| Au1rxx-base64 | 0.976 | 0.917 | 448 | 1499 | prefer |
| Surfboard-tg-mixed | 0.644 | 0.568 | 37 | 5739 | observe |
| DeltaKronecker-all | 0.537 | 0.457 | 326 | 5643 | observe |
| xiaoji235-airport-v2ray-all | 0.349 | 0.667 | 3 | 3959 | observe |
| tg-Farah_VPN | 0.263 | 1.0 | 1 | 200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6710 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3964 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6251 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4648 | observe |
| barry-far-vless | 0.255 | None | 0 | 5170 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4997 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 68 |
| speed | ClientOSError | - | 36 |
| cn-block | TimeoutError | - | 33 |
| 204 | ProxyError | - | 29 |
| 204 | TimeoutError | - | 29 |
| geo | ClientOSError | - | 23 |
| speed | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36196: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
