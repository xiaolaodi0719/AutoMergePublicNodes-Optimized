# AutoNodes 每日报告

生成时间：2026-07-29 19:29:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 79381 |
| 去重后节点数 | 22734 |
| TCP 可达数 | 3000 |
| 真测通过数 | 469 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22734 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 11.6 |
| generate | 43.6 |
| geo | 1.4 |
| probe | 56.7 |
| real_test | 133.9 |
| tcp | 32.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 14 | 10 | 4 | 71.4% |
| shadowsocks | 189 | 139 | 50 | 73.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 27 | 21 | 6 | 77.8% |
| vless | 355 | 226 | 129 | 63.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 50 |
| 204:TimeoutError | 38 |
| cn-block:TimeoutError | 32 |
| speed:TimeoutError | 26 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4442 |
| ConnectionRefusedError | 731 |
| gaierror | 261 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 70 | 1.0 | 84 |
| Au1rxx-base64 | 0.818 | prefer | 276 | 0.764 | 1384 |
| DeltaKronecker-all | 0.683 | observe | 177 | 0.605 | 5519 |
| Surfboard-tg-mixed | 0.661 | observe | 127 | 0.583 | 5853 |
| mheidari-all | 0.489 | observe | 6 | 0.833 | 16105 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6489 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.583 | 74 | 53 | 127 |
| DeltaKronecker-all | 0.605 | 107 | 70 | 177 |
| Au1rxx-base64 | 0.764 | 211 | 65 | 276 |
| mheidari-all | 0.833 | 5 | 1 | 6 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16105 | yes | 4.8 | 0 |
| SoliSpirit-all | 6586 | yes | 1.79 | 0 |
| Epodonios-all | 6489 | yes | 2.53 | 0 |
| Surfboard-tg-mixed | 5853 | yes | 2.83 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.34 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 5076 | yes | 2.33 | 0 |
| barry-far-vless | 4922 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 4561 | yes | 2.99 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 64 |
| 204 | 51 |
| cn-block | 41 |
| speed | 34 |
