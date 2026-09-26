# AutoNodes 每日报告

生成时间：2026-09-26 21:02:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96520 |
| 去重后节点数 | 26455 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26455 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 79.1 |
| geo | 1.4 |
| probe | 217.8 |
| real_test | 210.2 |
| tcp | 43.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 22 | 9 | 13 | 40.9% |
| hysteria2 | 26 | 26 | 0 | 100.0% |
| shadowsocks | 159 | 139 | 20 | 87.4% |
| socks | 5 | 0 | 5 | 0.0% |
| trojan | 12 | 8 | 4 | 66.7% |
| vless | 313 | 220 | 93 | 70.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 35 |
| 204:TimeoutError | 35 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 11 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 7 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 5 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6290 |
| ConnectionRefusedError | 954 |
| gaierror | 323 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.95 | prefer | 282 | 0.887 | 1654 |
| Surfboard-tg-mixed | 0.784 | prefer | 113 | 0.708 | 7263 |
| mheidari-all | 0.614 | observe | 114 | 0.535 | 22366 |
| ermaozi | 0.426 | observe | 19 | 0.421 | 296 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 5512 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7740 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.421 | 8 | 11 | 19 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.535 | 61 | 53 | 114 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Surfboard-tg-mixed | 0.708 | 80 | 33 | 113 |
| Au1rxx-base64 | 0.887 | 250 | 32 | 282 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22366 | yes | 5.1 | 0 |
| SoliSpirit-all | 8923 | yes | 5.2 | 0 |
| Epodonios-all | 7740 | yes | 2.87 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 4.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.58 | 0 |
| barry-far-vless | 6052 | yes | 2.79 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.22 | 0 |
| DeltaKronecker-all | 5512 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 2.73 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 1.54 | 0 |

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
| cn-block | 61 |
| 204 | 53 |
| speed | 13 |
| geo | 8 |
