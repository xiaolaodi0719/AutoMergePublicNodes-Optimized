# AutoNodes 每日报告

生成时间：2026-10-13 14:07:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99026 |
| 去重后节点数 | 27329 |
| TCP 可达数 | 3000 |
| 真测通过数 | 393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27329 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| generate | 88.4 |
| geo | 1.2 |
| probe | 303.8 |
| real_test | 311.8 |
| tcp | 46.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 4 | 0 | 100.0% |
| http | 26 | 11 | 15 | 42.3% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 151 | 131 | 20 | 86.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 129 | 111 | 18 | 86.0% |
| vless | 173 | 126 | 47 | 72.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 32 |
| 204:TimeoutError | 24 |
| 204:ProxyError | 14 |
| geo:TimeoutError | 10 |
| speed:TimeoutError | 6 |
| 204:ProxyConnectionError | 4 |
| 204:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6032 |
| ConnectionRefusedError | 1045 |
| gaierror | 441 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.932 | prefer | 317 | 0.864 | 1754 |
| mheidari-all | 0.813 | prefer | 43 | 0.744 | 24075 |
| Surfboard-tg-mixed | 0.77 | prefer | 69 | 0.696 | 7201 |
| DeltaKronecker-all | 0.756 | prefer | 35 | 0.686 | 5076 |
| zhangkai | 0.572 | observe | 13 | 0.769 | 144 |
| ermaozi-get_subscribe | 0.302 | observe | 18 | 0.278 | 534 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5086 |
| Epodonios-all | 0.255 | observe | 0 | None | 7717 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9931 |

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
| ermaozi-get_subscribe | 0.278 | 5 | 13 | 18 |
| DeltaKronecker-all | 0.686 | 24 | 11 | 35 |
| Surfboard-tg-mixed | 0.696 | 48 | 21 | 69 |
| mheidari-all | 0.744 | 32 | 11 | 43 |
| zhangkai | 0.769 | 10 | 3 | 13 |
| Au1rxx-base64 | 0.864 | 274 | 43 | 317 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24075 | yes | 7.13 | 0 |
| SoliSpirit-all | 9931 | yes | 2.7 | 0 |
| Epodonios-all | 7717 | yes | 7.59 | 0 |
| Surfboard-tg-mixed | 7201 | yes | 4.94 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.13 | 0 |
| barry-far-vless | 5973 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5723 | yes | 4.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5086 | yes | 0.55 | 0 |
| DeltaKronecker-all | 5076 | yes | 5.2 | 0 |
| mahdibland-V2RayAggregator | 4312 | yes | 3.63 | 0 |

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
| 204 | 46 |
| cn-block | 35 |
| geo | 12 |
| speed | 10 |
