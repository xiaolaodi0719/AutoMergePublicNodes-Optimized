# AutoNodes 每日报告

生成时间：2026-07-23 03:34:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81983 |
| 去重后节点数 | 22676 |
| TCP 可达数 | 3000 |
| 真测通过数 | 808 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22676 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.8 |
| generate | 29.5 |
| geo | 1.0 |
| probe | 69.8 |
| real_test | 207.0 |
| tcp | 31.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 149 | 137 | 12 | 91.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 536 | 492 | 44 | 91.8% |
| vless | 570 | 136 | 434 | 23.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 234 |
| speed:ClientOSError | 103 |
| cn-block:TimeoutError | 47 |
| speed:TimeoutError | 45 |
| geo:ClientOSError | 35 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4102 |
| ConnectionRefusedError | 710 |
| gaierror | 329 |
| OSError | 220 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.858 | prefer | 211 | 0.844 | 432 |
| DeltaKronecker-all | 0.677 | observe | 184 | 0.598 | 5212 |
| mheidari-all | 0.638 | observe | 857 | 0.558 | 19379 |
| Surfboard-tg-mixed | 0.401 | observe | 7 | 0.571 | 5286 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 4399 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4613 |
| Epodonios-all | 0.255 | observe | 0 | None | 6359 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.558 | 478 | 379 | 857 |
| Surfboard-tg-mixed | 0.571 | 4 | 3 | 7 |
| DeltaKronecker-all | 0.598 | 110 | 74 | 184 |
| Au1rxx-base64 | 0.844 | 178 | 33 | 211 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19379 | yes | 2.66 | 0 |
| SoliSpirit-all | 6912 | yes | 1.27 | 0 |
| Epodonios-all | 6359 | yes | 1.21 | 0 |
| Surfboard-tg-mixed | 5286 | yes | 1.57 | 0 |
| DeltaKronecker-all | 5212 | yes | 2.76 | 0 |
| mahdibland-V2RayAggregator | 4954 | yes | 1.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4613 | yes | 0.99 | 0 |
| barry-far-vless | 4602 | yes | 0.85 | 0 |
| xiaoji235-airport-v2ray-all | 4399 | yes | 0.74 | 0 |
| Surfboard-tg-vless | 4008 | yes | 1.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 269 |
| speed | 149 |
| cn-block | 55 |
| 204 | 19 |
