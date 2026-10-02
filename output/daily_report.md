# AutoNodes 每日报告

生成时间：2026-10-02 05:14:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 98630 |
| 去重后节点数 | 27538 |
| TCP 可达数 | 3000 |
| 真测通过数 | 427 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27538 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 34.3 |
| geo | 1.7 |
| probe | 346.0 |
| real_test | 505.2 |
| tcp | 47.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 3 | 4 | 42.9% |
| http | 24 | 17 | 7 | 70.8% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 165 | 155 | 10 | 93.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 12 | 9 | 3 | 75.0% |
| vless | 522 | 222 | 300 | 42.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 161 |
| speed:TimeoutError | 67 |
| geo:ClientOSError | 26 |
| 204:ProxyError | 19 |
| 204:TimeoutError | 19 |
| speed:ClientOSError | 17 |
| cn-block:TimeoutError | 10 |
| 204:ProxyConnectionError | 5 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6685 |
| ConnectionRefusedError | 1033 |
| gaierror | 371 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.971 | prefer | 253 | 0.905 | 1731 |
| Surfboard-tg-mixed | 0.803 | prefer | 45 | 0.733 | 7165 |
| ermaozi | 0.717 | prefer | 24 | 0.708 | 618 |
| mheidari-all | 0.431 | observe | 414 | 0.35 | 23308 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7654 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9200 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5778 |
| barry-far-vless | 0.255 | observe | 0 | None | 6015 |

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
| downweight | ermaozi-get_subscribe | 0.165 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| mheidari-all | 0.35 | 145 | 269 | 414 |
| ermaozi | 0.708 | 17 | 7 | 24 |
| Surfboard-tg-mixed | 0.733 | 33 | 12 | 45 |
| Au1rxx-base64 | 0.905 | 229 | 24 | 253 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23308 | yes | 5.86 | 0 |
| SoliSpirit-all | 9200 | yes | 2.67 | 0 |
| Epodonios-all | 7654 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 7165 | yes | 4.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.89 | 0 |
| barry-far-vless | 6015 | yes | 1.31 | 0 |
| Surfboard-tg-vless | 5778 | yes | 4.83 | 0 |
| DeltaKronecker-all | 5603 | yes | 4.13 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 3.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 188 |
| speed | 84 |
| 204 | 43 |
| cn-block | 12 |
