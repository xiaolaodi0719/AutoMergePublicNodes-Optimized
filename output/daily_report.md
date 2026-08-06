# AutoNodes 每日报告

生成时间：2026-08-06 03:00:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 88972 |
| 去重后节点数 | 24629 |
| TCP 可达数 | 3000 |
| 真测通过数 | 545 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24629 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| generate | 25.4 |
| geo | 1.5 |
| probe | 57.1 |
| real_test | 131.9 |
| tcp | 37.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 15 | 15 | 0 | 100.0% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 161 | 154 | 7 | 95.7% |
| socks | 18 | 15 | 3 | 83.3% |
| trojan | 167 | 159 | 8 | 95.2% |
| vless | 491 | 180 | 311 | 36.7% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 151 |
| speed:TimeoutError | 50 |
| speed:ClientOSError | 45 |
| cn-block:TimeoutError | 33 |
| geo:ClientOSError | 32 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:status | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5126 |
| ConnectionRefusedError | 818 |
| gaierror | 276 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 380 | 0.963 | 1395 |
| zhangkai | 0.789 | prefer | 15 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.649 | observe | 200 | 0.57 | 5908 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 5214 |
| nscl5-all | 0.272 | observe | 2 | 0.5 | 1621 |
| mheidari-all | 0.269 | observe | 241 | 0.187 | 21048 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5260 |
| Epodonios-all | 0.255 | observe | 0 | None | 6515 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| downweight | DeltaKronecker-all | 0.177 | 29 | 0.069 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 6 | 6 |
| DeltaKronecker-all | 0.069 | 2 | 27 | 29 |
| mheidari-all | 0.187 | 45 | 196 | 241 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.57 | 114 | 86 | 200 |
| Au1rxx-base64 | 0.963 | 366 | 14 | 380 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 15 | 0 | 15 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21048 | yes | 4.34 | 0 |
| SoliSpirit-all | 7399 | yes | 4.5 | 0 |
| Epodonios-all | 6515 | yes | 4.9 | 0 |
| Surfboard-tg-mixed | 5908 | yes | 3.75 | 0 |
| DeltaKronecker-all | 5316 | yes | 5.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 5260 | yes | 2.27 | 0 |
| xiaoji235-airport-v2ray-all | 5214 | yes | 0.67 | 0 |
| mahdibland-V2RayAggregator | 5206 | yes | 2.52 | 0 |
| barry-far-vless | 5104 | yes | 2.49 | 0 |
| Surfboard-tg-vless | 4791 | yes | 3.55 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 185 |
| speed | 95 |
| cn-block | 39 |
| 204 | 13 |
