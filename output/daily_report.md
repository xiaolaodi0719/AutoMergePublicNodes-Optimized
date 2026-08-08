# AutoNodes 每日报告

生成时间：2026-08-08 18:48:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83469 |
| 去重后节点数 | 23605 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23605 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 44.8 |
| geo | 1.0 |
| probe | 51.1 |
| real_test | 90.4 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 24 | 21 | 3 | 87.5% |
| shadowsocks | 144 | 131 | 13 | 91.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 148 | 131 | 17 | 88.5% |
| vless | 149 | 102 | 47 | 68.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 29 |
| cn-block:TimeoutError | 19 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 6 |
| speed:TimeoutError | 5 |
| geo:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4873 |
| ConnectionRefusedError | 827 |
| gaierror | 348 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | prefer | 338 | 0.926 | 1540 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.875 | prefer | 18 | 0.889 | 17642 |
| Surfboard-tg-mixed | 0.71 | prefer | 90 | 0.633 | 6620 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 7201 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7604 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5385 |
| barry-far-vless | 0.255 | observe | 0 | None | 5666 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.205 | 22 | 0.091 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.091 | 2 | 20 | 22 |
| Surfboard-tg-mixed | 0.633 | 57 | 33 | 90 |
| mheidari-all | 0.889 | 16 | 2 | 18 |
| Au1rxx-base64 | 0.926 | 313 | 25 | 338 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17642 | yes | 3.65 | 0 |
| SoliSpirit-all | 7604 | yes | 3.41 | 0 |
| Epodonios-all | 7201 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 6620 | yes | 2.55 | 0 |
| barry-far-vless | 5666 | yes | 2.64 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 2.28 | 0 |
| Surfboard-tg-vless | 5385 | yes | 2.95 | 0 |
| DeltaKronecker-all | 5347 | yes | 4.09 | 0 |
| mahdibland-V2RayAggregator | 5127 | yes | 2.33 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| cn-block | 23 |
| geo | 9 |
| speed | 8 |
