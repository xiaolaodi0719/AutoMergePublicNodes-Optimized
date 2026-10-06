# AutoNodes 每日报告

生成时间：2026-10-06 05:59:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 98384 |
| 去重后节点数 | 27442 |
| TCP 可达数 | 3000 |
| 真测通过数 | 513 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27442 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 75.6 |
| geo | 1.5 |
| probe | 289.2 |
| real_test | 421.6 |
| tcp | 46.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 1 | 4 | 20.0% |
| http | 59 | 34 | 25 | 57.6% |
| hysteria2 | 22 | 20 | 2 | 90.9% |
| shadowsocks | 123 | 115 | 8 | 93.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 111 | 104 | 7 | 93.7% |
| vless | 517 | 238 | 279 | 46.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 151 |
| speed:TimeoutError | 56 |
| geo:ClientOSError | 40 |
| 204:ProxyError | 32 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 10 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6357 |
| ConnectionRefusedError | 1039 |
| gaierror | 352 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | prefer | 351 | 0.926 | 1801 |
| DeltaKronecker-all | 0.727 | prefer | 32 | 0.656 | 5300 |
| ermaozi | 0.601 | observe | 59 | 0.576 | 691 |
| Surfboard-tg-mixed | 0.53 | observe | 10 | 0.7 | 7083 |
| mheidari-all | 0.409 | observe | 378 | 0.328 | 23039 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7631 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9601 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5600 |

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
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| mheidari-all | 0.328 | 124 | 254 | 378 |
| ermaozi | 0.576 | 34 | 25 | 59 |
| DeltaKronecker-all | 0.656 | 21 | 11 | 32 |
| Surfboard-tg-mixed | 0.7 | 7 | 3 | 10 |
| Au1rxx-base64 | 0.926 | 325 | 26 | 351 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23039 | yes | 6.53 | 0 |
| SoliSpirit-all | 9601 | yes | 3.66 | 0 |
| Epodonios-all | 7631 | yes | 7.28 | 0 |
| Surfboard-tg-mixed | 7083 | yes | 4.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.64 | 0 |
| barry-far-vless | 5876 | yes | 2.93 | 0 |
| Surfboard-tg-vless | 5600 | yes | 4.31 | 0 |
| DeltaKronecker-all | 5300 | yes | 5.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 2.42 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 3.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 192 |
| speed | 67 |
| 204 | 52 |
| cn-block | 15 |
