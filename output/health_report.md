# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 11:42:31 |
| 运行耗时 | 667.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98051 |
| 去重后节点 | 27189 |
| TCP 可达 | 3000 |
| 真实可用 | 316 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27189 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.5 |
| tcp | 47.2 |
| probe | 271.4 |
| real_test | 257.9 |
| generate | 81.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57900 |
| vmess | 16092 |
| shadowsocks | 11796 |
| trojan | 10175 |
| hysteria2 | 1303 |
| http | 483 |
| shadowsocksr | 167 |
| socks | 86 |
| anytls | 25 |
| hysteria | 18 |
| tuic | 6 |

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
| 81.05 | shadowsocks | 234.7 | 556.6 | 22.35 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 173.244.56.6 |
| 80.69 | shadowsocks | 250.0 | 601.4 | 21.99 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 149.22.95.183 |
| 80.57 | vless | 193.7 | 493.9 | 23.29 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 45.32.69.110 |
| 80.45 | vless | 198.8 | 501.1 | 23.17 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 144.202.126.147 |
| 80.33 | vless | 204.1 | 518.9 | 23.05 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 154.29.145.196 |
| 79.06 | vless | 259.0 | 581.5 | 21.78 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 78.87 | vless | 254.9 | 590.5 | 21.88 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 44.248.233.99 |
| 78.53 | vless | 282.1 | 726.7 | 21.25 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 154.12.38.159 |
| 77.81 | vless | 313.2 | 741.7 | 20.53 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 95.111.212.241 |
| 77.41 | vless | 330.5 | 848.7 | 20.13 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 51.81.203.63 |
| 77.03 | shadowsocks | 295.4 | 668.5 | 20.94 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 156.146.38.168 |
| 77.01 | shadowsocks | 294.6 | 667.0 | 20.96 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 156.146.38.170 |
| 76.88 | shadowsocks | 293.3 | 658.1 | 20.99 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 156.146.38.169 |
| 75.79 | hysteria2 | 340.4 | 749.7 | 19.9 | 0.0 | 10.0 | 11.67 | 18.92 | Au1rxx-base64 | 129.213.91.185 |
| 74.51 | hysteria2 | 422.3 | 698.6 | 18.0 | 0.0 | 9.45 | 11.67 | 18.92 | Au1rxx-base64 | 66.94.121.46 |
| 74.39 | trojan | 330.0 | 341.0 | 20.14 | 2.21 | 9.94 | 13.62 | 18.92 | Au1rxx-base64 | 45.32.52.173 |
| 73.88 | vless | 193.5 | 523.3 | 23.3 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 23.95.222.127 |
| 72.7 | vless | 313.5 | 662.0 | 20.52 | 0.0 | 10.0 | 8.36 | 18.92 | Au1rxx-base64 | 154.40.55.185 |
| 72.48 | trojan | 326.9 | 326.9 | 20.21 | 2.74 | 9.94 | 13.62 | 18.92 | Au1rxx-base64 | 108.61.186.37 |
| 72.02 | shadowsocks | 388.3 | 810.8 | 18.79 | 0.0 | 10.0 | 13.78 | 18.92 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.883 | 0.814 | 258 | 1786 | prefer |
| mheidari-all | 0.819 | 0.75 | 44 | 23983 | prefer |
| Surfboard-tg-mixed | 0.724 | 0.648 | 88 | 7056 | prefer |
| ermaozi-get_subscribe | 0.366 | 0.333 | 36 | 598 | observe |
| zhangkai | 0.278 | 0.5 | 6 | 144 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7542 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9834 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5579 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1778 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 27 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 22 |
| geo | ClientOSError | - | 13 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyConnectionError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
