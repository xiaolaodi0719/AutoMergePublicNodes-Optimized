# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 05:22:58 |
| 运行耗时 | 1128.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97520 |
| 去重后节点 | 27407 |
| TCP 可达 | 3000 |
| 真实可用 | 496 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27407 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 46.8 |
| probe | 409.4 |
| real_test | 583.7 |
| generate | 81.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56882 |
| vmess | 15827 |
| shadowsocks | 11866 |
| trojan | 10558 |
| hysteria2 | 1539 |
| http | 550 |
| shadowsocksr | 163 |
| socks | 75 |
| anytls | 37 |
| hysteria | 16 |
| tuic | 7 |

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
| 82.42 | vless | 213.7 | 493.1 | 22.83 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 47.251.108.158 |
| 82.38 | vless | 215.4 | 541.5 | 22.79 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 154.9.241.170 |
| 81.53 | vless | 208.9 | 527.8 | 22.94 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 154.29.145.196 |
| 81.43 | vless | 213.2 | 506.6 | 22.84 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 137.175.82.40 |
| 81.39 | trojan | 309.3 | 811.6 | 20.62 | 0.0 | 10.0 | 14.55 | 19.22 | Au1rxx-base64 | 107.149.159.190 |
| 81.03 | vless | 230.6 | 525.3 | 22.44 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 104.17.98.5 |
| 80.88 | vless | 280.4 | 760.4 | 21.29 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 107.173.237.146 |
| 80.8 | shadowsocks | 258.2 | 624.8 | 21.8 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 156.146.38.169 |
| 80.68 | shadowsocks | 263.3 | 644.7 | 21.68 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 156.146.38.170 |
| 80.41 | shadowsocks | 260.6 | 625.5 | 21.75 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 156.146.38.168 |
| 79.66 | shadowsocks | 300.6 | 744.4 | 20.82 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 156.146.38.167 |
| 79.29 | hysteria2 | 260.4 | 230.2 | 21.75 | 6.37 | 7.34 | 11.67 | 19.22 | Au1rxx-base64 | open.2ml.bid |
| 78.65 | shadowsocks | 250.6 | 507.6 | 21.98 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 173.244.56.6 |
| 78.64 | shadowsocks | 307.1 | 749.4 | 20.67 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 5.78.51.123 |
| 78.41 | vless | 302.5 | 705.2 | 20.78 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 23.95.222.127 |
| 78.25 | shadowsocks | 281.9 | 582.1 | 21.25 | 0.0 | 10.0 | 13.78 | 19.22 | Au1rxx-base64 | 173.244.56.9 |
| 77.91 | vless | 276.4 | 612.8 | 21.38 | 0.0 | 10.0 | 10.37 | 19.22 | Au1rxx-base64 | 15.204.97.216 |
| 77.67 | hysteria2 | 320.7 | 746.9 | 20.35 | 0.0 | 10.0 | 11.67 | 19.22 | Au1rxx-base64 | 129.213.91.185 |
| 77.04 | shadowsocks | 329.0 | 574.1 | 20.16 | 0.0 | 10.0 | 13.78 | 17.6 | mheidari-all | 103.11.76.248 |
| 76.96 | hysteria2 | 270.5 | 360.9 | 21.52 | 1.47 | 9.9 | 11.67 | 19.22 | Au1rxx-base64 | 45.32.10.7 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.975 | 0.905 | 379 | 1799 | prefer |
| ermaozi-get_subscribe | 0.58 | 0.56 | 25 | 610 | observe |
| Surfboard-tg-mixed | 0.529 | 0.857 | 7 | 7087 | observe |
| zhangkai | 0.483 | 1.0 | 6 | 144 | observe |
| mheidari-all | 0.397 | 0.316 | 392 | 23694 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4347 | observe |
| DeltaKronecker-all | 0.32 | 0.5 | 4 | 5009 | observe |
| Epodonios-all | 0.255 | None | 0 | 7576 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9365 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5545 | observe |
| barry-far-vless | 0.255 | None | 0 | 5790 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1799 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 141 |
| speed | TimeoutError | - | 60 |
| geo | ClientOSError | - | 37 |
| speed | ClientOSError | - | 31 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 16 |
| 204 | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
