# AutoNodes 每日报告

生成时间：2026-10-08 05:39:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99165 |
| 去重后节点数 | 27686 |
| TCP 可达数 | 3000 |
| 真测通过数 | 477 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27686 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 82.6 |
| geo | 1.5 |
| probe | 277.7 |
| real_test | 346.6 |
| tcp | 46.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 1 | 5 | 16.7% |
| http | 59 | 29 | 30 | 49.2% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 167 | 151 | 16 | 90.4% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 118 | 93 | 25 | 78.8% |
| vless | 392 | 177 | 215 | 45.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 122 |
| 204:ProxyError | 40 |
| speed:TimeoutError | 30 |
| geo:ClientOSError | 27 |
| 204:TimeoutError | 22 |
| speed:ClientOSError | 19 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6002 |
| ConnectionRefusedError | 1018 |
| gaierror | 460 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | prefer | 330 | 0.897 | 1772 |
| Surfboard-tg-mixed | 0.708 | prefer | 143 | 0.629 | 7193 |
| ermaozi-get_subscribe | 0.575 | observe | 27 | 0.556 | 592 |
| ermaozi | 0.457 | observe | 40 | 0.425 | 715 |
| mheidari-all | 0.343 | observe | 211 | 0.261 | 23407 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5138 |
| Epodonios-all | 0.255 | observe | 0 | None | 7663 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.228 | 15 | 0.133 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.133 | 2 | 13 | 15 |
| mheidari-all | 0.261 | 55 | 156 | 211 |
| ermaozi | 0.425 | 17 | 23 | 40 |
| ermaozi-get_subscribe | 0.556 | 15 | 12 | 27 |
| Surfboard-tg-mixed | 0.629 | 90 | 53 | 143 |
| Au1rxx-base64 | 0.897 | 296 | 34 | 330 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23407 | yes | 6.18 | 0 |
| SoliSpirit-all | 9552 | yes | 4.54 | 0 |
| Epodonios-all | 7663 | yes | 3.95 | 0 |
| Surfboard-tg-mixed | 7193 | yes | 4.94 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.12 | 0 |
| barry-far-vless | 5963 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 5725 | yes | 4.57 | 0 |
| DeltaKronecker-all | 5344 | yes | 7.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5138 | yes | 3.4 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 149 |
| 204 | 68 |
| speed | 49 |
| cn-block | 26 |
