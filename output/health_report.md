# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-24 21:30:15 |
| 运行耗时 | 543.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98134 |
| 去重后节点 | 26548 |
| TCP 可达 | 3000 |
| 真实可用 | 374 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26548 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 43.5 |
| probe | 255.5 |
| real_test | 155.0 |
| generate | 81.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60228 |
| vmess | 14904 |
| shadowsocks | 11269 |
| trojan | 9246 |
| hysteria2 | 1598 |
| http | 592 |
| shadowsocksr | 174 |
| socks | 76 |
| anytls | 22 |
| hysteria | 18 |
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
| 83.52 | vless | 220.3 | 602.8 | 22.68 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 195.211.98.43 |
| 82.44 | vless | 264.0 | 653.6 | 21.67 | 0.0 | 8.49 | 12.34 | 19.94 | Au1rxx-base64 | 198.251.78.29 |
| 82.24 | vless | 273.1 | 712.9 | 21.46 | 0.0 | 8.5 | 12.34 | 19.94 | Au1rxx-base64 | 79.141.172.154 |
| 82.23 | vless | 270.8 | 630.7 | 21.51 | 0.0 | 8.82 | 12.34 | 19.94 | Au1rxx-base64 | 195.123.235.177 |
| 81.65 | vless | 304.2 | 745.2 | 20.74 | 0.0 | 8.63 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.104 |
| 80.9 | vless | 298.5 | 704.8 | 20.87 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.225 |
| 80.36 | hysteria2 | 273.1 | 688.6 | 21.46 | 0.0 | 8.56 | 13.5 | 19.94 | Au1rxx-base64 | 159.223.157.129 |
| 79.8 | vless | 291.9 | 706.3 | 21.02 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.95 |
| 79.29 | vless | 354.8 | 825.3 | 19.57 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.15 |
| 79.05 | vless | 404.5 | 1004.8 | 18.41 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.163 |
| 78.99 | shadowsocks | 261.5 | 708.8 | 21.72 | 0.0 | 8.13 | 13.7 | 19.94 | Au1rxx-base64 | yyz-ca-01.blncvpn4u.cc |
| 78.74 | vless | 319.8 | 722.2 | 20.37 | 0.0 | 8.63 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.182 |
| 78.59 | vless | 351.0 | 765.9 | 19.65 | 0.0 | 8.51 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.16 |
| 78.41 | vless | 341.2 | 799.5 | 19.88 | 0.0 | 8.56 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.133 |
| 78.34 | shadowsocks | 286.8 | 734.1 | 21.14 | 0.0 | 10.0 | 13.7 | 17.5 | Surfboard-tg-mixed | 37.19.198.243 |
| 78.31 | shadowsocks | 254.6 | 636.2 | 21.88 | 0.0 | 10.0 | 13.7 | 17.5 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.04 | vless | 427.1 | 977.6 | 17.89 | 0.0 | 8.6 | 12.34 | 19.94 | Au1rxx-base64 | 185.95.231.233 |
| 77.82 | shadowsocks | 329.0 | 905.0 | 20.16 | 0.0 | 8.52 | 13.7 | 19.94 | Au1rxx-base64 | 185.156.47.97 |
| 77.72 | vless | 367.2 | 884.1 | 19.28 | 0.0 | 8.53 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.89 |
| 77.64 | vless | 322.8 | 793.4 | 20.31 | 0.0 | 8.5 | 12.34 | 19.94 | Au1rxx-base64 | 169.40.42.90 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | 0.933 | 253 | 1626 | prefer |
| mheidari-all | 0.846 | 0.773 | 75 | 22744 | prefer |
| Surfboard-tg-mixed | 0.788 | 0.712 | 104 | 7419 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4405 | observe |
| ermaozi-get_subscribe | 0.267 | 1.0 | 1 | 304 | observe |
| ermaozi | 0.263 | 0.286 | 14 | 298 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5307 | observe |
| Epodonios-all | 0.255 | None | 0 | 7888 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9086 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5963 | observe |
| barry-far-vless | 0.255 | None | 0 | 6215 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1626 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 16 |
| 204 | ProxyError | - | 13 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 8 |
| geo | TimeoutError | - | 7 |
| geo | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41485: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
