# AutoNodes 每日报告

生成时间：2026-10-21 21:37:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96052 |
| 去重后节点数 | 26993 |
| TCP 可达数 | 3000 |
| 真测通过数 | 360 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26993 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 78.7 |
| geo | 1.5 |
| probe | 261.4 |
| real_test | 211.1 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 15 | 17 | 46.9% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 160 | 145 | 15 | 90.6% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 53 | 49 | 4 | 92.5% |
| vless | 211 | 138 | 73 | 65.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 16 |
| speed:ClientOSError | 13 |
| geo:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 2 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6578 |
| ConnectionRefusedError | 1061 |
| gaierror | 275 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.88 | prefer | 58 | 0.81 | 23903 |
| Au1rxx-base64 | 0.857 | prefer | 250 | 0.796 | 1596 |
| Surfboard-tg-mixed | 0.856 | prefer | 123 | 0.78 | 7033 |
| zhangkai | 0.518 | observe | 27 | 0.519 | 31 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 4067 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7500 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10005 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5488 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| zhangkai | 0.519 | 14 | 13 | 27 |
| Surfboard-tg-mixed | 0.78 | 96 | 27 | 123 |
| Au1rxx-base64 | 0.796 | 199 | 51 | 250 |
| mheidari-all | 0.81 | 47 | 11 | 58 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23903 | yes | 2.87 | 0 |
| SoliSpirit-all | 10005 | yes | 4.5 | 0 |
| Epodonios-all | 7500 | yes | 4.46 | 0 |
| Surfboard-tg-mixed | 7033 | yes | 4.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5734 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 5488 | yes | 3.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 2.68 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 2.21 | 0 |
| DeltaKronecker-all | 4067 | yes | 4.58 | 0 |

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
| 204 | 43 |
| cn-block | 29 |
| speed | 22 |
| geo | 18 |
