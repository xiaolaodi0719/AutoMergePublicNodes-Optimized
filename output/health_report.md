# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-08 23:18:48 |
| 运行耗时 | 622.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98440 |
| 去重后节点 | 27653 |
| TCP 可达 | 3000 |
| 真实可用 | 418 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27653 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 47.1 |
| probe | 245.1 |
| real_test | 243.9 |
| generate | 76.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58517 |
| vmess | 15769 |
| shadowsocks | 11976 |
| trojan | 10049 |
| hysteria2 | 1413 |
| http | 410 |
| shadowsocksr | 162 |
| socks | 83 |
| anytls | 34 |
| hysteria | 16 |
| tuic | 11 |

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
| 81.95 | hysteria2 | 278.6 | 718.0 | 21.33 | 0.0 | 10.0 | 12.86 | 19.26 | Au1rxx-base64 | 129.213.91.185 |
| 80.81 | shadowsocks | 241.0 | 592.6 | 22.2 | 0.0 | 10.0 | 13.35 | 19.26 | Au1rxx-base64 | 156.146.38.169 |
| 79.16 | vless | 299.0 | 651.1 | 20.86 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 195.123.235.177 |
| 78.2 | vless | 366.6 | 775.0 | 19.29 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.235 |
| 77.69 | shadowsocks | 300.4 | 744.6 | 20.82 | 0.0 | 10.0 | 13.35 | 19.26 | Au1rxx-base64 | 37.19.198.243 |
| 77.31 | vless | 271.2 | 546.0 | 21.5 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 47.251.108.158 |
| 77.28 | vless | 340.0 | 761.9 | 19.91 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 66.70.179.198 |
| 77.1 | vless | 301.8 | 604.8 | 20.79 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 195.123.240.65 |
| 76.9 | hysteria2 | 400.1 | 693.6 | 18.52 | 0.0 | 10.0 | 12.86 | 19.26 | Au1rxx-base64 | 66.94.121.46 |
| 76.88 | vless | 332.9 | 776.2 | 20.07 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.163 |
| 76.84 | shadowsocks | 333.1 | 824.9 | 20.07 | 0.0 | 10.0 | 13.35 | 19.26 | Au1rxx-base64 | 37.19.198.244 |
| 76.55 | vless | 321.2 | 758.0 | 20.34 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.133 |
| 76.19 | vless | 397.5 | 998.5 | 18.58 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 185.95.231.156 |
| 76.18 | vless | 403.2 | 958.4 | 18.45 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 2.24.124.64 |
| 76.11 | vless | 327.6 | 625.3 | 20.19 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 23.95.222.127 |
| 76.11 | vless | 371.8 | 810.8 | 19.17 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.212 |
| 76.08 | vless | 325.2 | 691.4 | 20.25 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.184 |
| 76.01 | vless | 358.1 | 736.1 | 19.49 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 169.40.42.16 |
| 75.83 | vless | 321.5 | 608.1 | 20.33 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 15.204.97.197 |
| 75.7 | vless | 327.6 | 654.2 | 20.2 | 0.0 | 10.0 | 11.45 | 19.26 | Au1rxx-base64 | 15.204.97.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | 0.905 | 326 | 1827 | prefer |
| mheidari-all | 0.933 | 0.863 | 73 | 23588 | prefer |
| Surfboard-tg-mixed | 0.913 | 0.85 | 40 | 7092 | prefer |
| zhangkai | 0.646 | 0.652 | 23 | 144 | observe |
| DeltaKronecker-all | 0.593 | 1.0 | 7 | 5197 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5081 | observe |
| Epodonios-all | 0.255 | None | 0 | 7650 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9660 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5580 | observe |
| barry-far-vless | 0.255 | None | 0 | 5923 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4362 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 13 |
| speed | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 8 |
| 204 | TimeoutError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
