# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-20 01:38:23 |
| 运行耗时 | 374.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 91151 |
| 去重后节点 | 23539 |
| TCP 可达 | 3000 |
| 真实可用 | 1307 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23539 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 0.7 |
| tcp | 37.5 |
| probe | 73.3 |
| real_test | 229.0 |
| generate | 27.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51054 |
| trojan | 17477 |
| shadowsocks | 10760 |
| vmess | 9626 |
| hysteria2 | 1682 |
| shadowsocksr | 198 |
| http | 165 |
| socks | 131 |
| anytls | 33 |
| hysteria | 15 |
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
| 82.83 | vless | 256.4 | 629.1 | 21.84 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 82.76 | vless | 259.7 | 686.3 | 21.77 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 82.69 | shadowsocks | 221.6 | 611.8 | 22.65 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 82.34 | shadowsocks | 225.4 | 620.3 | 22.56 | 0.0 | 10.0 | 14.04 | 19.74 | Surfboard-tg-mixed | 37.19.198.243 |
| 82.29 | vless | 279.9 | 742.9 | 21.3 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 82.17 | vless | 284.9 | 755.0 | 21.18 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 81.9 | vless | 296.7 | 729.8 | 20.91 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 81.68 | vless | 306.2 | 831.7 | 20.69 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 81.67 | vless | 306.6 | 760.0 | 20.68 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.61 | vless | 309.1 | 703.8 | 20.62 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.90 |
| 81.56 | vless | 311.5 | 569.6 | 20.57 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 81.49 | vless | 314.3 | 849.9 | 20.5 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.74 |
| 80.84 | shadowsocks | 301.4 | 811.1 | 20.8 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 80.61 | vless | 352.6 | 842.7 | 19.62 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 80.37 | vless | 362.7 | 804.5 | 19.38 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 80.18 | vless | 308.6 | 696.9 | 20.63 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 80.11 | vless | 374.2 | 905.7 | 19.12 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 80.07 | shadowsocks | 237.5 | 611.3 | 22.28 | 0.0 | 10.0 | 14.04 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 80.03 | vless | 377.3 | 966.6 | 19.04 | 0.0 | 10.0 | 10.99 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 79.77 | shadowsocks | 246.4 | 681.5 | 22.08 | 0.0 | 10.0 | 14.04 | 18.18 | mheidari-all | 37.19.198.160 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.977 | 731 | 1789 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.848 | 0.77 | 291 | 6430 | prefer |
| mheidari-all | 0.839 | 0.76 | 334 | 20672 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 5974 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7184 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7353 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5059 | observe |
| barry-far-vless | 0.255 | None | 0 | 5381 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4086 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1789 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 59 |
| speed | TimeoutError | - | 34 |
| geo | ClientOSError | - | 33 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 7 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31350: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
