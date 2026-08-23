# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 06:53:58 |
| 运行耗时 | 293.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 98 |
| 原始节点 | 77609 |
| 去重后节点 | 21147 |
| TCP 可达 | 3000 |
| 真实可用 | 804 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21147 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.5 |
| tcp | 33.7 |
| probe | 57.2 |
| real_test | 158.1 |
| generate | 36.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47390 |
| shadowsocks | 10138 |
| vmess | 10012 |
| trojan | 8578 |
| hysteria2 | 1091 |
| http | 166 |
| shadowsocksr | 125 |
| socks | 100 |
| hysteria | 7 |
| tuic | 2 |

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
| 81.63 | shadowsocks | 295.0 | 579.2 | 20.95 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 142.4.216.225 |
| 81.61 | vless | 237.6 | 648.5 | 22.28 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 81.27 | vless | 252.0 | 648.0 | 21.94 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 81.18 | shadowsocks | 292.8 | 808.0 | 21.0 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 38.180.135.156 |
| 80.81 | vless | 271.9 | 672.6 | 21.48 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.89 |
| 80.8 | shadowsocks | 234.0 | 642.4 | 22.36 | 0.0 | 10.0 | 14.68 | 17.76 | Surfboard-tg-mixed | 37.19.198.243 |
| 80.73 | vless | 275.5 | 667.1 | 21.4 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 154.40.137.160 |
| 80.72 | vless | 275.9 | 737.8 | 21.39 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.212 |
| 80.49 | vless | 286.0 | 712.7 | 21.16 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.90 |
| 80.21 | shadowsocks | 259.6 | 727.7 | 21.77 | 0.0 | 10.0 | 14.68 | 17.76 | Surfboard-tg-mixed | 37.19.198.160 |
| 79.92 | vless | 310.4 | 715.9 | 20.59 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 79.91 | shadowsocks | 239.7 | 664.9 | 22.23 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.79 | vless | 316.0 | 731.7 | 20.46 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.74 |
| 79.61 | vless | 323.8 | 893.2 | 20.28 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 79.127.243.217 |
| 79.39 | shadowsocks | 283.8 | 654.7 | 21.21 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 79.32 | shadowsocks | 246.4 | 634.6 | 22.07 | 0.0 | 9.57 | 14.68 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 79.07 | vless | 347.1 | 941.7 | 19.74 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 169.40.42.182 |
| 78.92 | shadowsocks | 290.7 | 659.1 | 21.05 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 78.88 | shadowsocks | 286.8 | 651.4 | 21.14 | 0.0 | 10.0 | 14.68 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.76 | vless | 296.0 | 673.5 | 20.93 | 0.0 | 10.0 | 9.33 | 20.0 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Au1rxx-base64 | 0.991 | 0.92 | 489 | 1821 | prefer |
| Surfboard-tg-mixed | 0.891 | 0.815 | 157 | 6303 | prefer |
| DeltaKronecker-all | 0.687 | 0.61 | 82 | 5288 | observe |
| mheidari-all | 0.594 | 0.514 | 107 | 14434 | observe |
| nscl5-all | 0.452 | 0.833 | 6 | 1082 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 131 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4989 | observe |
| Epodonios-all | 0.255 | None | 0 | 6859 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7111 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5154 | observe |
| barry-far-vless | 0.255 | None | 0 | 5430 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 43 |
| speed | TimeoutError | - | 31 |
| cn-block | TimeoutError | - | 16 |
| speed | ClientOSError | - | 15 |
| geo | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
