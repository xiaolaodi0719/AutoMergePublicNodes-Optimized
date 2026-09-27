# AutoNodes 每日报告

生成时间：2026-09-27 11:55:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 95691 |
| 去重后节点数 | 26593 |
| TCP 可达数 | 3000 |
| 真测通过数 | 416 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26593 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 83.2 |
| geo | 1.7 |
| probe | 266.4 |
| real_test | 183.8 |
| tcp | 44.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 71 | 43 | 28 | 60.6% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 170 | 150 | 20 | 88.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 19 | 14 | 5 | 73.7% |
| vless | 243 | 188 | 55 | 77.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 30 |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 15 |
| speed:TimeoutError | 13 |
| geo:TimeoutError | 11 |
| speed:ClientOSError | 8 |
| cn-block:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6302 |
| ConnectionRefusedError | 937 |
| gaierror | 308 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | prefer | 278 | 0.878 | 1589 |
| mheidari-all | 0.883 | prefer | 69 | 0.812 | 22397 |
| Surfboard-tg-mixed | 0.764 | prefer | 93 | 0.688 | 7025 |
| ermaozi | 0.658 | observe | 57 | 0.649 | 338 |
| DeltaKronecker-all | 0.533 | observe | 14 | 0.571 | 5466 |
| ermaozi-get_subscribe | 0.401 | observe | 16 | 0.438 | 361 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7510 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8971 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.438 | 7 | 9 | 16 |
| DeltaKronecker-all | 0.571 | 8 | 6 | 14 |
| ermaozi | 0.649 | 37 | 20 | 57 |
| Surfboard-tg-mixed | 0.688 | 64 | 29 | 93 |
| mheidari-all | 0.812 | 56 | 13 | 69 |
| Au1rxx-base64 | 0.878 | 244 | 34 | 278 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22397 | yes | 6.61 | 0 |
| SoliSpirit-all | 8971 | yes | 4.25 | 0 |
| Epodonios-all | 7510 | yes | 0.95 | 0 |
| Surfboard-tg-mixed | 7025 | yes | 3.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.73 | 0 |
| barry-far-vless | 5862 | yes | 4.53 | 0 |
| Surfboard-tg-vless | 5637 | yes | 4.03 | 0 |
| DeltaKronecker-all | 5466 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 5.02 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 0.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 55 |
| speed | 22 |
| cn-block | 21 |
| geo | 15 |
