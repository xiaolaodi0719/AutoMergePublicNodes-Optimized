# AutoNodes 每日报告

生成时间：2026-08-04 03:02:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/3 |
| 清理建议：优先/观察 | 2/102 |
| 原始节点数 | 85783 |
| 去重后节点数 | 24686 |
| TCP 可达数 | 3000 |
| 真测通过数 | 680 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24686 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 43.1 |
| geo | 1.5 |
| probe | 59.2 |
| real_test | 166.3 |
| tcp | 36.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 160 | 151 | 9 | 94.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 116 | 102 | 14 | 87.9% |
| vless | 807 | 337 | 470 | 41.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 245 |
| speed:TimeoutError | 101 |
| speed:ClientOSError | 58 |
| geo:ClientOSError | 50 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4660 |
| ConnectionRefusedError | 798 |
| gaierror | 309 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 67 | 1.0 | 92 |
| Au1rxx-base64 | 0.886 | prefer | 627 | 0.82 | 1682 |
| Surfboard-tg-mixed | 0.494 | observe | 131 | 0.412 | 5262 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6831 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4123 |
| barry-far-vless | 0.255 | observe | 0 | None | 4484 |

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
| ninja-vless | 0.14 | downweight | 6 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ninja-vless | 0.14 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.183 | 37 | 0.081 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | mheidari-all | 0.216 | 306 | 0.134 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.081 | 3 | 34 | 37 |
| mheidari-all | 0.134 | 41 | 265 | 306 |
| Surfboard-tg-mixed | 0.412 | 54 | 77 | 131 |
| Au1rxx-base64 | 0.82 | 514 | 113 | 627 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 67 | 0 | 67 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19963 | yes | 6.05 | 0 |
| SoliSpirit-all | 6831 | yes | 6.15 | 0 |
| DeltaKronecker-all | 6205 | yes | 6.35 | 0 |
| Epodonios-all | 5848 | yes | 5.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 3.43 | 0 |
| Surfboard-tg-mixed | 5262 | yes | 4.16 | 0 |
| mahdibland-V2RayAggregator | 5152 | yes | 3.43 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 1.92 | 0 |
| barry-far-vless | 4484 | yes | 2.18 | 0 |
| Surfboard-tg-vless | 4123 | yes | 3.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 295 |
| speed | 159 |
| cn-block | 21 |
| 204 | 21 |
