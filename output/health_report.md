# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-26 19:56:37 |
| 运行耗时 | 245.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 89590 |
| 去重后节点 | 24386 |
| TCP 可达 | 3000 |
| 真实可用 | 481 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24386 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.3 |
| tcp | 39.2 |
| probe | 49.5 |
| real_test | 101.0 |
| generate | 49.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56371 |
| shadowsocks | 11842 |
| vmess | 11451 |
| trojan | 7341 |
| hysteria2 | 2158 |
| http | 172 |
| shadowsocksr | 138 |
| socks | 79 |
| anytls | 20 |
| hysteria | 13 |
| tuic | 5 |

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
| 82.29 | vless | 251.3 | 658.0 | 21.96 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.133 |
| 81.81 | vless | 272.1 | 722.1 | 21.48 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.184 |
| 81.75 | shadowsocks | 239.1 | 645.1 | 22.24 | 0.0 | 10.0 | 13.51 | 20.0 | mheidari-all | 37.19.198.236 |
| 81.75 | hysteria2 | 254.2 | 692.8 | 21.89 | 0.0 | 10.0 | 12.0 | 18.96 | Au1rxx-base64 | 159.223.157.129 |
| 81.65 | vless | 279.1 | 683.3 | 21.32 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.74 |
| 81.51 | shadowsocks | 249.7 | 691.8 | 22.0 | 0.0 | 10.0 | 13.51 | 20.0 | mheidari-all | 37.19.198.243 |
| 80.83 | vless | 314.2 | 706.9 | 20.5 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.231 |
| 80.79 | vless | 316.3 | 866.3 | 20.46 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 137.184.218.169 |
| 80.75 | vless | 317.7 | 858.8 | 20.42 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.232 |
| 80.5 | vless | 328.5 | 626.1 | 20.17 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 47.89.186.170 |
| 80.46 | vless | 279.3 | 642.5 | 21.31 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 195.211.99.45 |
| 80.46 | vless | 283.9 | 702.4 | 21.21 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 66.70.179.198 |
| 80.32 | vless | 336.3 | 931.9 | 19.99 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 79.127.243.217 |
| 80.24 | vless | 249.2 | 648.1 | 22.01 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.35 |
| 80.24 | vless | 253.6 | 654.3 | 21.91 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.163 |
| 80.13 | shadowsocks | 264.5 | 728.1 | 21.66 | 0.0 | 10.0 | 13.51 | 18.96 | Au1rxx-base64 | 37.19.198.244 |
| 79.98 | shadowsocks | 294.2 | 802.8 | 20.97 | 0.0 | 10.0 | 13.51 | 20.0 | mheidari-all | 38.180.135.156 |
| 79.96 | vless | 352.1 | 880.1 | 19.63 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.104 |
| 79.84 | vless | 277.0 | 763.8 | 21.37 | 0.0 | 9.24 | 11.37 | 18.96 | Au1rxx-base64 | using.neobo-tooth.ru |
| 79.84 | vless | 357.0 | 840.3 | 19.51 | 0.0 | 10.0 | 11.37 | 18.96 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | 0.883 | 351 | 1979 | prefer |
| Surfboard-tg-mixed | 0.958 | 0.887 | 80 | 6645 | prefer |
| zhangkai | 0.875 | 0.905 | 21 | 144 | prefer |
| mheidari-all | 0.65 | 0.571 | 133 | 19290 | observe |
| DeltaKronecker-all | 0.349 | 0.667 | 3 | 6107 | observe |
| tg-oneclickvpnkeys | 0.32 | 1.0 | 2 | 218 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4825 | observe |
| Epodonios-all | 0.255 | None | 0 | 7011 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7313 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5444 | observe |
| barry-far-vless | 0.255 | None | 0 | 5698 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4011 | observe |
| Au1rxx-clash | 0.254 | None | 0 | 1979 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 38 |
| speed | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 12 |
| cn-block | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
