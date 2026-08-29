# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-29 16:35:06 |
| 运行耗时 | 262.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 78466 |
| 去重后节点 | 21213 |
| TCP 可达 | 3000 |
| 真实可用 | 553 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21213 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 34.2 |
| probe | 58.0 |
| real_test | 126.6 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48938 |
| vmess | 11164 |
| shadowsocks | 10534 |
| trojan | 6001 |
| hysteria2 | 1452 |
| http | 176 |
| shadowsocksr | 132 |
| socks | 59 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.28 | vless | 222.2 | 603.5 | 22.63 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 195.211.99.45 |
| 82.66 | vless | 249.1 | 616.3 | 22.01 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 198.251.78.29 |
| 82.61 | vless | 251.4 | 654.3 | 21.96 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 216.152.147.28 |
| 82.37 | hysteria2 | 316.0 | 816.7 | 20.46 | 0.0 | 10.0 | 13.85 | 19.16 | Au1rxx-base64 | 159.223.157.129 |
| 81.0 | vless | 285.9 | 684.5 | 21.16 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 204.48.20.223 |
| 80.99 | shadowsocks | 239.1 | 582.3 | 22.24 | 0.0 | 10.0 | 13.59 | 19.16 | Au1rxx-base64 | 156.146.38.170 |
| 80.54 | shadowsocks | 258.6 | 645.8 | 21.79 | 0.0 | 10.0 | 13.59 | 19.16 | Au1rxx-base64 | 156.146.38.169 |
| 80.5 | trojan | 254.0 | 593.3 | 21.9 | 0.0 | 10.0 | 12.44 | 19.16 | Au1rxx-base64 | 64.94.95.117 |
| 79.88 | vless | 369.2 | 963.4 | 19.23 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 79.127.243.217 |
| 79.67 | vless | 341.8 | 792.3 | 19.86 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.202 |
| 79.55 | vless | 383.5 | 976.2 | 18.9 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 130.107.73.148 |
| 79.34 | vless | 331.4 | 757.8 | 20.11 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.184 |
| 79.29 | vless | 299.6 | 727.9 | 20.84 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.16 |
| 79.27 | vless | 305.1 | 688.8 | 20.72 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.212 |
| 79.15 | vless | 381.5 | 933.4 | 18.95 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.223 |
| 78.84 | vless | 381.1 | 916.0 | 18.96 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.75 |
| 78.8 | shadowsocks | 257.3 | 656.2 | 21.82 | 0.0 | 10.0 | 13.59 | 19.16 | Au1rxx-base64 | 37.19.198.160 |
| 78.47 | vless | 286.7 | 687.5 | 21.14 | 0.0 | 10.0 | 11.49 | 19.16 | Au1rxx-base64 | 169.40.42.163 |
| 78.19 | shadowsocks | 246.9 | 599.1 | 22.06 | 0.0 | 10.0 | 13.59 | 16.54 | Surfboard-tg-mixed | 156.146.38.168 |
| 77.99 | shadowsocks | 255.6 | 640.2 | 21.86 | 0.0 | 10.0 | 13.59 | 16.54 | Surfboard-tg-mixed | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.936 | 358 | 1807 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.883 | 0.808 | 125 | 6877 | prefer |
| DeltaKronecker-all | 0.868 | 0.806 | 31 | 4926 | prefer |
| mheidari-all | 0.845 | 0.771 | 83 | 14622 | prefer |
| tg-oneclickvpnkeys | 0.364 | 1.0 | 3 | 156 | observe |
| nscl5-all | 0.283 | 1.0 | 1 | 700 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4635 | observe |
| Epodonios-all | 0.255 | None | 0 | 7290 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7426 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5686 | observe |
| barry-far-vless | 0.255 | None | 0 | 5725 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4012 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 18 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 14 |
| speed | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
