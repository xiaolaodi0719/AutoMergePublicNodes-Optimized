# AutoNodes 每日报告

生成时间：2026-10-04 05:25:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 99344 |
| 去重后节点数 | 27384 |
| TCP 可达数 | 3000 |
| 真测通过数 | 462 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27384 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 75.2 |
| geo | 0.9 |
| probe | 260.9 |
| real_test | 319.3 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 23 | 17 | 6 | 73.9% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 167 | 148 | 19 | 88.6% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 89 | 70 | 19 | 78.7% |
| vless | 402 | 208 | 194 | 51.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 97 |
| speed:TimeoutError | 43 |
| cn-block:TimeoutError | 24 |
| geo:ClientOSError | 20 |
| 204:ProxyError | 14 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 7 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6680 |
| ConnectionRefusedError | 1181 |
| gaierror | 430 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.94 | prefer | 293 | 0.87 | 1797 |
| Surfboard-tg-mixed | 0.808 | prefer | 171 | 0.731 | 7318 |
| ermaozi | 0.718 | prefer | 24 | 0.708 | 646 |
| mheidari-all | 0.393 | observe | 199 | 0.312 | 23371 |
| Epodonios-all | 0.255 | observe | 0 | None | 7797 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9571 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5909 |
| barry-far-vless | 0.255 | observe | 0 | None | 6122 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4285 |

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
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| mheidari-all | 0.312 | 62 | 137 | 199 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.708 | 17 | 7 | 24 |
| Surfboard-tg-mixed | 0.731 | 125 | 46 | 171 |
| Au1rxx-base64 | 0.87 | 255 | 38 | 293 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23371 | yes | 6.62 | 0 |
| SoliSpirit-all | 9571 | yes | 2.57 | 0 |
| Epodonios-all | 7797 | yes | 3.58 | 0 |
| Surfboard-tg-mixed | 7318 | yes | 4.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.21 | 0 |
| barry-far-vless | 6122 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 5909 | yes | 4.09 | 0 |
| DeltaKronecker-all | 5207 | yes | 6.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 5192 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4285 | yes | 3.65 | 0 |

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
| geo | 117 |
| speed | 55 |
| 204 | 37 |
| cn-block | 33 |
