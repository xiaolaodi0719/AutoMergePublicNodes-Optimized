# AutoNodes 每日报告

生成时间：2026-08-03 14:54:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 83610 |
| 去重后节点数 | 24688 |
| TCP 可达数 | 3000 |
| 真测通过数 | 556 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24688 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 27.4 |
| geo | 1.4 |
| probe | 59.2 |
| real_test | 131.5 |
| tcp | 37.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 67 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 148 | 127 | 21 | 85.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 16 | 15 | 1 | 93.8% |
| vless | 565 | 331 | 234 | 58.6% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 70 |
| 204:ProxyError | 34 |
| 204:TimeoutError | 32 |
| geo:TimeoutError | 30 |
| speed:TimeoutError | 30 |
| cn-block:TimeoutError | 23 |
| speed:ClientOSError | 21 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 8 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5120 |
| ConnectionRefusedError | 806 |
| gaierror | 236 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | prefer | 69 | 1.0 | 92 |
| Au1rxx-base64 | 0.806 | prefer | 518 | 0.739 | 1692 |
| mheidari-all | 0.55 | observe | 196 | 0.469 | 18776 |
| Surfboard-tg-mixed | 0.459 | observe | 27 | 0.37 | 5293 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 3833 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 54 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5285 |
| Epodonios-all | 0.255 | observe | 0 | None | 5890 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6783 |

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
| DeltaKronecker-all | 0.153 | downweight | 5 | 0.0 | 0 | 6205 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| Surfboard-tg-mixed | 0.37 | 10 | 17 | 27 |
| mheidari-all | 0.469 | 92 | 104 | 196 |
| Au1rxx-base64 | 0.739 | 383 | 135 | 518 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18776 | yes | 4.03 | 0 |
| SoliSpirit-all | 6783 | yes | 4.0 | 0 |
| DeltaKronecker-all | 6205 | yes | 3.2 | 0 |
| Epodonios-all | 5890 | yes | 3.3 | 0 |
| Surfboard-tg-mixed | 5293 | yes | 2.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5285 | yes | 2.07 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 1.92 | 0 |
| barry-far-vless | 4526 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 4162 | yes | 3.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 101 |
| 204 | 75 |
| speed | 53 |
| cn-block | 33 |
