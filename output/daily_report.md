# AutoNodes 每日报告

生成时间：2026-10-20 04:27:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 94708 |
| 去重后节点数 | 26191 |
| TCP 可达数 | 3000 |
| 真测通过数 | 390 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26191 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 82.5 |
| geo | 1.5 |
| probe | 237.9 |
| real_test | 267.7 |
| tcp | 43.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 27 | 23 | 54.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 138 | 129 | 9 | 93.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 55 | 50 | 5 | 90.9% |
| vless | 305 | 164 | 141 | 53.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 64 |
| geo:ClientOSError | 22 |
| cn-block:TimeoutError | 18 |
| 204:ProxyConnectionError | 16 |
| 204:ProxyError | 15 |
| speed:ClientOSError | 13 |
| speed:TimeoutError | 11 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6302 |
| ConnectionRefusedError | 1036 |
| gaierror | 338 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.988 | prefer | 74 | 0.919 | 6911 |
| Au1rxx-base64 | 0.874 | prefer | 287 | 0.819 | 1424 |
| zhangkai | 0.819 | prefer | 20 | 0.85 | 27 |
| mheidari-all | 0.476 | observe | 147 | 0.395 | 23317 |
| ermaozi-get_subscribe | 0.354 | observe | 31 | 0.323 | 510 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7516 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10162 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5515 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.239 | 12 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.167 | 2 | 10 | 12 |
| ermaozi-get_subscribe | 0.323 | 10 | 21 | 31 |
| mheidari-all | 0.395 | 58 | 89 | 147 |
| Au1rxx-base64 | 0.819 | 235 | 52 | 287 |
| zhangkai | 0.85 | 17 | 3 | 20 |
| Surfboard-tg-mixed | 0.919 | 68 | 6 | 74 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23317 | yes | 6.24 | 0 |
| SoliSpirit-all | 10162 | yes | 6.14 | 0 |
| Epodonios-all | 7516 | yes | 4.73 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 3.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.81 | 0 |
| barry-far-vless | 5797 | yes | 3.67 | 0 |
| Surfboard-tg-vless | 5515 | yes | 3.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 3.91 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 0.57 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 86 |
| 204 | 43 |
| speed | 27 |
| cn-block | 25 |
