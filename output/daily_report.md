# AutoNodes 每日报告

生成时间：2026-10-16 11:17:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99257 |
| 去重后节点数 | 27610 |
| TCP 可达数 | 3000 |
| 真测通过数 | 422 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27610 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 86.7 |
| geo | 1.5 |
| probe | 386.9 |
| real_test | 291.1 |
| tcp | 47.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 93 | 43 | 50 | 46.2% |
| hysteria2 | 18 | 14 | 4 | 77.8% |
| shadowsocks | 141 | 122 | 19 | 86.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 47 | 21 | 26 | 44.7% |
| vless | 325 | 221 | 104 | 68.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 50 |
| 204:ProxyError | 41 |
| cn-block:TimeoutError | 27 |
| speed:TimeoutError | 16 |
| 204:ProxyConnectionError | 15 |
| speed:ClientOSError | 14 |
| geo:ClientOSError | 11 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 6 |
| 204:ClientOSError | 5 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6422 |
| ConnectionRefusedError | 1065 |
| gaierror | 331 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.849 | prefer | 457 | 0.77 | 1990 |
| ermaozi | 0.49 | observe | 91 | 0.462 | 693 |
| Surfboard-tg-mixed | 0.485 | observe | 35 | 0.4 | 7090 |
| mheidari-all | 0.474 | observe | 15 | 0.467 | 23871 |
| DeltaKronecker-all | 0.33 | observe | 26 | 0.231 | 4946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7568 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10065 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.231 | 6 | 20 | 26 |
| Surfboard-tg-mixed | 0.4 | 14 | 21 | 35 |
| ermaozi | 0.462 | 42 | 49 | 91 |
| mheidari-all | 0.467 | 7 | 8 | 15 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.77 | 352 | 105 | 457 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23871 | yes | 6.1 | 0 |
| SoliSpirit-all | 10065 | yes | 5.89 | 0 |
| Epodonios-all | 7568 | yes | 6.32 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 4.7 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 5.34 | 0 |
| barry-far-vless | 5827 | yes | 3.27 | 0 |
| Surfboard-tg-vless | 5572 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 3.51 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.73 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 0.28 | 0 |

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
| 204 | 111 |
| cn-block | 41 |
| speed | 30 |
| geo | 24 |
