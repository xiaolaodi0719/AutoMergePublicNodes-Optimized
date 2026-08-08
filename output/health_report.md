# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-08 02:01:09 |
| 运行耗时 | 253.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82250 |
| 去重后节点 | 23592 |
| TCP 可达 | 3000 |
| 真实可用 | 581 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23592 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.0 |
| tcp | 34.9 |
| probe | 52.4 |
| real_test | 123.7 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47723 |
| vmess | 12917 |
| trojan | 10244 |
| shadowsocks | 9893 |
| hysteria2 | 1278 |
| shadowsocksr | 74 |
| socks | 64 |
| http | 35 |
| hysteria | 13 |
| tuic | 8 |
| anytls | 1 |

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
| 84.08 | trojan | 222.4 | 503.8 | 22.63 | 0.0 | 10.0 | 14.69 | 19.26 | Au1rxx-base64 | 44.246.163.102 |
| 84.05 | trojan | 213.4 | 472.2 | 22.84 | 0.0 | 9.76 | 14.69 | 19.26 | Au1rxx-base64 | pet-ghost.rooster465.autos |
| 83.92 | http | 185.8 | 478.6 | 23.48 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.207 |
| 83.92 | http | 185.9 | 484.9 | 23.48 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.199 |
| 83.92 | trojan | 222.6 | 495.8 | 22.62 | 0.0 | 9.85 | 14.69 | 19.26 | Au1rxx-base64 | fleet-bonefish.rooster465.autos |
| 83.76 | http | 192.6 | 495.9 | 23.32 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.214 |
| 83.6 | http | 199.3 | 515.4 | 23.16 | 0.0 | 10.0 | 14.32 | 19.12 | zhangkai | 138.199.35.217 |
| 83.1 | trojan | 230.1 | 527.8 | 22.45 | 0.0 | 9.5 | 14.69 | 19.26 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 82.6 | trojan | 286.4 | 697.1 | 21.15 | 0.0 | 10.0 | 14.69 | 19.26 | Au1rxx-base64 | 44.242.235.129 |
| 81.97 | trojan | 273.0 | 643.0 | 21.46 | 0.0 | 10.0 | 14.69 | 19.26 | Au1rxx-base64 | 35.86.90.51 |
| 80.46 | trojan | 235.7 | 541.8 | 22.32 | 0.0 | 9.66 | 14.69 | 19.26 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 80.23 | vless | 303.0 | 369.7 | 20.76 | 1.14 | 10.0 | 10.07 | 19.26 | Au1rxx-base64 | 104.17.21.111 |
| 80.05 | shadowsocks | 231.7 | 514.8 | 22.41 | 0.0 | 10.0 | 12.38 | 19.26 | Au1rxx-base64 | 173.244.56.9 |
| 79.65 | trojan | 216.2 | 486.2 | 22.77 | 0.0 | 10.0 | 14.69 | 19.26 | Au1rxx-base64 | 44.244.3.114 |
| 79.55 | shadowsocks | 231.9 | 598.5 | 22.41 | 0.0 | 10.0 | 12.38 | 19.26 | Au1rxx-base64 | 108.181.118.10 |
| 79.4 | shadowsocks | 259.9 | 586.3 | 21.76 | 0.0 | 10.0 | 12.38 | 19.26 | Au1rxx-base64 | 149.22.95.183 |
| 79.18 | shadowsocks | 232.2 | 517.7 | 22.4 | 0.0 | 10.0 | 12.38 | 19.26 | Au1rxx-base64 | 173.244.56.6 |
| 78.33 | shadowsocks | 284.4 | 735.7 | 21.19 | 0.0 | 10.0 | 12.38 | 19.26 | Au1rxx-base64 | 108.181.0.177 |
| 77.95 | hysteria2 | 347.2 | 760.4 | 19.74 | 0.0 | 10.0 | 13.75 | 19.26 | Au1rxx-base64 | 138.124.68.188 |
| 77.86 | hysteria2 | 359.0 | 782.8 | 19.47 | 0.0 | 9.95 | 13.75 | 19.26 | Au1rxx-base64 | usa1.spectrumproxy.shop |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 440 | 1365 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| Surfboard-tg-mixed | 0.663 | 0.588 | 34 | 6471 | observe |
| mheidari-all | 0.568 | 0.488 | 211 | 17687 | observe |
| DeltaKronecker-all | 0.311 | 0.224 | 76 | 5326 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7081 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7469 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5179 | observe |
| barry-far-vless | 0.255 | None | 0 | 5509 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5175 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.241 | None | 0 | 1643 | observe |
| Au1rxx-clash | 0.23 | None | 0 | 1365 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 80 |
| speed | TimeoutError | - | 37 |
| geo | ClientOSError | - | 26 |
| speed | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32762: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
