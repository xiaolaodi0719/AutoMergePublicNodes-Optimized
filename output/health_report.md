# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 04:12:41 |
| 运行耗时 | 705.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82098 |
| 去重后节点 | 23215 |
| TCP 可达 | 3000 |
| 真实可用 | 576 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23215 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 37.9 |
| probe | 277.9 |
| real_test | 296.4 |
| generate | 85.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49951 |
| vmess | 11889 |
| shadowsocks | 9945 |
| trojan | 8271 |
| hysteria2 | 1194 |
| http | 648 |
| shadowsocksr | 123 |
| socks | 64 |
| hysteria | 8 |
| anytls | 3 |
| tuic | 2 |

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
| 80.66 | vless | 229.3 | 605.7 | 22.47 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 195.123.235.177 |
| 80.22 | shadowsocks | 245.1 | 686.6 | 22.1 | 0.0 | 10.0 | 13.56 | 18.56 | Au1rxx-base64 | 37.19.198.236 |
| 79.84 | shadowsocks | 261.7 | 732.0 | 21.72 | 0.0 | 10.0 | 13.56 | 18.56 | Au1rxx-base64 | 37.19.198.160 |
| 79.68 | vless | 271.8 | 651.2 | 21.49 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.173 |
| 79.58 | shadowsocks | 229.8 | 637.9 | 22.46 | 0.0 | 10.0 | 13.56 | 18.56 | Au1rxx-base64 | 37.19.198.244 |
| 79.5 | vless | 279.3 | 738.6 | 21.31 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.95 |
| 79.15 | vless | 294.7 | 657.2 | 20.96 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.231 |
| 79.15 | vless | 294.7 | 735.1 | 20.96 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.229 |
| 79.08 | vless | 297.8 | 673.0 | 20.89 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.184 |
| 79.03 | vless | 299.8 | 668.7 | 20.84 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.179 |
| 78.83 | vless | 308.5 | 790.3 | 20.64 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 66.70.179.198 |
| 78.7 | vless | 314.2 | 797.3 | 20.51 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.163 |
| 78.38 | vless | 327.6 | 812.0 | 20.19 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.212 |
| 78.29 | vless | 331.5 | 843.1 | 20.1 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.75 |
| 78.21 | shadowsocks | 310.7 | 797.7 | 20.59 | 0.0 | 10.0 | 13.56 | 18.56 | Au1rxx-base64 | 38.180.135.156 |
| 78.11 | hysteria2 | 241.2 | 657.0 | 22.2 | 0.0 | 10.0 | 14.25 | 12.76 | mheidari-all | 159.223.157.129 |
| 78.06 | vless | 298.7 | 669.0 | 20.86 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.52 |
| 78.06 | hysteria2 | 305.1 | 602.4 | 20.71 | 0.0 | 10.0 | 14.25 | 18.56 | Au1rxx-base64 | 66.94.121.46 |
| 77.88 | vless | 349.2 | 892.8 | 19.69 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.225 |
| 77.68 | vless | 358.2 | 850.8 | 19.49 | 0.0 | 10.0 | 9.63 | 18.56 | Au1rxx-base64 | 169.40.42.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | 0.898 | 313 | 1702 | prefer |
| ermaozi | 0.759 | 0.755 | 49 | 358 | prefer |
| Surfboard-tg-mixed | 0.756 | 0.677 | 254 | 7266 | prefer |
| roosterkid-openproxylist-v2ray | 0.555 | 1.0 | 8 | 150 | observe |
| mheidari-all | 0.521 | 0.44 | 109 | 13937 | observe |
| DeltaKronecker-all | 0.483 | 0.4 | 65 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8930 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5822 | observe |
| barry-far-vless | 0.255 | None | 0 | 6112 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1703 | observe |
| ermaozi-get_subscribe | 0.227 | 0.25 | 12 | 387 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 79 |
| speed | TimeoutError | - | 46 |
| geo | ClientOSError | - | 32 |
| 204 | ProxyError | - | 28 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 16 |
| cn-block | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | parse | TimeoutError | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
