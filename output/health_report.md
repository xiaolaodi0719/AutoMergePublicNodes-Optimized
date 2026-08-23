# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 18:41:18 |
| 运行耗时 | 306.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 77715 |
| 去重后节点 | 21484 |
| TCP 可达 | 3000 |
| 真实可用 | 638 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21484 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 12.9 |
| geo | 1.4 |
| tcp | 35.0 |
| probe | 57.6 |
| real_test | 149.0 |
| generate | 50.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47971 |
| shadowsocks | 10225 |
| vmess | 10110 |
| trojan | 7824 |
| hysteria2 | 1182 |
| http | 165 |
| shadowsocksr | 129 |
| socks | 100 |
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
| 83.01 | vless | 206.9 | 545.8 | 22.99 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 15.204.97.216 |
| 82.97 | vless | 208.6 | 550.9 | 22.95 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 15.204.97.197 |
| 82.39 | shadowsocks | 183.3 | 504.0 | 23.53 | 0.0 | 10.0 | 13.58 | 19.28 | Au1rxx-base64 | 94.72.127.55 |
| 81.81 | shadowsocks | 208.6 | 565.3 | 22.95 | 0.0 | 10.0 | 13.58 | 19.28 | mheidari-all | 149.22.95.183 |
| 81.75 | shadowsocks | 200.5 | 544.2 | 23.14 | 0.0 | 10.0 | 13.58 | 19.28 | Au1rxx-base64 | 154.12.240.141 |
| 81.73 | trojan | 208.4 | 487.8 | 22.95 | 0.0 | 10.0 | 12.0 | 19.28 | Au1rxx-base64 | 35.92.245.6 |
| 81.2 | vless | 285.1 | 776.2 | 21.18 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 15.204.97.209 |
| 81.12 | shadowsocks | 227.5 | 533.1 | 22.51 | 0.0 | 10.0 | 13.58 | 19.28 | Au1rxx-base64 | 94.72.127.58 |
| 80.48 | trojan | 262.4 | 664.8 | 21.7 | 0.0 | 10.0 | 12.0 | 19.28 | Au1rxx-base64 | 44.251.158.80 |
| 80.47 | shadowsocks | 250.2 | 501.1 | 21.99 | 0.0 | 10.0 | 13.58 | 19.28 | Au1rxx-base64 | 154.53.63.33 |
| 80.45 | trojan | 263.9 | 672.2 | 21.67 | 0.0 | 10.0 | 12.0 | 19.28 | Au1rxx-base64 | 35.91.251.124 |
| 78.02 | shadowsocks | 254.3 | 523.8 | 21.89 | 0.0 | 10.0 | 13.58 | 19.28 | mheidari-all | 108.181.118.10 |
| 77.91 | vless | 427.3 | 1140.8 | 17.89 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 51.81.223.225 |
| 77.23 | vless | 288.8 | 793.2 | 21.09 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 15.204.97.195 |
| 76.92 | trojan | 210.4 | 503.1 | 22.91 | 0.0 | 5.23 | 12.0 | 19.28 | Au1rxx-base64 | obliging-louse.rooster465.autos |
| 76.88 | vless | 330.3 | 295.2 | 20.13 | 3.93 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 46.250.250.149 |
| 76.48 | shadowsocks | 299.1 | 629.3 | 20.86 | 0.0 | 10.0 | 13.58 | 19.28 | Au1rxx-base64 | 108.181.0.177 |
| 76.08 | vless | 315.2 | 326.7 | 20.48 | 2.75 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 103.76.85.213 |
| 75.95 | vless | 295.8 | 808.9 | 20.93 | 0.0 | 10.0 | 10.74 | 19.28 | Au1rxx-base64 | 15.204.97.198 |
| 75.88 | shadowsocks | 279.4 | 603.5 | 21.31 | 0.0 | 10.0 | 13.58 | 16.52 | Surfboard-tg-mixed | 154.12.242.150 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Au1rxx-base64 | 0.978 | 0.911 | 403 | 1729 | prefer |
| mheidari-all | 0.783 | 0.71 | 62 | 14516 | prefer |
| Surfboard-tg-mixed | 0.771 | 0.694 | 134 | 6307 | prefer |
| DeltaKronecker-all | 0.663 | 0.588 | 34 | 5415 | observe |
| nscl5-all | 0.298 | 1.0 | 1 | 1082 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6871 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6995 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5215 | observe |
| barry-far-vless | 0.255 | None | 0 | 5492 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4085 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 23 |
| geo | TimeoutError | - | 17 |
| geo | ClientOSError | - | 15 |
| 204 | ProxyError | - | 11 |
| speed | ClientOSError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
