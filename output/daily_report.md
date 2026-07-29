# AutoNodes 每日报告

生成时间：2026-07-29 08:53:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 77963 |
| 去重后节点数 | 22462 |
| TCP 可达数 | 3000 |
| 真测通过数 | 607 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22462 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 33.6 |
| geo | 1.3 |
| probe | 67.5 |
| real_test | 179.5 |
| tcp | 31.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 95 | 95 | 0 | 100.0% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 190 | 166 | 24 | 87.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 56 | 44 | 12 | 78.6% |
| vless | 741 | 291 | 450 | 39.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 217 |
| speed:TimeoutError | 58 |
| geo:ClientOSError | 50 |
| speed:ClientOSError | 47 |
| 204:ProxyError | 42 |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 25 |
| cn-block:ProxyError | 11 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4155 |
| ConnectionRefusedError | 703 |
| gaierror | 294 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 95 | 1.0 | 167 |
| Au1rxx-base64 | 0.905 | prefer | 268 | 0.858 | 1232 |
| Surfboard-tg-mixed | 0.68 | observe | 23 | 0.609 | 5706 |
| DeltaKronecker-all | 0.461 | observe | 693 | 0.381 | 5519 |
| mheidari-all | 0.286 | observe | 13 | 0.231 | 15942 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6451 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6039 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.231 | 3 | 10 | 13 |
| DeltaKronecker-all | 0.381 | 264 | 429 | 693 |
| Surfboard-tg-mixed | 0.609 | 14 | 9 | 23 |
| Au1rxx-base64 | 0.858 | 230 | 38 | 268 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 95 | 0 | 95 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15942 | yes | 3.69 | 0 |
| Epodonios-all | 6451 | yes | 2.27 | 0 |
| SoliSpirit-all | 6039 | yes | 4.16 | 0 |
| Surfboard-tg-mixed | 5706 | yes | 3.88 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 1.17 | 0 |
| mahdibland-V2RayAggregator | 5089 | yes | 2.53 | 0 |
| barry-far-vless | 4902 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 4505 | yes | 2.45 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 271 |
| speed | 105 |
| 204 | 75 |
| cn-block | 40 |
