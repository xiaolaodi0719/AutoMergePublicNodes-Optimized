# AutoNodes 每日报告

生成时间：2026-10-21 11:39:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 95751 |
| 去重后节点数 | 26901 |
| TCP 可达数 | 3000 |
| 真测通过数 | 351 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26901 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 82.9 |
| geo | 1.6 |
| probe | 240.2 |
| real_test | 232.2 |
| tcp | 44.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 88 | 36 | 52 | 40.9% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 147 | 129 | 18 | 87.8% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 50 | 33 | 17 | 66.0% |
| vless | 218 | 139 | 79 | 63.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 44 |
| 204:TimeoutError | 29 |
| cn-block:TimeoutError | 24 |
| speed:TimeoutError | 17 |
| geo:ClientOSError | 14 |
| speed:ClientOSError | 13 |
| 204:ProxyConnectionError | 10 |
| geo:TimeoutError | 8 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6523 |
| ConnectionRefusedError | 1035 |
| gaierror | 258 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.906 | prefer | 44 | 0.841 | 23726 |
| Au1rxx-base64 | 0.82 | prefer | 272 | 0.761 | 1528 |
| Surfboard-tg-mixed | 0.726 | prefer | 97 | 0.649 | 6977 |
| ermaozi-get_subscribe | 0.475 | observe | 64 | 0.453 | 516 |
| DeltaKronecker-all | 0.382 | observe | 14 | 0.357 | 4067 |
| zhangkai | 0.358 | observe | 26 | 0.346 | 31 |
| Au1rxx-clash | 0.317 | observe | 1 | 1.0 | 1541 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7465 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| zhangkai | 0.346 | 9 | 17 | 26 |
| DeltaKronecker-all | 0.357 | 5 | 9 | 14 |
| ermaozi-get_subscribe | 0.453 | 29 | 35 | 64 |
| Surfboard-tg-mixed | 0.649 | 63 | 34 | 97 |
| Au1rxx-base64 | 0.761 | 207 | 65 | 272 |
| mheidari-all | 0.841 | 37 | 7 | 44 |
| Au1rxx-clash | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23726 | yes | 4.41 | 0 |
| SoliSpirit-all | 10023 | yes | 2.86 | 0 |
| Epodonios-all | 7465 | yes | 4.67 | 0 |
| Surfboard-tg-mixed | 6977 | yes | 0.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.79 | 0 |
| barry-far-vless | 5674 | yes | 0.92 | 0 |
| Surfboard-tg-vless | 5462 | yes | 3.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 1.11 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 2.7 | 0 |
| DeltaKronecker-all | 4067 | yes | 4.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 83 |
| speed | 30 |
| cn-block | 30 |
| geo | 25 |
