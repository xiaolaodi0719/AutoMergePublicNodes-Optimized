# AutoNodes 每日报告

生成时间：2026-08-05 02:57:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 86570 |
| 去重后节点数 | 24355 |
| TCP 可达数 | 3000 |
| 真测通过数 | 593 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24355 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 28.9 |
| geo | 1.4 |
| probe | 55.8 |
| real_test | 150.5 |
| tcp | 35.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 53 | 52 | 1 | 98.1% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 167 | 157 | 10 | 94.0% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 166 | 152 | 14 | 91.6% |
| vless | 568 | 208 | 360 | 36.6% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 161 |
| speed:TimeoutError | 72 |
| speed:ClientOSError | 66 |
| geo:ClientOSError | 46 |
| cn-block:TimeoutError | 23 |
| 204:ClientOSError | 6 |
| 204:TimeoutError | 5 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4630 |
| ConnectionRefusedError | 851 |
| gaierror | 357 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 408 | 0.949 | 1440 |
| zhangkai | 0.984 | prefer | 51 | 1.0 | 72 |
| Surfboard-tg-mixed | 0.675 | observe | 183 | 0.596 | 5655 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 6252 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7076 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4478 |
| barry-far-vless | 0.255 | observe | 0 | None | 4815 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | mheidari-all | 0.215 | 295 | 0.132 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.22 | 41 | 0.122 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.122 | 5 | 36 | 41 |
| mheidari-all | 0.132 | 39 | 256 | 295 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.596 | 109 | 74 | 183 |
| Au1rxx-base64 | 0.949 | 387 | 21 | 408 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 51 | 0 | 51 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20244 | yes | 5.23 | 0 |
| SoliSpirit-all | 7076 | yes | 2.38 | 0 |
| Epodonios-all | 6252 | yes | 2.45 | 0 |
| DeltaKronecker-all | 5788 | yes | 5.09 | 0 |
| Surfboard-tg-mixed | 5655 | yes | 3.23 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 2.03 | 0 |
| mahdibland-V2RayAggregator | 5141 | yes | 2.62 | 0 |
| barry-far-vless | 4815 | yes | 1.8 | 0 |
| xiaoji235-airport-v2ray-all | 4655 | yes | 1.56 | 0 |
| Surfboard-tg-vless | 4478 | yes | 3.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 208 |
| speed | 139 |
| cn-block | 28 |
| 204 | 16 |
