# AutoNodes 每日报告

生成时间：2026-10-22 04:15:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96952 |
| 去重后节点数 | 27043 |
| TCP 可达数 | 3000 |
| 真测通过数 | 325 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27043 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 75.3 |
| geo | 1.6 |
| probe | 206.9 |
| real_test | 210.4 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 53 | 21 | 32 | 39.6% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 162 | 152 | 10 | 93.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 80 | 59 | 21 | 73.8% |
| vless | 195 | 78 | 117 | 40.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 70 |
| 204:ProxyError | 45 |
| geo:ClientOSError | 20 |
| speed:ClientOSError | 18 |
| 204:ProxyConnectionError | 8 |
| cn-block:TimeoutError | 7 |
| speed:TimeoutError | 5 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6467 |
| ConnectionRefusedError | 1050 |
| gaierror | 282 |
| OSError | 239 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.988 | prefer | 142 | 0.93 | 1599 |
| Surfboard-tg-mixed | 0.85 | prefer | 72 | 0.778 | 7097 |
| mheidari-all | 0.603 | observe | 212 | 0.524 | 24252 |
| zhangkai | 0.547 | observe | 20 | 0.55 | 31 |
| ermaozi-get_subscribe | 0.335 | observe | 33 | 0.303 | 523 |
| DeltaKronecker-all | 0.294 | observe | 26 | 0.192 | 4067 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10125 |

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
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.192 | 5 | 21 | 26 |
| ermaozi-get_subscribe | 0.303 | 10 | 23 | 33 |
| mheidari-all | 0.524 | 111 | 101 | 212 |
| zhangkai | 0.55 | 11 | 9 | 20 |
| Surfboard-tg-mixed | 0.778 | 56 | 16 | 72 |
| Au1rxx-base64 | 0.93 | 132 | 10 | 142 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24252 | yes | 6.77 | 0 |
| SoliSpirit-all | 10125 | yes | 4.85 | 0 |
| Epodonios-all | 7591 | yes | 5.43 | 0 |
| Surfboard-tg-mixed | 7097 | yes | 4.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.41 | 0 |
| barry-far-vless | 5773 | yes | 2.62 | 0 |
| Surfboard-tg-vless | 5559 | yes | 5.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 2.99 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 0.19 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 90 |
| 204 | 60 |
| speed | 23 |
| cn-block | 9 |
