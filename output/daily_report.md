# AutoNodes 每日报告

生成时间：2026-08-22 01:33:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 92902 |
| 去重后节点数 | 23044 |
| TCP 可达数 | 3000 |
| 真测通过数 | 790 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23044 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 40.9 |
| geo | 1.0 |
| probe | 57.5 |
| real_test | 179.1 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 179 | 174 | 5 | 97.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 194 | 179 | 15 | 92.3% |
| vless | 639 | 304 | 335 | 47.6% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 131 |
| geo:ClientOSError | 91 |
| speed:TimeoutError | 81 |
| speed:ClientOSError | 21 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 8 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 4 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4996 |
| ConnectionRefusedError | 942 |
| gaierror | 798 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 330 | 0.93 | 1933 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.878 | prefer | 250 | 0.8 | 6361 |
| mheidari-all | 0.457 | observe | 436 | 0.376 | 21889 |
| DeltaKronecker-all | 0.337 | observe | 7 | 0.429 | 4245 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 162 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 5148 |
| Pawdroid | 0.256 | observe | 1 | 1.0 | 20 |
| Epodonios-all | 0.255 | observe | 0 | None | 7089 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3985 |

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
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | nscl5-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.143 | 1 | 6 | 7 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.376 | 164 | 272 | 436 |
| DeltaKronecker-all | 0.429 | 3 | 4 | 7 |
| Surfboard-tg-mixed | 0.8 | 200 | 50 | 250 |
| Au1rxx-base64 | 0.93 | 307 | 23 | 330 |
| Pawdroid | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21889 | yes | 3.96 | 0 |
| SoliSpirit-all | 7133 | yes | 3.77 | 0 |
| Epodonios-all | 7089 | yes | 4.12 | 0 |
| Surfboard-tg-mixed | 6361 | yes | 2.88 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.42 | 0 |
| barry-far-vless | 5449 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 2.02 | 0 |
| Surfboard-tg-vless | 5127 | yes | 1.26 | 0 |
| DeltaKronecker-all | 4245 | yes | 4.41 | 0 |
| mahdibland-V2RayAggregator | 4091 | yes | 1.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 223 |
| speed | 104 |
| cn-block | 22 |
| 204 | 10 |
