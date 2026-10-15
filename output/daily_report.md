# AutoNodes 每日报告

生成时间：2026-10-15 16:54:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 100051 |
| 去重后节点数 | 27884 |
| TCP 可达数 | 3000 |
| 真测通过数 | 377 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27884 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 88.0 |
| geo | 1.5 |
| probe | 365.4 |
| real_test | 328.8 |
| tcp | 48.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 37 | 6 | 31 | 16.2% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 134 | 105 | 29 | 78.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 70 | 43 | 27 | 61.4% |
| vless | 357 | 206 | 151 | 57.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 73 |
| 204:ProxyError | 33 |
| geo:ClientOSError | 32 |
| cn-block:TimeoutError | 29 |
| speed:ClientOSError | 15 |
| geo:TimeoutError | 14 |
| 204:ProxyConnectionError | 13 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6895 |
| ConnectionRefusedError | 1047 |
| gaierror | 248 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.793 | prefer | 441 | 0.723 | 1767 |
| Surfboard-tg-mixed | 0.462 | observe | 53 | 0.377 | 7281 |
| DeltaKronecker-all | 0.413 | observe | 79 | 0.329 | 5147 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 24080 |
| ermaozi-get_subscribe | 0.332 | observe | 2 | 1.0 | 519 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7794 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10074 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi | 0.206 | 37 | 0.162 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.162 | 6 | 31 | 37 |
| DeltaKronecker-all | 0.329 | 26 | 53 | 79 |
| Surfboard-tg-mixed | 0.377 | 20 | 33 | 53 |
| Au1rxx-base64 | 0.723 | 319 | 122 | 441 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24080 | yes | 6.17 | 0 |
| SoliSpirit-all | 10074 | yes | 5.92 | 0 |
| Epodonios-all | 7794 | yes | 5.28 | 0 |
| Surfboard-tg-mixed | 7281 | yes | 1.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.39 | 0 |
| barry-far-vless | 5961 | yes | 4.73 | 0 |
| Surfboard-tg-vless | 5707 | yes | 6.66 | 0 |
| DeltaKronecker-all | 5147 | yes | 7.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 3.28 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 123 |
| geo | 47 |
| cn-block | 43 |
| speed | 28 |
