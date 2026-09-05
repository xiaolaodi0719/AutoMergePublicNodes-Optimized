# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 10:23:01 |
| 运行耗时 | 271.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83253 |
| 去重后节点 | 22135 |
| TCP 可达 | 3000 |
| 真实可用 | 509 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22135 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 36.9 |
| probe | 84.0 |
| real_test | 106.7 |
| generate | 35.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52816 |
| vmess | 11203 |
| shadowsocks | 9747 |
| trojan | 7845 |
| hysteria2 | 1292 |
| http | 146 |
| shadowsocksr | 131 |
| socks | 53 |
| hysteria | 10 |
| tuic | 10 |

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
| 82.78 | shadowsocks | 235.7 | 644.5 | 22.32 | 0.0 | 10.0 | 14.86 | 19.6 | Au1rxx-base64 | 37.19.198.244 |
| 82.55 | shadowsocks | 245.7 | 677.5 | 22.09 | 0.0 | 10.0 | 14.86 | 19.6 | Au1rxx-base64 | 37.19.198.243 |
| 82.49 | shadowsocks | 248.2 | 680.6 | 22.03 | 0.0 | 10.0 | 14.86 | 19.6 | Au1rxx-base64 | 37.19.198.160 |
| 81.79 | vless | 254.1 | 665.6 | 21.9 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 167.17.69.171 |
| 81.62 | vless | 261.4 | 637.6 | 21.73 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 138.124.60.146 |
| 81.5 | vless | 266.6 | 639.1 | 21.61 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.223 |
| 80.99 | vless | 288.6 | 769.0 | 21.1 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.133 |
| 80.93 | shadowsocks | 294.1 | 816.6 | 20.97 | 0.0 | 10.0 | 14.86 | 19.6 | Au1rxx-base64 | 38.180.135.156 |
| 80.78 | vless | 297.4 | 657.9 | 20.89 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.52 |
| 80.51 | vless | 309.1 | 705.5 | 20.62 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.184 |
| 80.46 | vless | 311.5 | 831.7 | 20.57 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.15 |
| 80.36 | vless | 315.6 | 716.6 | 20.47 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.232 |
| 80.18 | vless | 295.1 | 700.0 | 20.95 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 216.152.147.28 |
| 79.78 | vless | 340.7 | 926.8 | 19.89 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.104 |
| 79.69 | vless | 270.7 | 644.2 | 21.51 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.173 |
| 79.43 | vless | 355.7 | 841.8 | 19.54 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.225 |
| 79.36 | vless | 358.8 | 916.8 | 19.47 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.182 |
| 79.18 | vless | 366.7 | 1008.9 | 19.29 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 185.95.231.156 |
| 79.13 | vless | 295.4 | 667.8 | 20.94 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.231 |
| 79.07 | vless | 371.5 | 1009.3 | 19.18 | 0.0 | 10.0 | 10.29 | 19.6 | Au1rxx-base64 | 169.40.42.179 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Au1rxx-base64 | 0.959 | 0.889 | 271 | 1813 | prefer |
| Surfboard-tg-mixed | 0.866 | 0.789 | 180 | 7332 | prefer |
| mheidari-all | 0.862 | 0.787 | 108 | 15508 | prefer |
| DeltaKronecker-all | 0.645 | 0.571 | 21 | 6212 | observe |
| tg-oneclickvpnkeys | 0.482 | 1.0 | 6 | 118 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7793 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8561 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6108 | observe |
| barry-far-vless | 0.255 | None | 0 | 6302 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1813 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| geo | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 14 |
| 204 | ProxyError | - | 13 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| speed | ClientOSError | - | 4 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
