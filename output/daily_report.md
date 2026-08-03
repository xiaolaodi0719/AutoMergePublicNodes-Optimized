# AutoNodes 每日报告

生成时间：2026-08-03 19:49:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 84754 |
| 去重后节点数 | 25181 |
| TCP 可达数 | 3000 |
| 真测通过数 | 555 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25181 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.6 |
| generate | 39.6 |
| geo | 1.6 |
| probe | 60.8 |
| real_test | 135.4 |
| tcp | 37.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 14 | 10 | 4 | 71.4% |
| shadowsocks | 136 | 113 | 23 | 83.1% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 60 | 58 | 2 | 96.7% |
| vless | 497 | 301 | 196 | 60.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 92 |
| speed:TimeoutError | 26 |
| 204:ProxyError | 26 |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 17 |
| speed:ClientOSError | 8 |
| 204:ClientOSError | 7 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4828 |
| ConnectionRefusedError | 800 |
| gaierror | 285 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 67 | 1.0 | 92 |
| Au1rxx-base64 | 0.807 | prefer | 526 | 0.74 | 1718 |
| Surfboard-tg-mixed | 0.674 | observe | 30 | 0.6 | 5168 |
| mheidari-all | 0.643 | observe | 140 | 0.564 | 18750 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5127 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5757 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6825 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.129 | downweight | 15 | 0.0 | 0 | 6205 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.129 | 15 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 15 | 15 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.564 | 79 | 61 | 140 |
| Surfboard-tg-mixed | 0.6 | 18 | 12 | 30 |
| Au1rxx-base64 | 0.74 | 389 | 137 | 526 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 67 | 0 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18750 | yes | 4.52 | 0 |
| SoliSpirit-all | 6825 | yes | 3.22 | 0 |
| DeltaKronecker-all | 6205 | yes | 5.0 | 0 |
| Epodonios-all | 5757 | yes | 3.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 1.13 | 0 |
| Surfboard-tg-mixed | 5168 | yes | 3.68 | 0 |
| mahdibland-V2RayAggregator | 5152 | yes | 2.94 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 2.41 | 0 |
| barry-far-vless | 4498 | yes | 0.68 | 0 |
| Surfboard-tg-vless | 4147 | yes | 4.73 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 111 |
| 204 | 55 |
| speed | 34 |
| cn-block | 27 |
