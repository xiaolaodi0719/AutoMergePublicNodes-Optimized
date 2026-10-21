# AutoNodes 每日报告

生成时间：2026-10-21 04:15:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 95343 |
| 去重后节点数 | 26611 |
| TCP 可达数 | 3000 |
| 真测通过数 | 445 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26611 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 77.3 |
| geo | 1.4 |
| probe | 217.4 |
| real_test | 305.8 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 60 | 34 | 26 | 56.7% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 169 | 157 | 12 | 92.9% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 39 | 34 | 5 | 87.2% |
| vless | 365 | 204 | 161 | 55.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 72 |
| 204:ProxyError | 38 |
| geo:ClientOSError | 29 |
| speed:ClientOSError | 24 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 13 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6670 |
| ConnectionRefusedError | 1029 |
| OSError | 232 |
| gaierror | 200 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.919 | prefer | 301 | 0.864 | 1433 |
| Surfboard-tg-mixed | 0.91 | prefer | 51 | 0.843 | 7115 |
| zhangkai | 0.592 | observe | 20 | 0.6 | 31 |
| ermaozi-get_subscribe | 0.579 | observe | 41 | 0.561 | 516 |
| mheidari-all | 0.533 | observe | 234 | 0.453 | 23653 |
| DeltaKronecker-all | 0.259 | observe | 3 | 0.333 | 3519 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10016 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.453 | 106 | 128 | 234 |
| ermaozi-get_subscribe | 0.561 | 23 | 18 | 41 |
| zhangkai | 0.6 | 12 | 8 | 20 |
| Surfboard-tg-mixed | 0.843 | 43 | 8 | 51 |
| Au1rxx-base64 | 0.864 | 260 | 41 | 301 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23653 | yes | 4.46 | 0 |
| SoliSpirit-all | 10016 | yes | 1.96 | 0 |
| Epodonios-all | 7598 | yes | 4.74 | 0 |
| Surfboard-tg-mixed | 7115 | yes | 3.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.86 | 0 |
| barry-far-vless | 5764 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 5552 | yes | 2.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 2.16 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 102 |
| 204 | 45 |
| speed | 40 |
| cn-block | 20 |
