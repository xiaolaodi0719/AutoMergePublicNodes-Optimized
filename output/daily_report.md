# AutoNodes 每日报告

生成时间：2026-09-15 16:49:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 91321 |
| 去重后节点数 | 25727 |
| TCP 可达数 | 3000 |
| 真测通过数 | 418 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25727 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 84.7 |
| geo | 1.5 |
| probe | 226.5 |
| real_test | 219.8 |
| tcp | 42.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 25 | 10 | 15 | 40.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 162 | 146 | 16 | 90.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 402 | 238 | 164 | 59.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 55 |
| geo:ClientOSError | 40 |
| 204:TimeoutError | 30 |
| cn-block:TimeoutError | 24 |
| 204:ProxyError | 11 |
| speed:ClientOSError | 11 |
| 204:ProxyConnectionError | 10 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 6 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5714 |
| ConnectionRefusedError | 939 |
| gaierror | 418 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | prefer | 309 | 0.874 | 1553 |
| Surfboard-tg-mixed | 0.68 | observe | 88 | 0.602 | 7516 |
| mheidari-all | 0.517 | observe | 188 | 0.436 | 21913 |
| ermaozi | 0.416 | observe | 23 | 0.391 | 406 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 5932 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 422 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8076 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9411 |

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
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.391 | 9 | 14 | 23 |
| mheidari-all | 0.436 | 82 | 106 | 188 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.602 | 53 | 35 | 88 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.874 | 270 | 39 | 309 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21913 | yes | 5.64 | 0 |
| SoliSpirit-all | 9411 | yes | 1.79 | 0 |
| Epodonios-all | 8076 | yes | 5.04 | 0 |
| Surfboard-tg-mixed | 7516 | yes | 4.33 | 0 |
| barry-far-vless | 6401 | yes | 0.57 | 0 |
| Surfboard-tg-vless | 6065 | yes | 4.0 | 0 |
| DeltaKronecker-all | 5932 | yes | 5.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.79 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 3.08 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.15 | 0 |

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
| cn-block | 80 |
| 204 | 51 |
| geo | 46 |
| speed | 20 |
