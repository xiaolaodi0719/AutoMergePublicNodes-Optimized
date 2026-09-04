# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 11:02:22 |
| 运行耗时 | 304.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83808 |
| 去重后节点 | 23398 |
| TCP 可达 | 3000 |
| 真实可用 | 589 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23398 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.4 |
| tcp | 37.8 |
| probe | 88.9 |
| real_test | 127.2 |
| generate | 43.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53128 |
| vmess | 11429 |
| shadowsocks | 9519 |
| trojan | 7915 |
| hysteria2 | 1458 |
| http | 141 |
| shadowsocksr | 129 |
| socks | 63 |
| tuic | 15 |
| hysteria | 10 |
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
| 82.26 | shadowsocks | 241.7 | 651.6 | 22.18 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 82.12 | shadowsocks | 247.8 | 668.8 | 22.04 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 37.19.198.160 |
| 81.73 | vless | 246.1 | 657.8 | 22.08 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 23.237.192.18 |
| 81.46 | vless | 257.9 | 671.8 | 21.81 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 204.48.20.223 |
| 81.15 | vless | 270.6 | 649.2 | 21.51 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 138.124.60.146 |
| 81.07 | vless | 274.8 | 690.9 | 21.42 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 137.184.218.169 |
| 80.75 | shadowsocks | 306.9 | 787.4 | 20.67 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | ca225.vpnbook.com |
| 80.34 | vless | 306.4 | 671.7 | 20.69 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.173 |
| 80.26 | vless | 299.3 | 649.9 | 20.85 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.225 |
| 80.23 | vless | 311.1 | 669.1 | 20.58 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.223 |
| 79.69 | vless | 334.4 | 860.0 | 20.04 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 172.105.104.54 |
| 79.66 | vless | 335.5 | 877.5 | 20.01 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.16 |
| 79.32 | shadowsocks | 316.8 | 814.9 | 20.44 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 38.180.135.156 |
| 79.29 | shadowsocks | 284.0 | 662.6 | 21.2 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 156.146.38.167 |
| 79.2 | shadowsocks | 244.4 | 659.7 | 22.12 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 37.19.198.236 |
| 78.85 | vless | 370.5 | 992.2 | 19.2 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.231 |
| 78.79 | shadowsocks | 286.5 | 656.1 | 21.15 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 156.146.38.170 |
| 78.76 | shadowsocks | 283.5 | 657.9 | 21.21 | 0.0 | 10.0 | 14.18 | 19.9 | Au1rxx-base64 | 156.146.38.168 |
| 78.75 | vless | 374.7 | 869.6 | 19.1 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 169.40.42.168 |
| 78.42 | vless | 334.9 | 812.3 | 20.03 | 0.0 | 10.0 | 9.75 | 19.9 | Au1rxx-base64 | 158.69.112.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Au1rxx-base64 | 0.945 | 0.877 | 367 | 1736 | prefer |
| Surfboard-tg-mixed | 0.922 | 0.846 | 156 | 7244 | prefer |
| mheidari-all | 0.828 | 0.752 | 129 | 15923 | prefer |
| DeltaKronecker-all | 0.561 | 0.48 | 25 | 7089 | observe |
| tg-oneclickvpnkeys | 0.443 | 1.0 | 5 | 87 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4810 | observe |
| Epodonios-all | 0.255 | None | 0 | 7763 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7993 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6120 | observe |
| barry-far-vless | 0.255 | None | 0 | 6426 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4123 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1736 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 22 |
| geo | ClientOSError | - | 19 |
| speed | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 17 |
| cn-block | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
