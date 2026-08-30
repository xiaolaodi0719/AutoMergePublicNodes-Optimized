# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 04:49:04 |
| 运行耗时 | 266.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 86359 |
| 去重后节点 | 21983 |
| TCP 可达 | 3000 |
| 真实可用 | 689 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21983 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 54.7 |
| real_test | 131.8 |
| generate | 38.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52493 |
| vmess | 10882 |
| trojan | 10618 |
| shadowsocks | 10398 |
| hysteria2 | 1589 |
| http | 180 |
| shadowsocksr | 129 |
| socks | 54 |
| tuic | 8 |
| hysteria | 7 |
| anytls | 1 |

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
| 84.13 | vless | 217.6 | 589.3 | 22.74 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 195.211.99.45 |
| 84.04 | vless | 221.6 | 607.6 | 22.65 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 195.211.98.214 |
| 82.54 | vless | 286.3 | 697.3 | 21.15 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 167.17.69.171 |
| 82.43 | vless | 247.9 | 646.2 | 22.04 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 172.105.104.54 |
| 82.41 | vless | 291.8 | 725.5 | 21.02 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 47.89.186.170 |
| 81.92 | vless | 313.2 | 647.2 | 20.53 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 169.40.42.163 |
| 81.71 | vless | 316.3 | 724.0 | 20.46 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 169.40.42.95 |
| 81.25 | shadowsocks | 241.3 | 591.6 | 22.19 | 0.0 | 10.0 | 13.76 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 81.04 | vless | 216.6 | 594.5 | 22.76 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 195.211.99.49 |
| 81.04 | vless | 275.8 | 676.3 | 21.39 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 38.77.133.141 |
| 80.92 | shadowsocks | 255.8 | 650.1 | 21.86 | 0.0 | 10.0 | 13.76 | 19.3 | Au1rxx-base64 | 37.19.198.160 |
| 80.88 | vless | 357.9 | 931.0 | 19.49 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 79.127.243.217 |
| 80.76 | vless | 363.1 | 972.3 | 19.37 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 216.152.147.28 |
| 80.73 | vless | 339.6 | 732.0 | 19.92 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 169.40.42.15 |
| 80.54 | vless | 318.2 | 728.5 | 20.41 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 169.40.42.52 |
| 80.46 | vless | 343.9 | 851.5 | 19.82 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 137.184.218.169 |
| 80.04 | shadowsocks | 293.5 | 739.6 | 20.98 | 0.0 | 10.0 | 13.76 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 79.95 | shadowsocks | 254.4 | 646.3 | 21.89 | 0.0 | 10.0 | 13.76 | 19.3 | Au1rxx-base64 | 37.19.198.244 |
| 79.92 | shadowsocks | 298.7 | 771.2 | 20.86 | 0.0 | 10.0 | 13.76 | 19.3 | Au1rxx-base64 | 37.19.198.243 |
| 79.7 | vless | 343.9 | 823.8 | 19.82 | 0.0 | 10.0 | 12.09 | 19.3 | Au1rxx-base64 | 158.69.112.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.95 | 377 | 1825 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.96 | 0.89 | 73 | 6910 | prefer |
| DeltaKronecker-all | 0.846 | 0.772 | 92 | 4926 | prefer |
| mheidari-all | 0.668 | 0.588 | 289 | 18105 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 169 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7323 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3992 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7549 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |
| nscl5-all | 0.255 | None | 0 | 4310 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1825 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 42 |
| geo | ClientOSError | - | 40 |
| speed | TimeoutError | - | 31 |
| cn-block | TimeoutError | - | 20 |
| speed | ClientOSError | - | 13 |
| 204 | ProxyError | - | 8 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
