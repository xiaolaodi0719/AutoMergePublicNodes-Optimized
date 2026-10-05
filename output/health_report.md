# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-05 05:10:56 |
| 运行耗时 | 820.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 98824 |
| 去重后节点 | 27507 |
| TCP 可达 | 3000 |
| 真实可用 | 535 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27507 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 47.2 |
| probe | 287.5 |
| real_test | 445.0 |
| generate | 34.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59303 |
| vmess | 15515 |
| shadowsocks | 11391 |
| trojan | 10323 |
| hysteria2 | 1365 |
| http | 623 |
| shadowsocksr | 170 |
| socks | 68 |
| anytls | 30 |
| tuic | 19 |
| hysteria | 17 |

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
| 85.74 | vless | 211.3 | 536.6 | 22.89 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 15.204.97.216 |
| 84.88 | hysteria2 | 228.3 | 270.0 | 22.49 | 4.87 | 9.74 | 14.38 | 19.96 | Au1rxx-base64 | open.w2m.ink |
| 83.86 | vless | 235.4 | 518.8 | 22.33 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 47.251.108.158 |
| 82.33 | vless | 263.0 | 550.3 | 21.69 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 23.95.222.127 |
| 81.84 | vless | 290.5 | 601.6 | 21.05 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 137.175.82.40 |
| 81.68 | vless | 259.9 | 565.2 | 21.76 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 107.173.237.146 |
| 81.07 | trojan | 224.5 | 550.8 | 22.58 | 0.0 | 9.24 | 12.79 | 19.96 | Au1rxx-base64 | happy-gibbon.rooster465.autos |
| 79.38 | vless | 334.9 | 295.0 | 20.03 | 3.94 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 46.250.250.149 |
| 79.37 | vless | 486.2 | 1324.0 | 16.52 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 51.81.203.63 |
| 79.27 | hysteria2 | 234.8 | 291.6 | 22.34 | 4.06 | 10.0 | 14.38 | 19.96 | Au1rxx-base64 | 132.226.14.77 |
| 79.2 | trojan | 234.5 | 556.4 | 22.35 | 0.0 | 8.6 | 12.79 | 19.96 | Au1rxx-base64 | guided-ferret.rooster465.autos |
| 79.07 | trojan | 300.7 | 768.2 | 20.82 | 0.0 | 10.0 | 12.79 | 19.96 | Au1rxx-base64 | 44.255.123.205 |
| 78.81 | shadowsocks | 207.7 | 557.8 | 22.97 | 0.0 | 10.0 | 12.8 | 17.04 | mheidari-all | 149.22.95.183 |
| 78.19 | http | 270.7 | 585.5 | 21.51 | 0.0 | 10.0 | 13.89 | 19.04 | ermaozi | 138.199.35.203 |
| 78.11 | http | 274.3 | 587.9 | 21.43 | 0.0 | 10.0 | 13.89 | 19.04 | ermaozi | 138.199.35.198 |
| 77.97 | vless | 330.8 | 848.5 | 20.12 | 0.0 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 34.3.101.206 |
| 77.59 | vless | 272.0 | 390.4 | 21.48 | 0.36 | 10.0 | 12.89 | 19.96 | Au1rxx-base64 | 104.21.70.21 |
| 77.54 | hysteria2 | 334.5 | 756.2 | 20.03 | 0.0 | 10.0 | 14.38 | 19.96 | Au1rxx-base64 | 129.213.91.185 |
| 77.36 | trojan | 314.3 | 788.8 | 20.5 | 0.0 | 9.61 | 12.79 | 19.96 | Au1rxx-base64 | ultimate-jaguar.rooster465.autos |
| 76.69 | trojan | 273.6 | 691.9 | 21.44 | 0.0 | 10.0 | 12.79 | 19.96 | Au1rxx-base64 | 34.220.15.24 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | 0.893 | 364 | 1883 | prefer |
| ermaozi | 0.622 | 0.597 | 62 | 694 | observe |
| Surfboard-tg-mixed | 0.471 | 0.381 | 21 | 7178 | observe |
| mheidari-all | 0.459 | 0.379 | 425 | 23195 | observe |
| 10ium-ScrapeCategorize-Vless | 0.287 | 0.5 | 2 | 5173 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 68 | observe |
| Epodonios-all | 0.255 | None | 0 | 7673 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9258 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5736 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4365 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.25 | None | 0 | 1883 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 146 |
| speed | TimeoutError | - | 77 |
| 204 | ProxyError | - | 43 |
| geo | ClientOSError | - | 40 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 13 |
| speed | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
