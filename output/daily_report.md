# AutoNodes 每日报告

生成时间：2026-09-11 20:55:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83905 |
| 去重后节点数 | 23390 |
| TCP 可达数 | 3000 |
| 真测通过数 | 416 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23390 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 76.7 |
| geo | 1.4 |
| probe | 273.1 |
| real_test | 216.9 |
| tcp | 40.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 9 | 13 | 40.9% |
| hysteria2 | 26 | 23 | 3 | 88.5% |
| shadowsocks | 164 | 148 | 16 | 90.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 17 | 15 | 2 | 88.2% |
| vless | 329 | 220 | 109 | 66.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 48 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 19 |
| speed:ClientOSError | 12 |
| cn-block:ClientOSError | 11 |
| 204:ClientOSError | 6 |
| geo:TimeoutError | 3 |
| geo:ProxyError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5551 |
| ConnectionRefusedError | 909 |
| gaierror | 489 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.931 | prefer | 274 | 0.869 | 1630 |
| mheidari-all | 0.78 | prefer | 88 | 0.705 | 15494 |
| DeltaKronecker-all | 0.776 | prefer | 21 | 0.714 | 6070 |
| Surfboard-tg-mixed | 0.674 | observe | 153 | 0.595 | 7355 |
| ermaozi | 0.458 | observe | 15 | 0.533 | 377 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 194 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7810 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9022 |

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
| downweight | ermaozi-get_subscribe | 0.144 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| ermaozi | 0.533 | 8 | 7 | 15 |
| Surfboard-tg-mixed | 0.595 | 91 | 62 | 153 |
| mheidari-all | 0.705 | 62 | 26 | 88 |
| DeltaKronecker-all | 0.714 | 15 | 6 | 21 |
| Au1rxx-base64 | 0.869 | 238 | 36 | 274 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15494 | yes | 2.93 | 0 |
| SoliSpirit-all | 9022 | yes | 2.35 | 0 |
| Epodonios-all | 7810 | yes | 2.03 | 0 |
| Surfboard-tg-mixed | 7355 | yes | 2.37 | 0 |
| barry-far-vless | 6209 | yes | 1.39 | 0 |
| DeltaKronecker-all | 6070 | yes | 3.14 | 0 |
| Surfboard-tg-vless | 5993 | yes | 2.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 1.64 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 1.87 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.44 | 0 |

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
| geo | 53 |
| 204 | 45 |
| cn-block | 32 |
| speed | 14 |
