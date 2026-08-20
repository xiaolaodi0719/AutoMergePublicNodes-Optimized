# AutoNodes 每日报告

生成时间：2026-08-20 07:00:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 93905 |
| 去重后节点数 | 25131 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1283 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25131 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 28.9 |
| geo | 0.9 |
| probe | 75.8 |
| real_test | 217.1 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 110 | 110 | 0 | 100.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 179 | 170 | 9 | 95.0% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 777 | 766 | 11 | 98.6% |
| vless | 321 | 214 | 107 | 66.7% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 43 |
| geo:ClientOSError | 25 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 9 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5055 |
| ConnectionRefusedError | 964 |
| gaierror | 471 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 712 | 0.969 | 1789 |
| mheidari-all | 0.998 | prefer | 327 | 0.92 | 21143 |
| zhangkai | 0.997 | prefer | 110 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.849 | prefer | 232 | 0.772 | 6418 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7111 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7230 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5062 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| DeltaKronecker-all | 0.171 | downweight | 31 | 0.065 | 0 | 6781 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.171 | 31 | 0.065 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.065 | 2 | 29 | 31 |
| Surfboard-tg-mixed | 0.772 | 179 | 53 | 232 |
| mheidari-all | 0.92 | 301 | 26 | 327 |
| Au1rxx-base64 | 0.969 | 690 | 22 | 712 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 110 | 0 | 110 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21143 | yes | 3.57 | 0 |
| SoliSpirit-all | 7230 | yes | 4.11 | 0 |
| Epodonios-all | 7111 | yes | 3.72 | 0 |
| DeltaKronecker-all | 6781 | yes | 3.8 | 0 |
| Surfboard-tg-mixed | 6418 | yes | 2.61 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.22 | 0 |
| barry-far-vless | 5404 | yes | 1.65 | 0 |
| Surfboard-tg-vless | 5062 | yes | 3.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.8 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 2.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 68 |
| speed | 25 |
| 204 | 22 |
| cn-block | 17 |
