# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 20:29:52 |
| 运行耗时 | 567.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91271 |
| 去重后节点 | 25369 |
| TCP 可达 | 3000 |
| 真实可用 | 509 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25369 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.4 |
| tcp | 41.7 |
| probe | 223.6 |
| real_test | 212.1 |
| generate | 81.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54766 |
| vmess | 14438 |
| shadowsocks | 11272 |
| trojan | 8764 |
| hysteria2 | 1249 |
| http | 576 |
| shadowsocksr | 122 |
| socks | 64 |
| hysteria | 10 |
| tuic | 5 |
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
| 81.79 | vless | 248.5 | 699.0 | 22.03 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 79.141.172.154 |
| 81.3 | vless | 269.6 | 708.5 | 21.54 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.133 |
| 81.19 | shadowsocks | 224.9 | 620.4 | 22.57 | 0.0 | 10.0 | 13.8 | 18.82 | Au1rxx-base64 | 37.19.198.236 |
| 81.19 | vless | 264.2 | 683.3 | 21.66 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.15 |
| 81.1 | vless | 278.0 | 735.4 | 21.34 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.74 |
| 80.99 | vless | 282.9 | 689.6 | 21.23 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 216.152.147.28 |
| 80.97 | vless | 283.6 | 743.6 | 21.21 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.212 |
| 80.91 | vless | 286.5 | 636.4 | 21.15 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.232 |
| 80.7 | vless | 286.4 | 699.6 | 21.15 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.182 |
| 80.43 | vless | 306.9 | 814.7 | 20.67 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.202 |
| 80.41 | vless | 308.1 | 710.2 | 20.65 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.90 |
| 80.0 | vless | 325.8 | 841.0 | 20.24 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 66.70.179.198 |
| 79.9 | shadowsocks | 280.6 | 778.3 | 21.28 | 0.0 | 10.0 | 13.8 | 18.82 | Au1rxx-base64 | 37.19.198.160 |
| 79.85 | vless | 332.2 | 768.1 | 20.09 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.229 |
| 79.78 | vless | 335.1 | 791.1 | 20.02 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.184 |
| 79.68 | vless | 339.5 | 789.0 | 19.92 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.179 |
| 79.63 | shadowsocks | 292.5 | 822.7 | 21.01 | 0.0 | 10.0 | 13.8 | 18.82 | Au1rxx-base64 | 37.19.198.244 |
| 79.61 | vless | 342.7 | 942.8 | 19.85 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.52 |
| 79.39 | vless | 347.5 | 885.6 | 19.73 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.173 |
| 79.32 | vless | 354.9 | 845.0 | 19.56 | 0.0 | 10.0 | 10.94 | 18.82 | Au1rxx-base64 | 169.40.42.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.918 | 0.855 | 303 | 1650 | prefer |
| mheidari-all | 0.917 | 0.851 | 47 | 19269 | prefer |
| ermaozi | 0.856 | 0.875 | 24 | 250 | prefer |
| DeltaKronecker-all | 0.797 | 0.72 | 150 | 6421 | prefer |
| Surfboard-tg-mixed | 0.702 | 0.624 | 125 | 7211 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7761 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9098 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5765 | observe |
| barry-far-vless | 0.255 | None | 0 | 6077 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 3625 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 34 |
| geo | ClientOSError | - | 26 |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 10 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
