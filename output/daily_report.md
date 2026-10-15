# AutoNodes 每日报告

生成时间：2026-10-15 21:21:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99754 |
| 去重后节点数 | 27713 |
| TCP 可达数 | 3000 |
| 真测通过数 | 420 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27713 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 87.0 |
| geo | 1.5 |
| probe | 302.6 |
| real_test | 301.8 |
| tcp | 47.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 60 | 21 | 39 | 35.0% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 144 | 131 | 13 | 91.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 71 | 53 | 18 | 74.6% |
| vless | 306 | 198 | 108 | 64.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 52 |
| 204:TimeoutError | 41 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 17 |
| geo:ClientOSError | 15 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| cn-block:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6877 |
| ConnectionRefusedError | 1057 |
| gaierror | 268 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.853 | prefer | 461 | 0.781 | 1827 |
| Surfboard-tg-mixed | 0.572 | observe | 57 | 0.491 | 7166 |
| mheidari-all | 0.465 | observe | 7 | 0.714 | 24072 |
| ermaozi | 0.371 | observe | 59 | 0.339 | 659 |
| DeltaKronecker-all | 0.337 | observe | 13 | 0.308 | 5147 |
| ermaozi-get_subscribe | 0.332 | observe | 2 | 1.0 | 519 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 89 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7793 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.308 | 4 | 9 | 13 |
| ermaozi | 0.339 | 20 | 39 | 59 |
| Surfboard-tg-mixed | 0.491 | 28 | 29 | 57 |
| mheidari-all | 0.714 | 5 | 2 | 7 |
| Au1rxx-base64 | 0.781 | 360 | 101 | 461 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24072 | yes | 4.75 | 0 |
| SoliSpirit-all | 9888 | yes | 3.1 | 0 |
| Epodonios-all | 7793 | yes | 5.9 | 0 |
| Surfboard-tg-mixed | 7166 | yes | 3.38 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.61 | 0 |
| barry-far-vless | 5957 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 5625 | yes | 3.19 | 0 |
| DeltaKronecker-all | 5147 | yes | 4.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 0.45 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 2.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 99 |
| cn-block | 33 |
| geo | 25 |
| speed | 25 |
