# AutoNodes 每日报告

生成时间：2026-10-18 04:08:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 1/105 |
| 原始节点数 | 99131 |
| 去重后节点数 | 27861 |
| TCP 可达数 | 3000 |
| 真测通过数 | 524 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27861 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 85.7 |
| geo | 1.5 |
| probe | 306.0 |
| real_test | 403.5 |
| tcp | 47.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 101 | 53 | 48 | 52.5% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 128 | 124 | 4 | 96.9% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 46 | 38 | 8 | 82.6% |
| vless | 476 | 284 | 192 | 59.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 88 |
| 204:ProxyError | 55 |
| geo:ClientOSError | 29 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 18 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 15 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6706 |
| ConnectionRefusedError | 1057 |
| gaierror | 412 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | prefer | 482 | 0.842 | 1798 |
| ermaozi | 0.567 | observe | 102 | 0.539 | 710 |
| Surfboard-tg-mixed | 0.48 | observe | 4 | 1.0 | 7181 |
| mheidari-all | 0.406 | observe | 176 | 0.324 | 23946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Epodonios-all | 0.255 | observe | 0 | None | 7667 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9901 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5616 |
| barry-far-vless | 0.255 | observe | 0 | None | 5884 |

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
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| mheidari-all | 0.324 | 57 | 119 | 176 |
| ermaozi | 0.539 | 55 | 47 | 102 |
| Au1rxx-base64 | 0.842 | 406 | 76 | 482 |
| Surfboard-tg-mixed | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23946 | yes | 4.05 | 0 |
| SoliSpirit-all | 9901 | yes | 4.39 | 0 |
| Epodonios-all | 7667 | yes | 3.57 | 0 |
| Surfboard-tg-mixed | 7181 | yes | 4.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.11 | 0 |
| barry-far-vless | 5884 | yes | 2.43 | 0 |
| Surfboard-tg-vless | 5616 | yes | 3.31 | 0 |
| DeltaKronecker-all | 4999 | yes | 4.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.26 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 118 |
| 204 | 77 |
| speed | 33 |
| cn-block | 26 |
