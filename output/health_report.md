# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-09 07:07:35 |
| 运行耗时 | 244.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 82917 |
| 去重后节点 | 23035 |
| TCP 可达 | 3000 |
| 真实可用 | 540 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23035 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 34.6 |
| probe | 57.2 |
| real_test | 118.8 |
| generate | 27.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48660 |
| vmess | 13113 |
| trojan | 9931 |
| shadowsocks | 9632 |
| hysteria2 | 1383 |
| shadowsocksr | 70 |
| socks | 61 |
| http | 43 |
| hysteria | 13 |
| tuic | 11 |

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
| 83.85 | http | 191.2 | 485.9 | 23.35 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.217 |
| 83.75 | http | 195.8 | 506.1 | 23.25 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.207 |
| 83.63 | http | 200.7 | 517.5 | 23.13 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.214 |
| 82.87 | http | 233.5 | 611.8 | 22.37 | 0.0 | 10.0 | 14.38 | 19.12 | zhangkai | 138.199.35.199 |
| 82.36 | shadowsocks | 202.5 | 487.8 | 23.09 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 81.78 | shadowsocks | 249.3 | 651.5 | 22.01 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 81.65 | shadowsocks | 254.6 | 621.7 | 21.88 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.64 | shadowsocks | 233.7 | 565.3 | 22.37 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 81.58 | vless | 191.6 | 485.5 | 23.34 | 0.0 | 10.0 | 8.24 | 20.0 | Au1rxx-base64 | 186.241.106.97 |
| 81.57 | shadowsocks | 258.2 | 631.0 | 21.8 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.52 | vless | 194.1 | 481.4 | 23.28 | 0.0 | 10.0 | 8.24 | 20.0 | Au1rxx-base64 | 179.255.148.66 |
| 81.48 | vless | 195.9 | 507.4 | 23.24 | 0.0 | 10.0 | 8.24 | 20.0 | Au1rxx-base64 | 167.17.68.205 |
| 81.48 | shadowsocks | 254.4 | 612.9 | 21.89 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.35 | shadowsocks | 263.5 | 646.9 | 21.68 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.69 | shadowsocks | 209.8 | 510.1 | 22.92 | 0.0 | 10.0 | 13.77 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 80.28 | vless | 247.7 | 654.9 | 22.04 | 0.0 | 10.0 | 8.24 | 20.0 | Au1rxx-base64 | 70.39.178.231 |
| 79.6 | trojan | 272.5 | 559.2 | 21.47 | 0.0 | 10.0 | 14.03 | 20.0 | Au1rxx-base64 | 44.244.3.114 |
| 79.31 | vless | 202.9 | 518.3 | 23.08 | 0.0 | 9.99 | 8.24 | 20.0 | Au1rxx-base64 | t17.qifei.app |
| 79.0 | trojan | 290.9 | 610.0 | 21.04 | 0.0 | 10.0 | 14.03 | 20.0 | Au1rxx-base64 | 35.86.90.51 |
| 78.83 | hysteria2 | 390.7 | 890.8 | 18.73 | 0.0 | 10.0 | 14.5 | 20.0 | Au1rxx-base64 | 138.124.68.188 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.93 | 401 | 1640 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.836 | 0.762 | 84 | 6537 | prefer |
| mheidari-all | 0.616 | 0.537 | 136 | 17626 | observe |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 171 | observe |
| nscl5-all | 0.315 | 1.0 | 1 | 1506 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5505 | observe |
| Epodonios-all | 0.255 | None | 0 | 7052 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7616 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5295 | observe |
| barry-far-vless | 0.255 | None | 0 | 5569 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5130 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1640 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 54 |
| 204 | TimeoutError | - | 21 |
| speed | ClientOSError | - | 18 |
| speed | TimeoutError | - | 15 |
| geo | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
