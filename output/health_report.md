# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 02:09:06 |
| 运行耗时 | 275.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 82844 |
| 去重后节点 | 23635 |
| TCP 可达 | 3000 |
| 真实可用 | 553 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23635 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.3 |
| tcp | 35.3 |
| probe | 54.5 |
| real_test | 134.9 |
| generate | 45.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48567 |
| vmess | 13156 |
| trojan | 9878 |
| shadowsocks | 9737 |
| hysteria2 | 1307 |
| shadowsocksr | 70 |
| socks | 68 |
| http | 40 |
| hysteria | 13 |
| tuic | 8 |

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
| 83.82 | http | 190.1 | 495.6 | 23.38 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 83.8 | http | 190.9 | 497.5 | 23.36 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 83.77 | http | 192.1 | 488.7 | 23.33 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 83.72 | http | 194.2 | 508.8 | 23.28 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 83.34 | vless | 188.9 | 487.6 | 23.41 | 0.0 | 10.0 | 10.23 | 19.7 | Au1rxx-base64 | 179.255.148.66 |
| 83.24 | vless | 192.8 | 488.1 | 23.31 | 0.0 | 10.0 | 10.23 | 19.7 | Au1rxx-base64 | 186.241.106.97 |
| 82.08 | shadowsocks | 192.7 | 506.1 | 23.32 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 108.181.118.10 |
| 81.97 | shadowsocks | 218.9 | 512.7 | 22.71 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 173.244.56.6 |
| 81.24 | shadowsocks | 250.0 | 610.0 | 21.99 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 156.146.38.168 |
| 81.01 | shadowsocks | 260.2 | 634.9 | 21.75 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 156.146.38.169 |
| 80.84 | shadowsocks | 258.0 | 639.4 | 21.8 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 156.146.38.170 |
| 80.25 | shadowsocks | 254.3 | 621.3 | 21.89 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 156.146.38.167 |
| 79.64 | shadowsocks | 297.9 | 789.9 | 20.88 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 108.181.0.177 |
| 79.3 | shadowsocks | 204.6 | 510.2 | 23.04 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 173.244.56.9 |
| 78.6 | trojan | 274.4 | 569.6 | 21.43 | 0.0 | 10.0 | 13.2 | 19.7 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 78.57 | trojan | 273.8 | 574.0 | 21.44 | 0.0 | 10.0 | 13.2 | 19.7 | Au1rxx-base64 | 44.242.235.129 |
| 78.49 | vless | 221.0 | 520.6 | 22.66 | 0.0 | 10.0 | 10.23 | 19.7 | Au1rxx-base64 | 172.64.152.241 |
| 78.28 | vless | 191.1 | 489.2 | 23.35 | 0.0 | 10.0 | 10.23 | 19.7 | Au1rxx-base64 | 179.253.240.24 |
| 78.26 | hysteria2 | 333.3 | 744.7 | 20.06 | 0.0 | 10.0 | 12.69 | 19.7 | Au1rxx-base64 | 138.124.68.188 |
| 77.88 | shadowsocks | 179.8 | 471.5 | 23.62 | 0.0 | 10.0 | 13.56 | 19.7 | Au1rxx-base64 | 216.105.168.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.949 | 336 | 1540 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.662 | 151 | 6454 | prefer |
| mheidari-all | 0.58 | 0.5 | 204 | 17775 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 123 | observe |
| DeltaKronecker-all | 0.276 | 0.184 | 49 | 5347 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7127 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7538 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5209 | observe |
| barry-far-vless | 0.255 | None | 0 | 5532 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5127 | observe |
| Au1rxx-clash | 0.237 | None | 0 | 1540 | observe |
| nscl5-all | 0.235 | None | 0 | 1506 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 68 |
| speed | TimeoutError | - | 42 |
| cn-block | TimeoutError | - | 35 |
| speed | ClientOSError | - | 19 |
| geo | ClientOSError | - | 17 |
| 204 | TimeoutError | - | 17 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
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
