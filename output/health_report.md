# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-13 00:45:28 |
| 运行耗时 | 1256.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 100924 |
| 去重后节点 | 27887 |
| TCP 可达 | 3000 |
| 真实可用 | 483 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27887 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 47.6 |
| probe | 413.2 |
| real_test | 693.8 |
| generate | 92.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59339 |
| vmess | 15946 |
| shadowsocks | 12150 |
| trojan | 11093 |
| hysteria2 | 1450 |
| http | 655 |
| shadowsocksr | 176 |
| socks | 66 |
| anytls | 26 |
| hysteria | 17 |
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
| 83.95 | vless | 218.7 | 543.2 | 22.71 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 154.12.38.202 |
| 83.77 | vless | 226.9 | 577.0 | 22.53 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 154.29.145.196 |
| 83.65 | hysteria2 | 277.0 | 677.3 | 21.37 | 0.0 | 10.0 | 13.64 | 19.64 | Au1rxx-base64 | 66.94.121.46 |
| 83.41 | vless | 242.3 | 595.5 | 22.17 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 154.12.38.159 |
| 80.81 | shadowsocks | 238.2 | 553.3 | 22.26 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 173.244.56.6 |
| 80.57 | hysteria2 | 319.9 | 735.1 | 20.37 | 0.0 | 10.0 | 13.64 | 19.64 | Au1rxx-base64 | 129.213.91.185 |
| 80.45 | shadowsocks | 237.1 | 540.3 | 22.29 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 173.244.56.9 |
| 80.33 | shadowsocks | 259.0 | 621.5 | 21.78 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 156.146.38.168 |
| 79.7 | vless | 291.8 | 691.8 | 21.02 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 147.45.60.160 |
| 79.11 | shadowsocks | 264.2 | 629.7 | 21.66 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 156.146.38.167 |
| 78.85 | vless | 335.0 | 727.0 | 20.02 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 23.95.222.127 |
| 78.76 | vless | 255.2 | 479.3 | 21.87 | 0.0 | 10.0 | 11.6 | 15.76 | mheidari-all | 47.251.108.158 |
| 78.76 | vless | 359.7 | 727.0 | 19.45 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 95.111.212.241 |
| 78.46 | shadowsocks | 300.3 | 743.6 | 20.83 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 156.146.38.169 |
| 78.43 | shadowsocks | 259.4 | 632.1 | 21.77 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 156.146.38.170 |
| 77.36 | vless | 503.6 | 1296.7 | 16.12 | 0.0 | 10.0 | 11.6 | 19.64 | Au1rxx-base64 | 195.123.240.65 |
| 76.52 | shadowsocks | 282.6 | 291.0 | 21.24 | 4.09 | 9.91 | 12.91 | 19.64 | Au1rxx-base64 | 149.22.87.204 |
| 76.2 | shadowsocks | 286.7 | 625.5 | 21.14 | 0.0 | 10.0 | 12.91 | 19.64 | Au1rxx-base64 | 149.22.95.183 |
| 75.98 | vless | 289.5 | 602.8 | 21.08 | 0.0 | 6.84 | 11.6 | 19.64 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 75.66 | vless | 335.2 | 336.4 | 20.02 | 2.39 | 9.91 | 11.6 | 19.64 | Au1rxx-base64 | 142.91.108.25 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.935 | 336 | 1847 | prefer |
| Surfboard-tg-mixed | 0.48 | 1.0 | 4 | 7208 | observe |
| ermaozi | 0.479 | 0.448 | 29 | 675 | observe |
| mheidari-all | 0.355 | 0.274 | 536 | 23897 | observe |
| ermaozi-get_subscribe | 0.29 | 0.667 | 3 | 532 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| Epodonios-all | 0.255 | None | 0 | 7736 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10536 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5678 | observe |
| barry-far-vless | 0.255 | None | 0 | 6023 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1847 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 213 |
| speed | TimeoutError | - | 107 |
| geo | ClientOSError | - | 38 |
| speed | ClientOSError | - | 32 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
