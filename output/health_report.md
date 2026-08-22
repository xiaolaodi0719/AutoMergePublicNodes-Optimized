# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 12:53:32 |
| 运行耗时 | 306.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 92293 |
| 去重后节点 | 23763 |
| TCP 可达 | 3000 |
| 真实可用 | 798 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23763 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 38.9 |
| probe | 60.9 |
| real_test | 158.6 |
| generate | 40.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52350 |
| trojan | 16168 |
| shadowsocks | 10804 |
| vmess | 10574 |
| hysteria2 | 1851 |
| shadowsocksr | 202 |
| http | 168 |
| socks | 116 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 81.31 | vless | 249.5 | 673.9 | 22.0 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 137.184.218.169 |
| 81.1 | shadowsocks | 237.4 | 610.0 | 22.28 | 0.0 | 10.0 | 13.67 | 19.4 | Au1rxx-base64 | 155.138.136.240 |
| 80.26 | vless | 295.1 | 661.9 | 20.95 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.104 |
| 79.8 | vless | 315.0 | 824.0 | 20.49 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.223 |
| 79.42 | vless | 331.4 | 844.9 | 20.11 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.202 |
| 79.41 | vless | 254.8 | 674.8 | 21.88 | 0.0 | 10.0 | 9.91 | 17.62 | Surfboard-tg-mixed | 169.40.42.75 |
| 79.22 | vless | 339.7 | 921.9 | 19.91 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.225 |
| 78.83 | vless | 356.8 | 855.5 | 19.52 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.15 |
| 78.78 | vless | 292.9 | 698.7 | 21.0 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 140.99.223.187 |
| 78.62 | vless | 365.9 | 867.4 | 19.31 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 169.40.42.212 |
| 78.54 | vless | 270.1 | 653.5 | 21.53 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 154.40.137.160 |
| 78.44 | vless | 373.7 | 1028.2 | 19.13 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 167.17.69.171 |
| 77.57 | shadowsocks | 314.9 | 750.6 | 20.49 | 0.0 | 10.0 | 13.67 | 19.4 | Au1rxx-base64 | 156.146.38.169 |
| 77.35 | shadowsocks | 306.3 | 730.0 | 20.69 | 0.0 | 10.0 | 13.67 | 19.4 | Au1rxx-base64 | 156.146.38.168 |
| 77.0 | vless | 365.9 | 1032.1 | 19.31 | 0.0 | 9.48 | 9.91 | 19.4 | Au1rxx-base64 | using.neobo-tooth.ru |
| 76.98 | shadowsocks | 339.0 | 826.3 | 19.93 | 0.0 | 10.0 | 13.67 | 19.4 | Au1rxx-base64 | 156.146.38.167 |
| 76.75 | shadowsocks | 395.6 | 690.5 | 18.62 | 0.0 | 10.0 | 13.67 | 19.4 | Au1rxx-base64 | 142.4.216.225 |
| 76.68 | hysteria2 | 235.1 | 646.1 | 22.34 | 0.0 | 10.0 | 13.64 | 13.8 | mheidari-all | 159.223.157.129 |
| 76.66 | vless | 325.3 | 679.5 | 20.25 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 140.99.223.19 |
| 76.25 | vless | 449.1 | 1189.7 | 17.38 | 0.0 | 10.0 | 9.91 | 19.4 | Au1rxx-base64 | 158.69.112.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 111 | 144 | prefer |
| Au1rxx-base64 | 0.993 | 0.928 | 499 | 1674 | prefer |
| Surfboard-tg-mixed | 0.886 | 0.81 | 168 | 6287 | prefer |
| mheidari-all | 0.615 | 0.536 | 153 | 21719 | observe |
| 10ium-HighSpeed | 0.345 | 1.0 | 2 | 839 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 3321 | observe |
| DeltaKronecker-all | 0.284 | 0.333 | 6 | 5015 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 161 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| Epodonios-all | 0.255 | None | 0 | 6868 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3984 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6876 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5093 | observe |
| barry-far-vless | 0.255 | None | 0 | 5403 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 44 |
| geo | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 18 |
| speed | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
