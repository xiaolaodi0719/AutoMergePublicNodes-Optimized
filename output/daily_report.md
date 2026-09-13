# AutoNodes 每日报告

生成时间：2026-09-13 04:26:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 3/102 |
| 原始节点数 | 94343 |
| 去重后节点数 | 25322 |
| TCP 可达数 | 3000 |
| 真测通过数 | 550 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25322 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 81.2 |
| geo | 1.4 |
| probe | 327.2 |
| real_test | 545.8 |
| tcp | 41.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 29 | 19 | 10 | 65.5% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 174 | 162 | 12 | 93.1% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 20 | 9 | 11 | 45.0% |
| vless | 838 | 334 | 504 | 39.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 165 |
| geo:ClientOSError | 100 |
| speed:TimeoutError | 81 |
| speed:ClientOSError | 66 |
| cn-block:ClientOSError | 39 |
| 204:ProxyError | 33 |
| 204:TimeoutError | 31 |
| cn-block:TimeoutError | 15 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |
| geo:exit-country | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5497 |
| ConnectionRefusedError | 955 |
| gaierror | 445 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | prefer | 372 | 0.86 | 1653 |
| ermaozi | 0.777 | prefer | 23 | 0.783 | 436 |
| Surfboard-tg-mixed | 0.701 | prefer | 93 | 0.624 | 7432 |
| mheidari-all | 0.344 | observe | 569 | 0.264 | 20709 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 141 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8736 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.147 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.16 | 23 | 0.043 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.043 | 1 | 22 | 23 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.264 | 150 | 419 | 569 |
| Surfboard-tg-mixed | 0.624 | 58 | 35 | 93 |
| ermaozi | 0.783 | 18 | 5 | 23 |
| Au1rxx-base64 | 0.86 | 320 | 52 | 372 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20709 | yes | 6.43 | 0 |
| SoliSpirit-all | 8736 | yes | 5.24 | 0 |
| Epodonios-all | 7895 | yes | 2.3 | 0 |
| Surfboard-tg-mixed | 7432 | yes | 4.96 | 0 |
| barry-far-vless | 6259 | yes | 2.18 | 0 |
| Surfboard-tg-vless | 6027 | yes | 4.36 | 0 |
| DeltaKronecker-all | 5970 | yes | 6.24 | 0 |
| xiaoji235-airport-v2ray-all | 5301 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 2.61 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 0.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 267 |
| speed | 147 |
| 204 | 70 |
| cn-block | 57 |
