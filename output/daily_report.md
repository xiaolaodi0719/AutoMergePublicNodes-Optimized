# AutoNodes 每日报告

生成时间：2026-10-06 13:15:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 97839 |
| 去重后节点数 | 26950 |
| TCP 可达数 | 3000 |
| 真测通过数 | 486 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26950 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 90.8 |
| geo | 1.5 |
| probe | 238.7 |
| real_test | 189.5 |
| tcp | 45.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 10 | 0 | 10 | 0.0% |
| http | 74 | 30 | 44 | 40.5% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 163 | 148 | 15 | 90.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 107 | 98 | 9 | 91.6% |
| vless | 257 | 185 | 72 | 72.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 45 |
| 204:ProxyConnectionError | 19 |
| 204:TimeoutError | 18 |
| geo:ClientOSError | 15 |
| cn-block:TimeoutError | 15 |
| cn-block:ClientOSError | 13 |
| speed:TimeoutError | 10 |
| geo:TimeoutError | 9 |
| speed:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5913 |
| ConnectionRefusedError | 1032 |
| gaierror | 510 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 318 | 0.931 | 1805 |
| Surfboard-tg-mixed | 0.911 | prefer | 57 | 0.842 | 7050 |
| mheidari-all | 0.867 | prefer | 59 | 0.797 | 23204 |
| DeltaKronecker-all | 0.618 | observe | 117 | 0.538 | 4889 |
| ermaozi | 0.446 | observe | 77 | 0.416 | 708 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7553 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9571 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5573 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.08 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 10 | 10 |
| ermaozi | 0.416 | 32 | 45 | 77 |
| DeltaKronecker-all | 0.538 | 63 | 54 | 117 |
| mheidari-all | 0.797 | 47 | 12 | 59 |
| Surfboard-tg-mixed | 0.842 | 48 | 9 | 57 |
| Au1rxx-base64 | 0.931 | 296 | 22 | 318 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23204 | yes | 6.68 | 0 |
| SoliSpirit-all | 9571 | yes | 2.48 | 0 |
| Epodonios-all | 7553 | yes | 3.75 | 0 |
| Surfboard-tg-mixed | 7050 | yes | 4.22 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.17 | 0 |
| barry-far-vless | 5839 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5573 | yes | 4.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.4 | 0 |
| DeltaKronecker-all | 4889 | yes | 5.57 | 0 |
| mahdibland-V2RayAggregator | 4373 | yes | 2.01 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 82 |
| cn-block | 30 |
| geo | 25 |
| speed | 17 |
