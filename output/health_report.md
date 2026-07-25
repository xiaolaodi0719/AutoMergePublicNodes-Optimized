# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-25 08:18:26 |
| 运行耗时 | 317.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78921 |
| 去重后节点 | 22393 |
| TCP 可达 | 3000 |
| 真实可用 | 749 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22393 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.4 |
| tcp | 31.3 |
| probe | 63.2 |
| real_test | 180.3 |
| generate | 36.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45182 |
| trojan | 13285 |
| vmess | 10183 |
| shadowsocks | 9687 |
| hysteria2 | 357 |
| socks | 73 |
| shadowsocksr | 71 |
| http | 50 |
| tuic | 17 |
| hysteria | 15 |
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
| 73.61 | trojan | 276.6 | 619.1 | 21.38 | 0.0 | 10.0 | 14.22 | 12.94 | mheidari-all | 163.245.196.68 |
| 69.89 | trojan | 373.3 | 540.9 | 19.14 | 0.0 | 10.0 | 14.22 | 15.3 | Surfboard-tg-mixed | 104.16.72.50 |
| 67.57 | vless | 248.5 | 513.4 | 22.03 | 0.0 | 10.0 | 4.9 | 15.3 | Surfboard-tg-mixed | 198.41.209.87 |
| 66.81 | trojan | 480.0 | 804.8 | 16.67 | 0.0 | 10.0 | 14.22 | 15.3 | Surfboard-tg-mixed | 208.103.161.170 |
| 65.53 | trojan | 572.5 | 817.7 | 14.53 | 0.0 | 10.0 | 14.22 | 15.3 | Surfboard-tg-mixed | 172.64.146.198 |
| 65.37 | trojan | 481.8 | 809.1 | 16.63 | 0.0 | 10.0 | 14.22 | 12.94 | mheidari-all | 8.6.112.6 |
| 65.18 | trojan | 496.4 | 512.5 | 16.29 | 0.0 | 10.0 | 14.22 | 15.3 | Surfboard-tg-mixed | 151.101.1.194 |
| 64.71 | shadowsocks | 280.0 | 708.6 | 21.3 | 0.0 | 10.0 | 10.83 | 6.58 | Au1rxx-base64 | 37.19.198.243 |
| 64.63 | shadowsocks | 283.2 | 717.1 | 21.22 | 0.0 | 10.0 | 10.83 | 6.58 | Au1rxx-base64 | 37.19.198.160 |
| 64.45 | trojan | 556.5 | 1040.6 | 14.9 | 0.0 | 10.0 | 14.22 | 15.3 | Surfboard-tg-mixed | 89.39.70.233 |
| 64.35 | trojan | 559.3 | 1039.2 | 14.83 | 0.0 | 9.93 | 14.22 | 15.3 | Surfboard-tg-mixed | 193.169.239.162 |
| 64.16 | trojan | 519.8 | 821.0 | 15.74 | 0.0 | 10.0 | 14.22 | 12.94 | mheidari-all | 172.64.147.227 |
| 63.76 | trojan | 433.7 | 419.8 | 17.74 | 0.0 | 9.51 | 14.22 | 12.94 | mheidari-all | 31.223.184.43 |
| 63.73 | shadowsocks | 322.4 | 817.9 | 20.32 | 0.0 | 10.0 | 10.83 | 6.58 | Au1rxx-base64 | 37.19.198.236 |
| 63.72 | trojan | 435.2 | 419.9 | 17.7 | 0.0 | 9.5 | 14.22 | 12.94 | mheidari-all | 95.85.94.199 |
| 63.72 | trojan | 592.4 | 1027.4 | 14.07 | 0.0 | 9.96 | 14.22 | 15.3 | Surfboard-tg-mixed | 89.39.70.159 |
| 63.67 | trojan | 435.5 | 423.9 | 17.7 | 0.0 | 9.46 | 14.22 | 12.94 | mheidari-all | 31.223.184.164 |
| 63.66 | trojan | 435.2 | 422.2 | 17.7 | 0.0 | 9.5 | 14.22 | 12.94 | mheidari-all | 95.85.94.112 |
| 63.56 | trojan | 437.6 | 425.7 | 17.65 | 0.0 | 9.39 | 14.22 | 12.94 | mheidari-all | 95.85.94.148 |
| 63.52 | vmess | 650.5 | 1825.6 | 12.72 | 0.0 | 10.0 | 10.0 | 15.3 | Surfboard-tg-mixed | 67.220.95.3 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.95 | 0.972 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.88 | 0.803 | 208 | 5838 | prefer |
| mheidari-all | 0.825 | 0.745 | 499 | 17378 | prefer |
| Surfboard-tg-mixed | 0.666 | 0.587 | 283 | 5473 | observe |
| Au1rxx-base64 | 0.566 | 1.0 | 8 | 432 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4879 | observe |
| Epodonios-all | 0.255 | None | 0 | 6614 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6346 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4256 | observe |
| barry-far-vless | 0.255 | None | 0 | 4927 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5009 | observe |
| nscl5-all | 0.255 | None | 0 | 2974 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 135 |
| speed | ClientOSError | - | 51 |
| cn-block | TimeoutError | - | 25 |
| geo | ClientOSError | - | 22 |
| 204 | ProxyError | - | 17 |
| speed | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
