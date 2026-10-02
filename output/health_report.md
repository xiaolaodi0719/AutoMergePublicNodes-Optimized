# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-02 12:21:19 |
| 运行耗时 | 530.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97754 |
| 去重后节点 | 26970 |
| TCP 可达 | 3000 |
| 真实可用 | 380 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26970 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| geo | 1.3 |
| tcp | 46.9 |
| probe | 215.4 |
| real_test | 181.3 |
| generate | 78.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59633 |
| vmess | 15413 |
| shadowsocks | 11463 |
| trojan | 8909 |
| hysteria2 | 1524 |
| http | 521 |
| shadowsocksr | 169 |
| socks | 60 |
| anytls | 35 |
| hysteria | 17 |
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
| 83.24 | hysteria2 | 244.2 | 543.2 | 22.13 | 0.0 | 10.0 | 13.57 | 19.42 | Au1rxx-base64 | 192.255.128.123 |
| 82.19 | hysteria2 | 308.9 | 707.3 | 20.63 | 0.0 | 10.0 | 13.57 | 19.42 | Au1rxx-base64 | 159.223.157.129 |
| 76.97 | shadowsocks | 386.8 | 992.4 | 18.82 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 15.204.246.132 |
| 75.67 | shadowsocks | 337.5 | 767.4 | 19.97 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 108.181.57.93 |
| 74.61 | shadowsocks | 280.9 | 602.6 | 21.27 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 74.201.177.54 |
| 74.3 | shadowsocks | 335.4 | 655.7 | 20.01 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 108.181.0.177 |
| 74.19 | shadowsocks | 334.3 | 660.5 | 20.04 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 108.181.118.10 |
| 74.14 | shadowsocks | 295.7 | 649.2 | 20.93 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 173.234.25.90 |
| 73.63 | vless | 322.9 | 732.9 | 20.3 | 0.0 | 10.0 | 6.38 | 19.42 | Au1rxx-base64 | 66.70.179.198 |
| 73.5 | hysteria2 | 489.6 | 920.8 | 16.44 | 0.0 | 10.0 | 13.57 | 19.42 | Au1rxx-base64 | 66.94.121.46 |
| 73.35 | shadowsocks | 340.5 | 332.7 | 19.89 | 2.52 | 9.58 | 14.01 | 19.42 | Au1rxx-base64 | 149.22.87.240 |
| 73.32 | shadowsocks | 310.9 | 729.9 | 20.58 | 0.0 | 10.0 | 14.01 | 16.06 | Surfboard-tg-mixed | 15.204.247.206 |
| 73.24 | shadowsocks | 258.7 | 558.6 | 21.79 | 0.0 | 10.0 | 14.01 | 19.42 | Au1rxx-base64 | 216.105.168.157 |
| 73.22 | shadowsocks | 293.2 | 644.1 | 20.99 | 0.0 | 10.0 | 14.01 | 16.06 | Surfboard-tg-mixed | 5.78.51.123 |
| 73.14 | shadowsocks | 246.8 | 623.2 | 22.07 | 0.0 | 10.0 | 14.01 | 16.06 | Surfboard-tg-mixed | 156.146.38.168 |
| 73.07 | vless | 292.5 | 614.8 | 21.01 | 0.0 | 10.0 | 6.38 | 19.42 | Au1rxx-base64 | 172.235.43.210 |
| 73.02 | shadowsocks | 251.6 | 620.2 | 21.95 | 0.0 | 10.0 | 14.01 | 16.06 | Surfboard-tg-mixed | 156.146.38.169 |
| 72.9 | hysteria2 | 403.2 | 650.8 | 18.44 | 0.0 | 9.17 | 13.57 | 19.42 | Au1rxx-base64 | open.w2m.ink |
| 72.81 | vless | 249.1 | 610.9 | 22.01 | 0.0 | 10.0 | 6.38 | 19.42 | Au1rxx-base64 | us51.mech-pro.online |
| 72.69 | vless | 245.5 | 602.8 | 22.09 | 0.0 | 10.0 | 6.38 | 19.42 | Au1rxx-base64 | 140.150.227.51 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.904 | 0.839 | 286 | 1673 | prefer |
| mheidari-all | 0.863 | 0.795 | 44 | 23059 | prefer |
| Surfboard-tg-mixed | 0.821 | 0.746 | 114 | 7176 | prefer |
| ermaozi | 0.728 | 0.72 | 25 | 618 | prefer |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5276 | observe |
| Epodonios-all | 0.255 | None | 0 | 7676 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Pawdroid | 0.255 | 1.0 | 1 | 12 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9234 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5828 | observe |
| barry-far-vless | 0.255 | None | 0 | 6070 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4310 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 26 |
| cn-block | TimeoutError | - | 23 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | ProxyConnectionError | - | 5 |
| geo | TimeoutError | - | 5 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
