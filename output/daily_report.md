# AutoNodes 每日报告

生成时间：2026-10-08 13:19:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 98622 |
| 去重后节点数 | 27533 |
| TCP 可达数 | 3000 |
| 真测通过数 | 439 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27533 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| generate | 93.0 |
| geo | 1.5 |
| probe | 297.0 |
| real_test | 212.8 |
| tcp | 46.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 1 | 5 | 16.7% |
| http | 34 | 11 | 23 | 32.4% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 162 | 145 | 17 | 89.5% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 78 | 67 | 11 | 85.9% |
| vless | 264 | 202 | 62 | 76.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 20 |
| 204:ProxyConnectionError | 16 |
| 204:ProxyError | 14 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 11 |
| geo:TimeoutError | 7 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6118 |
| ConnectionRefusedError | 1015 |
| gaierror | 451 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.963 | prefer | 344 | 0.892 | 1824 |
| mheidari-all | 0.902 | prefer | 43 | 0.837 | 23417 |
| Surfboard-tg-mixed | 0.747 | prefer | 118 | 0.669 | 7320 |
| zhangkai | 0.527 | observe | 21 | 0.524 | 144 |
| DeltaKronecker-all | 0.298 | observe | 11 | 0.273 | 5197 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5081 |
| Epodonios-all | 0.255 | observe | 0 | None | 7669 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| downweight | ermaozi-get_subscribe | 0.114 | 19 | 0.053 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.053 | 1 | 18 | 19 |
| DeltaKronecker-all | 0.273 | 3 | 8 | 11 |
| zhangkai | 0.524 | 11 | 10 | 21 |
| Surfboard-tg-mixed | 0.669 | 79 | 39 | 118 |
| mheidari-all | 0.837 | 36 | 7 | 43 |
| Au1rxx-base64 | 0.892 | 307 | 37 | 344 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23417 | yes | 7.06 | 0 |
| SoliSpirit-all | 9654 | yes | 4.77 | 0 |
| Epodonios-all | 7669 | yes | 4.21 | 0 |
| Surfboard-tg-mixed | 7320 | yes | 5.95 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.12 | 0 |
| barry-far-vless | 5968 | yes | 3.34 | 0 |
| Surfboard-tg-vless | 5776 | yes | 4.43 | 0 |
| DeltaKronecker-all | 5197 | yes | 7.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5081 | yes | 3.12 | 0 |
| mahdibland-V2RayAggregator | 4431 | yes | 3.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 58 |
| cn-block | 25 |
| geo | 19 |
| speed | 17 |
