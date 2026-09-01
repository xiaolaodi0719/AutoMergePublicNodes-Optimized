# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 16:26:03 |
| 运行耗时 | 308.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 83812 |
| 去重后节点 | 24692 |
| TCP 可达 | 3000 |
| 真实可用 | 660 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24692 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.5 |
| tcp | 40.7 |
| probe | 88.7 |
| real_test | 129.9 |
| generate | 41.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52365 |
| vmess | 11789 |
| shadowsocks | 10254 |
| trojan | 7631 |
| hysteria2 | 1392 |
| http | 145 |
| shadowsocksr | 130 |
| socks | 83 |
| hysteria | 9 |
| tuic | 9 |
| anytls | 5 |

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
| 81.41 | vless | 272.0 | 592.1 | 21.48 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 195.211.99.45 |
| 80.89 | shadowsocks | 240.4 | 616.0 | 22.21 | 0.0 | 10.0 | 14.22 | 18.46 | Au1rxx-base64 | 156.146.38.170 |
| 79.96 | shadowsocks | 237.4 | 618.3 | 22.28 | 0.0 | 10.0 | 14.22 | 18.46 | Au1rxx-base64 | 156.146.38.167 |
| 79.91 | vless | 269.8 | 663.8 | 21.53 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 195.211.99.49 |
| 78.95 | shadowsocks | 251.7 | 612.7 | 21.95 | 0.0 | 10.0 | 14.22 | 16.78 | mheidari-all | 156.146.38.168 |
| 78.83 | shadowsocks | 257.1 | 597.3 | 21.83 | 0.0 | 10.0 | 14.22 | 16.78 | mheidari-all | 156.146.38.169 |
| 78.34 | shadowsocks | 289.4 | 673.0 | 21.08 | 0.0 | 10.0 | 14.22 | 18.46 | Au1rxx-base64 | 37.19.198.243 |
| 78.02 | shadowsocks | 302.8 | 688.5 | 20.77 | 0.0 | 10.0 | 14.22 | 18.46 | Au1rxx-base64 | 37.19.198.160 |
| 77.09 | hysteria2 | 255.1 | 558.9 | 21.87 | 0.0 | 10.0 | 9.55 | 18.46 | Au1rxx-base64 | 66.94.121.46 |
| 76.92 | shadowsocks | 273.3 | 667.7 | 21.45 | 0.0 | 10.0 | 14.22 | 16.6 | Surfboard-tg-mixed | 23.150.248.20 |
| 76.52 | vless | 260.7 | 525.8 | 21.74 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 64.23.229.123 |
| 76.4 | vless | 319.7 | 687.9 | 20.38 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 172.239.67.156 |
| 76.1 | vless | 367.8 | 881.7 | 19.26 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 216.152.147.28 |
| 76.02 | vless | 340.5 | 736.9 | 19.9 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 2.24.124.64 |
| 76.01 | vless | 327.6 | 710.2 | 20.19 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 204.48.20.223 |
| 75.91 | shadowsocks | 283.8 | 672.7 | 21.21 | 0.0 | 10.0 | 14.22 | 16.78 | mheidari-all | 37.19.198.236 |
| 75.88 | vless | 251.8 | 578.8 | 21.95 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | us5-r.link-t7.com |
| 75.87 | vless | 341.1 | 654.2 | 19.88 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 172.233.139.46 |
| 75.86 | vless | 349.2 | 677.9 | 19.7 | 0.0 | 10.0 | 11.47 | 18.46 | Au1rxx-base64 | 172.233.156.118 |
| 75.66 | shadowsocks | 299.1 | 616.7 | 20.85 | 0.0 | 10.0 | 14.22 | 18.46 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | 0.91 | 398 | 1760 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| mheidari-all | 0.953 | 0.877 | 155 | 17557 | prefer |
| Surfboard-tg-mixed | 0.869 | 0.793 | 169 | 6964 | prefer |
| DeltaKronecker-all | 0.352 | 0.5 | 6 | 7294 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7367 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7657 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5838 | observe |
| barry-far-vless | 0.255 | None | 0 | 6013 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4013 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 20 |
| cn-block | ClientOSError | - | 15 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 8 |
| cn-block | ProxyError | - | 4 |
| geo | TimeoutError | - | 4 |
| speed | ClientOSError | - | 4 |
| speed | TimeoutError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48555: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
