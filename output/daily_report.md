# AutoNodes 每日报告

生成时间：2026-09-25 11:40:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96970 |
| 去重后节点数 | 26321 |
| TCP 可达数 | 3000 |
| 真测通过数 | 316 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26321 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 34.2 |
| geo | 1.5 |
| probe | 297.4 |
| real_test | 126.6 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 44 | 29 | 15 | 65.9% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 134 | 121 | 13 | 90.3% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 12 | 4 | 8 | 33.3% |
| vless | 169 | 142 | 27 | 84.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 19 |
| 204:ProxyError | 17 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| speed:TimeoutError | 3 |
| speed:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| speed:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5823 |
| ConnectionRefusedError | 958 |
| gaierror | 386 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | prefer | 202 | 0.916 | 1624 |
| mheidari-all | 0.901 | prefer | 65 | 0.831 | 22444 |
| Surfboard-tg-mixed | 0.774 | prefer | 60 | 0.7 | 7280 |
| ermaozi | 0.666 | observe | 44 | 0.659 | 338 |
| DeltaKronecker-all | 0.446 | observe | 8 | 0.625 | 5452 |
| ermaozi-get_subscribe | 0.269 | observe | 1 | 1.0 | 359 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5293 |
| Epodonios-all | 0.255 | observe | 0 | None | 7869 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9069 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.625 | 5 | 3 | 8 |
| ermaozi | 0.659 | 29 | 15 | 44 |
| Surfboard-tg-mixed | 0.7 | 42 | 18 | 60 |
| mheidari-all | 0.831 | 54 | 11 | 65 |
| Au1rxx-base64 | 0.916 | 185 | 17 | 202 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22444 | yes | 6.08 | 0 |
| SoliSpirit-all | 9069 | yes | 1.33 | 0 |
| Epodonios-all | 7869 | yes | 0.64 | 0 |
| Surfboard-tg-mixed | 7280 | yes | 4.16 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.31 | 0 |
| barry-far-vless | 6140 | yes | 1.54 | 0 |
| Surfboard-tg-vless | 5801 | yes | 3.58 | 0 |
| DeltaKronecker-all | 5452 | yes | 4.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5293 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4324 | yes | 3.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 42 |
| cn-block | 16 |
| speed | 7 |
| geo | 3 |
