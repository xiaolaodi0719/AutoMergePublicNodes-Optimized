# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-06 14:28:04 |
| 运行耗时 | 235.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 89832 |
| 去重后节点 | 24596 |
| TCP 可达 | 3000 |
| 真实可用 | 475 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24596 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 37.5 |
| probe | 49.9 |
| real_test | 97.6 |
| generate | 41.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52487 |
| vmess | 13308 |
| trojan | 12017 |
| shadowsocks | 10213 |
| hysteria2 | 1473 |
| socks | 171 |
| shadowsocksr | 74 |
| anytls | 30 |
| http | 24 |
| hysteria | 21 |
| tuic | 14 |

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
| 83.07 | trojan | 264.5 | 666.1 | 21.66 | 0.0 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 44.246.163.102 |
| 81.94 | trojan | 313.3 | 817.5 | 20.53 | 0.0 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 44.242.235.129 |
| 81.33 | vless | 187.9 | 522.9 | 23.43 | 0.0 | 10.0 | 8.18 | 19.72 | Au1rxx-base64 | 64.49.38.6 |
| 81.18 | shadowsocks | 209.0 | 562.4 | 22.94 | 0.0 | 9.38 | 13.14 | 19.72 | Au1rxx-base64 | 149.22.95.183 |
| 80.71 | trojan | 331.4 | 839.2 | 20.11 | 0.0 | 9.19 | 14.19 | 19.72 | Au1rxx-base64 | 44.244.3.114 |
| 80.3 | trojan | 348.5 | 883.1 | 19.71 | 0.0 | 9.18 | 14.19 | 19.72 | Au1rxx-base64 | 35.91.251.124 |
| 79.6 | trojan | 327.7 | 858.8 | 20.19 | 0.0 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 35.86.90.51 |
| 77.83 | trojan | 361.3 | 281.5 | 19.41 | 4.44 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 54.199.202.238 |
| 77.8 | shadowsocks | 259.2 | 271.5 | 21.78 | 4.82 | 9.38 | 13.14 | 19.72 | Au1rxx-base64 | 149.22.87.240 |
| 77.66 | trojan | 309.3 | 315.7 | 20.62 | 3.16 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 13.231.232.184 |
| 77.63 | trojan | 311.4 | 317.0 | 20.57 | 3.11 | 9.97 | 14.19 | 19.72 | Au1rxx-base64 | 57.180.13.78 |
| 77.57 | trojan | 310.0 | 318.5 | 20.6 | 3.06 | 9.99 | 14.19 | 19.72 | Au1rxx-base64 | 57.180.27.225 |
| 77.5 | trojan | 311.0 | 320.3 | 20.58 | 2.99 | 9.99 | 14.19 | 19.72 | Au1rxx-base64 | 13.230.118.96 |
| 77.48 | trojan | 312.0 | 320.2 | 20.56 | 2.99 | 9.96 | 14.19 | 19.72 | Au1rxx-base64 | 52.194.230.221 |
| 77.43 | trojan | 313.5 | 318.3 | 20.52 | 3.06 | 9.96 | 14.19 | 19.72 | Au1rxx-base64 | 18.181.164.216 |
| 77.4 | trojan | 313.6 | 320.2 | 20.52 | 2.99 | 9.97 | 14.19 | 19.72 | Au1rxx-base64 | 43.207.140.98 |
| 77.38 | trojan | 313.0 | 321.9 | 20.53 | 2.93 | 10.0 | 14.19 | 19.72 | Au1rxx-base64 | 13.192.168.51 |
| 77.34 | trojan | 314.3 | 322.7 | 20.5 | 2.9 | 9.97 | 14.19 | 19.72 | Au1rxx-base64 | 18.178.132.111 |
| 77.28 | trojan | 313.0 | 324.9 | 20.53 | 2.82 | 9.98 | 14.19 | 19.72 | Au1rxx-base64 | 3.112.223.141 |
| 77.27 | trojan | 314.7 | 323.2 | 20.49 | 2.88 | 9.97 | 14.19 | 19.72 | Au1rxx-base64 | 43.207.155.134 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.999 | 0.938 | 403 | 1577 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.584 | 0.504 | 127 | 5904 | observe |
| DeltaKronecker-all | 0.503 | 0.583 | 12 | 5897 | observe |
| mheidari-all | 0.389 | 0.385 | 13 | 20767 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 5184 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5219 | observe |
| Epodonios-all | 0.255 | None | 0 | 6534 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7693 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5092 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5212 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.24 | None | 0 | 1621 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 26 |
| 204 | ProxyError | - | 20 |
| geo | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| speed | TimeoutError | - | 3 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
