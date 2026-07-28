# AutoNodes 每日报告

生成时间：2026-07-28 08:48:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86095 |
| 去重后节点数 | 23310 |
| TCP 可达数 | 3000 |
| 真测通过数 | 731 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23310 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 42.9 |
| geo | 1.3 |
| probe | 63.1 |
| real_test | 180.5 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 157 | 144 | 13 | 91.7% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 408 | 351 | 57 | 86.0% |
| vless | 283 | 151 | 132 | 53.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 62 |
| cn-block:TimeoutError | 32 |
| geo:ClientOSError | 29 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 17 |
| speed:TimeoutError | 16 |
| 204:ProxyError | 14 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4435 |
| ConnectionRefusedError | 744 |
| gaierror | 270 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.989 | prefer | 412 | 0.937 | 1345 |
| zhangkai | 0.989 | prefer | 69 | 1.0 | 81 |
| Surfboard-tg-mixed | 0.711 | prefer | 166 | 0.633 | 5743 |
| mheidari-all | 0.707 | prefer | 140 | 0.629 | 18776 |
| DeltaKronecker-all | 0.659 | observe | 138 | 0.58 | 5965 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4972 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 3959 |
| Epodonios-all | 0.255 | observe | 0 | None | 6749 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3972 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.58 | 80 | 58 | 138 |
| mheidari-all | 0.629 | 88 | 52 | 140 |
| Surfboard-tg-mixed | 0.633 | 105 | 61 | 166 |
| Au1rxx-base64 | 0.937 | 386 | 26 | 412 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18776 | yes | 5.57 | 0 |
| Epodonios-all | 6749 | yes | 2.32 | 0 |
| SoliSpirit-all | 6579 | yes | 1.78 | 0 |
| DeltaKronecker-all | 5965 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 5743 | yes | 3.63 | 0 |
| barry-far-vless | 5112 | yes | 1.07 | 0 |
| mahdibland-V2RayAggregator | 4991 | yes | 2.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 0.86 | 0 |
| Surfboard-tg-vless | 4586 | yes | 3.35 | 0 |
| MatinGhanbari-all-sub | 3972 | yes | 1.32 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 93 |
| cn-block | 41 |
| 204 | 37 |
| speed | 34 |
