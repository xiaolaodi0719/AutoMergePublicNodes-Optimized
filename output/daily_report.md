# AutoNodes 每日报告

生成时间：2026-09-27 21:17:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96200 |
| 去重后节点数 | 26756 |
| TCP 可达数 | 3000 |
| 真测通过数 | 419 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26756 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 86.0 |
| geo | 1.5 |
| probe | 207.9 |
| real_test | 165.2 |
| tcp | 43.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 20 | 16 | 55.6% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 172 | 155 | 17 | 90.1% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 6 | 4 | 2 | 66.7% |
| vless | 272 | 217 | 55 | 79.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 21 |
| speed:ClientOSError | 20 |
| 204:ProxyConnectionError | 11 |
| geo:TimeoutError | 9 |
| speed:TimeoutError | 8 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5956 |
| ConnectionRefusedError | 977 |
| gaierror | 438 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.965 | prefer | 59 | 0.898 | 22680 |
| Au1rxx-base64 | 0.924 | prefer | 259 | 0.861 | 1652 |
| Surfboard-tg-mixed | 0.88 | prefer | 148 | 0.804 | 7018 |
| ermaozi | 0.579 | observe | 35 | 0.571 | 289 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6752 |
| DeltaKronecker-all | 0.284 | observe | 6 | 0.333 | 5466 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7540 |
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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 2 | 4 | 6 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.571 | 20 | 15 | 35 |
| Surfboard-tg-mixed | 0.804 | 119 | 29 | 148 |
| Au1rxx-base64 | 0.861 | 223 | 36 | 259 |
| mheidari-all | 0.898 | 53 | 6 | 59 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22680 | yes | 6.58 | 0 |
| SoliSpirit-all | 9353 | yes | 4.78 | 0 |
| Epodonios-all | 7540 | yes | 5.49 | 0 |
| Surfboard-tg-mixed | 7018 | yes | 4.25 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5823 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5592 | yes | 3.38 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.77 | 0 |
| mahdibland-V2RayAggregator | 4185 | yes | 0.3 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 29 |
| speed | 28 |
| 204 | 27 |
| geo | 10 |
