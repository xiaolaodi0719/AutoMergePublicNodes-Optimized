# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 07:12:13 |
| 运行耗时 | 290.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 78696 |
| 去重后节点 | 21961 |
| TCP 可达 | 3000 |
| 真实可用 | 718 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21961 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.4 |
| tcp | 34.7 |
| probe | 55.6 |
| real_test | 156.1 |
| generate | 36.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48970 |
| shadowsocks | 10350 |
| vmess | 10007 |
| trojan | 7779 |
| hysteria2 | 1199 |
| http | 164 |
| shadowsocksr | 129 |
| socks | 89 |
| hysteria | 7 |
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
| 84.33 | hysteria2 | 252.3 | 675.0 | 21.94 | 0.0 | 10.0 | 13.75 | 19.74 | Au1rxx-base64 | 159.223.157.129 |
| 82.39 | shadowsocks | 236.9 | 637.5 | 22.29 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 37.19.198.160 |
| 82.0 | shadowsocks | 253.8 | 688.2 | 21.9 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 37.19.198.243 |
| 81.77 | shadowsocks | 263.7 | 718.3 | 21.67 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 37.19.198.244 |
| 80.71 | shadowsocks | 256.5 | 649.5 | 21.84 | 0.0 | 9.02 | 14.36 | 19.74 | Au1rxx-base64 | 155.138.136.240 |
| 80.66 | vless | 307.0 | 825.9 | 20.67 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 137.184.218.169 |
| 80.52 | vless | 299.5 | 729.1 | 20.84 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 66.70.179.198 |
| 80.4 | vless | 318.3 | 860.7 | 20.41 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 79.127.243.217 |
| 80.36 | vless | 320.2 | 833.7 | 20.37 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 167.17.69.171 |
| 79.08 | vless | 288.8 | 728.7 | 21.09 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 138.124.60.146 |
| 78.95 | vless | 366.5 | 979.0 | 19.29 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 169.40.42.225 |
| 78.57 | vless | 397.4 | 944.3 | 18.58 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 169.40.42.173 |
| 78.55 | vless | 391.3 | 932.5 | 18.72 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 169.40.42.15 |
| 78.48 | vless | 352.2 | 859.7 | 19.63 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 216.152.147.28 |
| 78.44 | vless | 305.7 | 676.7 | 20.7 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 198.251.78.29 |
| 77.76 | shadowsocks | 283.7 | 652.1 | 21.21 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 156.146.38.170 |
| 77.2 | shadowsocks | 316.9 | 682.3 | 20.44 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 23.150.248.20 |
| 77.02 | vless | 342.0 | 783.9 | 19.86 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 169.40.42.35 |
| 76.87 | vless | 446.6 | 1159.2 | 17.44 | 0.0 | 10.0 | 10.25 | 19.74 | Au1rxx-base64 | 158.69.112.254 |
| 76.65 | shadowsocks | 485.1 | 1343.8 | 16.55 | 0.0 | 10.0 | 14.36 | 19.74 | Au1rxx-base64 | 142.4.216.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | 1.0 | 34 | 14629 | prefer |
| zhangkai | 0.988 | 0.991 | 113 | 144 | prefer |
| Au1rxx-base64 | 0.957 | 0.89 | 383 | 1718 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.799 | 149 | 6484 | prefer |
| DeltaKronecker-all | 0.376 | 0.295 | 370 | 5914 | observe |
| nscl5-all | 0.352 | 1.0 | 2 | 1008 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6867 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7231 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5385 | observe |
| barry-far-vless | 0.255 | None | 0 | 5530 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4097 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1728 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 134 |
| geo | ClientOSError | - | 60 |
| speed | ClientOSError | - | 38 |
| 204 | ProxyError | - | 31 |
| speed | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 8 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
