# AutoNodes 每日报告

生成时间：2026-10-20 21:34:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94587 |
| 去重后节点数 | 26417 |
| TCP 可达数 | 3000 |
| 真测通过数 | 347 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26417 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 81.7 |
| geo | 1.5 |
| probe | 203.7 |
| real_test | 190.1 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 13 | 19 | 40.6% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 142 | 125 | 17 | 88.0% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 45 | 39 | 6 | 86.7% |
| vless | 209 | 154 | 55 | 73.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 17 |
| 204:TimeoutError | 15 |
| speed:ClientOSError | 13 |
| 204:ProxyError | 12 |
| 204:ProxyConnectionError | 7 |
| geo:ClientOSError | 7 |
| geo:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6703 |
| ConnectionRefusedError | 1025 |
| OSError | 233 |
| gaierror | 175 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.893 | prefer | 73 | 0.822 | 23621 |
| Au1rxx-base64 | 0.887 | prefer | 256 | 0.832 | 1438 |
| Surfboard-tg-mixed | 0.808 | prefer | 79 | 0.734 | 6945 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 74 |
| zhangkai | 0.346 | observe | 27 | 0.333 | 31 |
| DeltaKronecker-all | 0.324 | observe | 8 | 0.375 | 3519 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7425 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9871 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| zhangkai | 0.333 | 9 | 18 | 27 |
| DeltaKronecker-all | 0.375 | 3 | 5 | 8 |
| Surfboard-tg-mixed | 0.734 | 58 | 21 | 79 |
| mheidari-all | 0.822 | 60 | 13 | 73 |
| Au1rxx-base64 | 0.832 | 213 | 43 | 256 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23621 | yes | 5.4 | 0 |
| SoliSpirit-all | 9871 | yes | 4.62 | 0 |
| Epodonios-all | 7425 | yes | 4.68 | 0 |
| Surfboard-tg-mixed | 6945 | yes | 3.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.87 | 0 |
| barry-far-vless | 5701 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 5487 | yes | 4.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 2.24 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 37 |
| speed | 31 |
| cn-block | 21 |
| geo | 12 |
