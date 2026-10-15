# AutoNodes 每日报告

生成时间：2026-10-15 11:23:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 1/106 |
| 原始节点数 | 99769 |
| 去重后节点数 | 27811 |
| TCP 可达数 | 3000 |
| 真测通过数 | 408 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27811 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 17.9 |
| generate | 84.0 |
| geo | 1.5 |
| probe | 406.1 |
| real_test | 293.9 |
| tcp | 48.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 81 | 34 | 47 | 42.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 146 | 130 | 16 | 89.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 70 | 43 | 27 | 61.4% |
| vless | 278 | 187 | 91 | 67.3% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 46 |
| 204:TimeoutError | 45 |
| cn-block:TimeoutError | 20 |
| geo:ClientOSError | 13 |
| geo:TimeoutError | 12 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| 204:ProxyConnectionError | 10 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 3 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7063 |
| ConnectionRefusedError | 1039 |
| OSError | 236 |
| gaierror | 208 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.848 | prefer | 451 | 0.778 | 1769 |
| ermaozi | 0.452 | observe | 83 | 0.422 | 703 |
| Surfboard-tg-mixed | 0.418 | observe | 10 | 0.5 | 7139 |
| DeltaKronecker-all | 0.413 | observe | 34 | 0.324 | 5147 |
| ermaozi-get_subscribe | 0.335 | observe | 2 | 1.0 | 595 |
| mheidari-all | 0.324 | observe | 8 | 0.375 | 24005 |
| peasoft-NoMoreWalls | 0.261 | observe | 1 | 1.0 | 147 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| Epodonios-all | 0.255 | observe | 0 | None | 7652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.324 | 11 | 23 | 34 |
| mheidari-all | 0.375 | 3 | 5 | 8 |
| ermaozi | 0.422 | 35 | 48 | 83 |
| Surfboard-tg-mixed | 0.5 | 5 | 5 | 10 |
| Au1rxx-base64 | 0.778 | 351 | 100 | 451 |
| peasoft-NoMoreWalls | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24005 | yes | 5.81 | 0 |
| SoliSpirit-all | 10113 | yes | 3.45 | 0 |
| Epodonios-all | 7652 | yes | 3.96 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.82 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.91 | 0 |
| barry-far-vless | 5924 | yes | 2.07 | 0 |
| Surfboard-tg-vless | 5693 | yes | 3.58 | 0 |
| DeltaKronecker-all | 5147 | yes | 6.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.68 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 2.96 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 105 |
| cn-block | 29 |
| geo | 28 |
| speed | 24 |
