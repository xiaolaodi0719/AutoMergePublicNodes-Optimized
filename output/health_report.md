# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 05:29:29 |
| 运行耗时 | 940.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97887 |
| 去重后节点 | 27737 |
| TCP 可达 | 3000 |
| 真实可用 | 520 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27737 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.5 |
| tcp | 47.9 |
| probe | 333.4 |
| real_test | 480.7 |
| generate | 71.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57027 |
| vmess | 15714 |
| shadowsocks | 11919 |
| trojan | 10811 |
| hysteria2 | 1565 |
| http | 555 |
| shadowsocksr | 169 |
| socks | 70 |
| anytls | 28 |
| hysteria | 17 |
| tuic | 12 |

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
| 82.09 | shadowsocks | 239.6 | 590.4 | 22.23 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 156.146.38.170 |
| 81.92 | shadowsocks | 246.8 | 641.4 | 22.06 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 156.146.38.168 |
| 81.9 | shadowsocks | 248.0 | 638.9 | 22.04 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 156.146.38.169 |
| 81.78 | shadowsocks | 253.2 | 634.9 | 21.92 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 156.146.38.167 |
| 80.65 | shadowsocks | 280.3 | 744.7 | 21.29 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 66.23.204.214 |
| 80.03 | vless | 331.1 | 751.5 | 20.11 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 66.70.179.198 |
| 79.9 | shadowsocks | 306.1 | 757.7 | 20.69 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 37.19.198.243 |
| 79.74 | vless | 379.5 | 946.1 | 18.99 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 185.95.231.156 |
| 79.43 | vless | 290.5 | 595.6 | 21.05 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 47.251.108.158 |
| 79.41 | shadowsocks | 303.7 | 752.5 | 20.75 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 37.19.198.244 |
| 79.32 | shadowsocks | 302.2 | 741.6 | 20.78 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 37.19.198.236 |
| 78.97 | shadowsocks | 295.3 | 684.4 | 20.94 | 0.0 | 10.0 | 14.06 | 19.8 | Au1rxx-base64 | 140.82.63.79 |
| 78.87 | vless | 286.3 | 677.6 | 21.15 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 69.48.201.136 |
| 78.5 | vless | 395.8 | 896.4 | 18.61 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 169.40.42.232 |
| 78.42 | vless | 387.0 | 953.7 | 18.82 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 137.184.218.169 |
| 78.33 | vless | 306.0 | 701.1 | 20.69 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 198.251.78.29 |
| 78.28 | hysteria2 | 323.7 | 321.2 | 20.29 | 2.96 | 8.92 | 14.35 | 19.8 | Au1rxx-base64 | open.2ml.bid |
| 78.28 | vless | 348.7 | 753.5 | 19.71 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 107.173.237.146 |
| 78.01 | vless | 305.0 | 725.4 | 20.72 | 0.0 | 10.0 | 12.42 | 19.8 | Au1rxx-base64 | 172.245.253.16 |
| 77.93 | hysteria2 | 323.5 | 349.1 | 20.29 | 1.91 | 9.54 | 14.35 | 19.8 | Au1rxx-base64 | 158.101.148.79 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.908 | 357 | 1786 | prefer |
| Surfboard-tg-mixed | 0.712 | 0.633 | 180 | 7155 | prefer |
| ermaozi-get_subscribe | 0.681 | 0.667 | 27 | 653 | observe |
| zhangkai | 0.483 | 1.0 | 6 | 144 | observe |
| mheidari-all | 0.373 | 0.291 | 182 | 23395 | observe |
| DeltaKronecker-all | 0.337 | 0.429 | 7 | 5154 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4984 | observe |
| Epodonios-all | 0.255 | None | 0 | 7634 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9590 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5643 | observe |
| barry-far-vless | 0.255 | None | 0 | 5793 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4346 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 104 |
| speed | TimeoutError | - | 37 |
| geo | ClientOSError | - | 26 |
| cn-block | TimeoutError | - | 20 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyError | - | 12 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48085: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
