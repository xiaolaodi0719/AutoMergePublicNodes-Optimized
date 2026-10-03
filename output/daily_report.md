# AutoNodes 每日报告

生成时间：2026-10-03 04:54:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98934 |
| 去重后节点数 | 27176 |
| TCP 可达数 | 3000 |
| 真测通过数 | 453 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27176 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 73.8 |
| geo | 1.1 |
| probe | 257.8 |
| real_test | 336.6 |
| tcp | 47.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 4 | 1 | 80.0% |
| http | 24 | 19 | 5 | 79.2% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 165 | 144 | 21 | 87.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 45 | 31 | 14 | 68.9% |
| vless | 447 | 234 | 213 | 52.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 109 |
| speed:TimeoutError | 47 |
| cn-block:TimeoutError | 23 |
| geo:ClientOSError | 20 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 10 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6709 |
| ConnectionRefusedError | 1164 |
| gaierror | 369 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.96 | prefer | 271 | 0.893 | 1751 |
| ermaozi | 0.767 | prefer | 25 | 0.76 | 645 |
| Surfboard-tg-mixed | 0.756 | prefer | 183 | 0.678 | 7256 |
| mheidari-all | 0.364 | observe | 216 | 0.282 | 23323 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 4981 |
| ermaozi-get_subscribe | 0.341 | observe | 4 | 0.75 | 516 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5276 |
| Epodonios-all | 0.255 | observe | 0 | None | 7743 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.282 | 61 | 155 | 216 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.678 | 124 | 59 | 183 |
| ermaozi-get_subscribe | 0.75 | 3 | 1 | 4 |
| ermaozi | 0.76 | 19 | 6 | 25 |
| Au1rxx-base64 | 0.893 | 242 | 29 | 271 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23323 | yes | 4.81 | 0 |
| SoliSpirit-all | 9351 | yes | 1.59 | 0 |
| Epodonios-all | 7743 | yes | 2.95 | 0 |
| Surfboard-tg-mixed | 7256 | yes | 3.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.99 | 0 |
| barry-far-vless | 6214 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 5980 | yes | 3.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5276 | yes | 1.06 | 0 |
| DeltaKronecker-all | 4981 | yes | 5.16 | 0 |
| mahdibland-V2RayAggregator | 4357 | yes | 2.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 130 |
| speed | 58 |
| cn-block | 35 |
| 204 | 33 |
