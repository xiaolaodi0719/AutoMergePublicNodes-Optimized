# AutoNodes 每日报告

生成时间：2026-10-17 20:34:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99282 |
| 去重后节点数 | 27771 |
| TCP 可达数 | 3000 |
| 真测通过数 | 399 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27771 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 82.9 |
| geo | 1.5 |
| probe | 273.4 |
| real_test | 289.8 |
| tcp | 48.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 33 | 26 | 7 | 78.8% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 122 | 110 | 12 | 90.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 37 | 34 | 3 | 91.9% |
| vless | 289 | 212 | 77 | 73.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| 204:ProxyConnectionError | 17 |
| speed:ClientOSError | 16 |
| speed:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| geo:TimeoutError | 8 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6743 |
| ConnectionRefusedError | 1056 |
| gaierror | 293 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.887 | prefer | 444 | 0.809 | 1992 |
| ermaozi | 0.819 | prefer | 32 | 0.812 | 623 |
| mheidari-all | 0.646 | observe | 13 | 0.769 | 23876 |
| Surfboard-tg-mixed | 0.385 | observe | 8 | 0.5 | 7109 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| Epodonios-all | 0.255 | observe | 0 | None | 7590 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10112 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5614 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.0 | 0 | 4 | 4 |
| Surfboard-tg-mixed | 0.5 | 4 | 4 | 8 |
| mheidari-all | 0.769 | 10 | 3 | 13 |
| Au1rxx-base64 | 0.809 | 359 | 85 | 444 |
| ermaozi | 0.812 | 26 | 6 | 32 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23876 | yes | 6.32 | 0 |
| SoliSpirit-all | 10112 | yes | 6.58 | 0 |
| Epodonios-all | 7590 | yes | 6.54 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 4.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.86 | 0 |
| barry-far-vless | 5860 | yes | 4.01 | 0 |
| Surfboard-tg-vless | 5614 | yes | 4.52 | 0 |
| DeltaKronecker-all | 4999 | yes | 7.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 3.92 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 0.99 | 0 |

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
| 204 | 46 |
| speed | 30 |
| cn-block | 19 |
| geo | 10 |
