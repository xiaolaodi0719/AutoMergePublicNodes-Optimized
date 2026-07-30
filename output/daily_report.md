# AutoNodes 每日报告

生成时间：2026-07-30 19:46:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78433 |
| 去重后节点数 | 23046 |
| TCP 可达数 | 3000 |
| 真测通过数 | 529 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23046 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 47.4 |
| geo | 1.4 |
| probe | 64.3 |
| real_test | 162.0 |
| tcp | 33.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 11 | 8 | 3 | 72.7% |
| shadowsocks | 122 | 96 | 26 | 78.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 25 | 16 | 9 | 64.0% |
| vless | 517 | 294 | 223 | 56.9% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 86 |
| geo:TimeoutError | 40 |
| 204:ProxyError | 40 |
| 204:TimeoutError | 26 |
| geo:ClientOSError | 22 |
| speed:TimeoutError | 16 |
| speed:ClientOSError | 12 |
| cn-block:ProxyError | 7 |
| speed:ProxyError | 7 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4525 |
| ConnectionRefusedError | 745 |
| gaierror | 264 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.833 | prefer | 266 | 0.778 | 1430 |
| DeltaKronecker-all | 0.582 | observe | 400 | 0.502 | 5759 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 16222 |
| Surfboard-tg-mixed | 0.385 | observe | 8 | 0.5 | 5387 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6090 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6594 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.5 | 4 | 4 | 8 |
| DeltaKronecker-all | 0.502 | 201 | 199 | 400 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.778 | 207 | 59 | 266 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16222 | yes | 4.46 | 0 |
| SoliSpirit-all | 6594 | yes | 3.88 | 0 |
| Epodonios-all | 6090 | yes | 4.64 | 0 |
| DeltaKronecker-all | 5759 | yes | 4.9 | 0 |
| Surfboard-tg-mixed | 5387 | yes | 2.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 2.88 | 0 |
| mahdibland-V2RayAggregator | 5047 | yes | 4.0 | 0 |
| barry-far-vless | 4589 | yes | 2.36 | 0 |
| Surfboard-tg-vless | 4264 | yes | 3.54 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 97 |
| 204 | 69 |
| geo | 63 |
| speed | 35 |
