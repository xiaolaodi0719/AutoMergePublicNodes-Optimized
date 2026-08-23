# AutoNodes 每日报告

生成时间：2026-08-23 01:47:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83081 |
| 去重后节点数 | 23824 |
| TCP 可达数 | 3000 |
| 真测通过数 | 858 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23824 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 31.7 |
| geo | 1.3 |
| probe | 60.7 |
| real_test | 168.7 |
| tcp | 40.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 114 | 114 | 0 | 100.0% |
| hysteria2 | 26 | 26 | 0 | 100.0% |
| shadowsocks | 188 | 185 | 3 | 98.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 177 | 168 | 9 | 94.9% |
| vless | 580 | 361 | 219 | 62.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 74 |
| speed:TimeoutError | 54 |
| geo:ClientOSError | 45 |
| cn-block:TimeoutError | 19 |
| speed:ClientOSError | 15 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 7 |
| 204:TimeoutError | 7 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5050 |
| ConnectionRefusedError | 998 |
| gaierror | 709 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 516 | 0.936 | 1658 |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.888 | prefer | 180 | 0.811 | 6297 |
| mheidari-all | 0.613 | observe | 165 | 0.533 | 14498 |
| xiaoji235-airport-v2ray-all | 0.43 | observe | 38 | 0.342 | 5974 |
| nscl5-all | 0.355 | observe | 2 | 1.0 | 1082 |
| tg-oneclickvpnkeys | 0.317 | observe | 2 | 1.0 | 146 |
| Epodonios-all | 0.255 | observe | 0 | None | 6920 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3986 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7010 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.249 | 69 | 0.159 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.159 | 11 | 58 | 69 |
| xiaoji235-airport-v2ray-all | 0.342 | 13 | 25 | 38 |
| mheidari-all | 0.533 | 88 | 77 | 165 |
| Surfboard-tg-mixed | 0.811 | 146 | 34 | 180 |
| Au1rxx-base64 | 0.936 | 483 | 33 | 516 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14498 | yes | 4.38 | 0 |
| SoliSpirit-all | 7010 | yes | 2.2 | 0 |
| Epodonios-all | 6920 | yes | 4.56 | 0 |
| Surfboard-tg-mixed | 6297 | yes | 3.25 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 3.29 | 0 |
| barry-far-vless | 5496 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5114 | yes | 3.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 1.06 | 0 |
| DeltaKronecker-all | 5015 | yes | 4.78 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 2.83 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 119 |
| speed | 69 |
| cn-block | 24 |
| 204 | 21 |
