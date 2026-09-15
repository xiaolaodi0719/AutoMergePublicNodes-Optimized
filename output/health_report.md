# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-15 04:36:29 |
| 运行耗时 | 1174.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 90171 |
| 去重后节点 | 25748 |
| TCP 可达 | 3000 |
| 真实可用 | 502 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25748 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 42.1 |
| probe | 452.1 |
| real_test | 590.4 |
| generate | 83.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55824 |
| vmess | 13249 |
| shadowsocks | 10082 |
| trojan | 8399 |
| hysteria2 | 1762 |
| http | 646 |
| shadowsocksr | 124 |
| socks | 53 |
| hysteria | 14 |
| tuic | 10 |
| anytls | 8 |

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
| 84.57 | vless | 223.5 | 561.6 | 22.61 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 45.149.172.80 |
| 84.34 | hysteria2 | 208.3 | 481.6 | 22.96 | 0.0 | 9.98 | 13.12 | 19.56 | Au1rxx-base64 | 107.175.219.48 |
| 82.48 | vless | 227.2 | 576.6 | 22.52 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 45.149.172.74 |
| 81.77 | vless | 257.4 | 685.1 | 21.82 | 0.0 | 9.99 | 12.4 | 19.56 | Au1rxx-base64 | 192.3.247.109 |
| 81.08 | shadowsocks | 203.9 | 536.1 | 23.06 | 0.0 | 10.0 | 13.94 | 18.08 | mheidari-all | 173.244.56.9 |
| 80.98 | vless | 247.8 | 277.8 | 22.04 | 4.58 | 9.82 | 12.4 | 18.26 | Surfboard-tg-mixed | 31.76.91.72 |
| 80.78 | shadowsocks | 203.0 | 472.1 | 23.08 | 0.0 | 10.0 | 13.94 | 18.26 | Surfboard-tg-mixed | 108.181.0.177 |
| 80.6 | shadowsocks | 202.8 | 493.7 | 23.08 | 0.0 | 10.0 | 13.94 | 18.08 | mheidari-all | 108.181.118.10 |
| 80.33 | shadowsocks | 254.9 | 627.9 | 21.88 | 0.0 | 10.0 | 13.94 | 19.56 | Au1rxx-base64 | 156.146.38.168 |
| 80.12 | vless | 275.3 | 552.4 | 21.41 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 144.172.104.26 |
| 80.09 | vless | 223.5 | 522.4 | 22.61 | 0.0 | 10.0 | 12.4 | 18.08 | mheidari-all | 47.251.108.158 |
| 80.09 | shadowsocks | 246.5 | 659.9 | 22.07 | 0.0 | 10.0 | 13.94 | 18.08 | mheidari-all | 173.244.56.6 |
| 79.96 | vless | 228.0 | 483.2 | 22.5 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 162.159.38.127 |
| 79.84 | shadowsocks | 257.5 | 612.8 | 21.82 | 0.0 | 10.0 | 13.94 | 18.08 | mheidari-all | 156.146.38.169 |
| 79.78 | shadowsocks | 259.9 | 626.6 | 21.76 | 0.0 | 10.0 | 13.94 | 18.08 | mheidari-all | 156.146.38.170 |
| 79.64 | vless | 362.8 | 886.3 | 19.38 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 15.204.97.216 |
| 79.35 | shadowsocks | 257.3 | 623.3 | 21.82 | 0.0 | 10.0 | 13.94 | 18.26 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.99 | vless | 270.0 | 649.8 | 21.53 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 104.18.46.234 |
| 78.98 | vless | 338.7 | 760.1 | 19.94 | 0.0 | 10.0 | 12.4 | 19.56 | Au1rxx-base64 | 79.141.172.154 |
| 78.43 | hysteria2 | 204.4 | 529.6 | 23.05 | 0.0 | 10.0 | 13.12 | 18.26 | Surfboard-tg-mixed | 45.149.172.80 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | 0.805 | 287 | 1584 | prefer |
| Surfboard-tg-mixed | 0.758 | 0.68 | 172 | 7572 | prefer |
| ermaozi | 0.628 | 0.618 | 34 | 425 | observe |
| ermaozi-get_subscribe | 0.368 | 0.556 | 9 | 447 | observe |
| mheidari-all | 0.294 | 0.213 | 592 | 21540 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 120 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4914 | observe |
| Epodonios-all | 0.255 | None | 0 | 8044 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8754 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6105 | observe |
| barry-far-vless | 0.255 | None | 0 | 6333 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4099 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1584 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 199 |
| speed | TimeoutError | - | 92 |
| geo | ClientOSError | - | 88 |
| cn-block | ClientOSError | - | 76 |
| speed | ClientOSError | - | 56 |
| 204 | ProxyError | - | 40 |
| cn-block | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42000: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
