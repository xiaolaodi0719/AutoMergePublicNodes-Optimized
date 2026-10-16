# AutoNodes 每日报告

生成时间：2026-10-16 04:11:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99761 |
| 去重后节点数 | 27965 |
| TCP 可达数 | 3000 |
| 真测通过数 | 538 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27965 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 77.7 |
| geo | 1.4 |
| probe | 261.2 |
| real_test | 374.8 |
| tcp | 48.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 39 | 27 | 12 | 69.2% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 158 | 147 | 11 | 93.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 70 | 62 | 8 | 88.6% |
| vless | 474 | 280 | 194 | 59.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 70 |
| speed:TimeoutError | 43 |
| speed:ClientOSError | 31 |
| geo:ClientOSError | 27 |
| 204:ProxyError | 17 |
| 204:TimeoutError | 12 |
| cn-block:ClientOSError | 10 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7008 |
| ConnectionRefusedError | 1033 |
| OSError | 239 |
| gaierror | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.88 | prefer | 555 | 0.802 | 1991 |
| ermaozi | 0.728 | prefer | 38 | 0.711 | 693 |
| Surfboard-tg-mixed | 0.688 | observe | 72 | 0.611 | 7135 |
| ermaozi-get_subscribe | 0.381 | observe | 3 | 1.0 | 574 |
| mheidari-all | 0.295 | observe | 77 | 0.208 | 23985 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |
| Epodonios-all | 0.255 | observe | 0 | None | 7647 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| downweight | DeltaKronecker-all | 0.225 | 16 | 0.125 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.125 | 2 | 14 | 16 |
| mheidari-all | 0.208 | 16 | 61 | 77 |
| Surfboard-tg-mixed | 0.611 | 44 | 28 | 72 |
| ermaozi | 0.711 | 27 | 11 | 38 |
| Au1rxx-base64 | 0.802 | 445 | 110 | 555 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23985 | yes | 3.51 | 0 |
| SoliSpirit-all | 9903 | yes | 2.99 | 0 |
| Epodonios-all | 7647 | yes | 3.13 | 0 |
| Surfboard-tg-mixed | 7135 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.94 | 0 |
| barry-far-vless | 5878 | yes | 1.55 | 0 |
| Surfboard-tg-vless | 5628 | yes | 2.36 | 0 |
| DeltaKronecker-all | 5147 | yes | 4.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.33 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 1.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 97 |
| speed | 75 |
| 204 | 32 |
| cn-block | 22 |
