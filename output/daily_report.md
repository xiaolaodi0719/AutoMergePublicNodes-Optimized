# AutoNodes 每日报告

生成时间：2026-09-30 05:09:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96916 |
| 去重后节点数 | 27039 |
| TCP 可达数 | 3000 |
| 真测通过数 | 465 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27039 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 32.3 |
| geo | 1.5 |
| probe | 287.2 |
| real_test | 430.6 |
| tcp | 43.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 41 | 35 | 6 | 85.4% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 154 | 138 | 16 | 89.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 10 | 7 | 3 | 70.0% |
| vless | 660 | 261 | 399 | 39.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 163 |
| speed:TimeoutError | 74 |
| speed:ClientOSError | 65 |
| geo:ClientOSError | 52 |
| cn-block:TimeoutError | 25 |
| 204:ProxyError | 20 |
| 204:TimeoutError | 11 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5708 |
| ConnectionRefusedError | 1009 |
| gaierror | 406 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.861 | prefer | 299 | 0.793 | 1756 |
| ermaozi | 0.838 | prefer | 38 | 0.842 | 335 |
| Surfboard-tg-mixed | 0.762 | prefer | 42 | 0.69 | 7024 |
| ermaozi-get_subscribe | 0.453 | observe | 5 | 1.0 | 353 |
| mheidari-all | 0.398 | observe | 492 | 0.317 | 22586 |
| tg-oneclickvpnkeys | 0.361 | observe | 3 | 1.0 | 74 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| DeltaKronecker-all | 0.255 | observe | 9 | 0.222 | 5528 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5314 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.222 | 2 | 7 | 9 |
| mheidari-all | 0.317 | 156 | 336 | 492 |
| Surfboard-tg-mixed | 0.69 | 29 | 13 | 42 |
| Au1rxx-base64 | 0.793 | 237 | 62 | 299 |
| ermaozi | 0.842 | 32 | 6 | 38 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| ermaozi-get_subscribe | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22586 | yes | 6.55 | 0 |
| SoliSpirit-all | 9347 | yes | 3.09 | 0 |
| Epodonios-all | 7591 | yes | 5.61 | 0 |
| Surfboard-tg-mixed | 7024 | yes | 3.78 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.69 | 0 |
| barry-far-vless | 5895 | yes | 1.75 | 0 |
| Surfboard-tg-vless | 5656 | yes | 4.24 | 0 |
| DeltaKronecker-all | 5528 | yes | 5.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 5314 | yes | 1.26 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 1.47 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 215 |
| speed | 140 |
| 204 | 37 |
| cn-block | 34 |
