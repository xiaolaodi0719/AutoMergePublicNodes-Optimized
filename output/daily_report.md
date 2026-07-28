# AutoNodes 每日报告

生成时间：2026-07-28 19:44:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 80840 |
| 去重后节点数 | 22955 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22955 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 33.9 |
| geo | 1.4 |
| probe | 52.7 |
| real_test | 119.0 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 165 | 127 | 38 | 77.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 45 | 33 | 12 | 73.3% |
| vless | 390 | 223 | 167 | 57.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 49 |
| geo:TimeoutError | 39 |
| cn-block:TimeoutError | 37 |
| 204:TimeoutError | 25 |
| geo:ClientOSError | 23 |
| speed:ClientOSError | 15 |
| cn-block:ProxyError | 11 |
| speed:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4131 |
| ConnectionRefusedError | 765 |
| gaierror | 350 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | prefer | 271 | 0.815 | 1312 |
| DeltaKronecker-all | 0.588 | observe | 329 | 0.508 | 5965 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 5820 |
| mheidari-all | 0.352 | observe | 6 | 0.5 | 17378 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4972 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6834 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3970 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6507 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4597 |

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
| zhangkai | 0.129 | observe | 1 | 0.0 | 0 | 33 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| zhangkai | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 3 | 3 | 6 |
| DeltaKronecker-all | 0.508 | 167 | 162 | 329 |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| Au1rxx-base64 | 0.815 | 221 | 50 | 271 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17378 | yes | 4.09 | 0 |
| Epodonios-all | 6834 | yes | 3.59 | 0 |
| SoliSpirit-all | 6507 | yes | 4.0 | 0 |
| DeltaKronecker-all | 5965 | yes | 4.27 | 0 |
| Surfboard-tg-mixed | 5820 | yes | 2.68 | 0 |
| barry-far-vless | 5117 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 5059 | yes | 2.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 4597 | yes | 2.84 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 80 |
| geo | 64 |
| cn-block | 51 |
| speed | 24 |
