# AutoNodes 每日报告

生成时间：2026-07-29 03:17:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76585 |
| 去重后节点数 | 21579 |
| TCP 可达数 | 3000 |
| 真测通过数 | 694 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21579 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 46.2 |
| geo | 1.4 |
| probe | 54.1 |
| real_test | 146.6 |
| tcp | 31.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 64 | 64 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 217 | 181 | 36 | 83.4% |
| socks | 9 | 7 | 2 | 77.8% |
| trojan | 95 | 86 | 9 | 90.5% |
| vless | 555 | 341 | 214 | 61.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 90 |
| geo:TimeoutError | 69 |
| speed:TimeoutError | 24 |
| geo:ClientOSError | 21 |
| speed:ClientOSError | 18 |
| 204:TimeoutError | 11 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 8 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4051 |
| ConnectionRefusedError | 740 |
| gaierror | 323 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 64 | 1.0 | 167 |
| Au1rxx-base64 | 0.921 | prefer | 301 | 0.877 | 1151 |
| DeltaKronecker-all | 0.724 | prefer | 489 | 0.644 | 4038 |
| Surfboard-tg-mixed | 0.654 | observe | 59 | 0.576 | 5708 |
| mheidari-all | 0.501 | observe | 36 | 0.417 | 17232 |
| 10ium-ScrapeCategorize-Vless | 0.287 | observe | 2 | 0.5 | 4972 |
| tg-Farah_VPN | 0.263 | observe | 1 | 1.0 | 200 |
| Epodonios-all | 0.255 | observe | 0 | None | 6752 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3968 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6491 |

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
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.417 | 15 | 21 | 36 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.576 | 34 | 25 | 59 |
| DeltaKronecker-all | 0.644 | 315 | 174 | 489 |
| Au1rxx-base64 | 0.877 | 264 | 37 | 301 |
| tg-Farah_VPN | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 64 | 0 | 64 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17232 | yes | 4.07 | 0 |
| Epodonios-all | 6752 | yes | 1.89 | 0 |
| SoliSpirit-all | 6491 | yes | 2.0 | 0 |
| Surfboard-tg-mixed | 5708 | yes | 3.16 | 0 |
| mahdibland-V2RayAggregator | 5059 | yes | 2.38 | 0 |
| barry-far-vless | 5026 | yes | 1.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 4480 | yes | 2.73 | 0 |
| DeltaKronecker-all | 4038 | yes | 3.43 | 0 |
| MatinGhanbari-all-sub | 3968 | yes | 1.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 100 |
| geo | 90 |
| speed | 43 |
| 204 | 28 |
