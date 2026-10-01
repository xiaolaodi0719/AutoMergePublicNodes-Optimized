# AutoNodes 每日报告

生成时间：2026-10-01 12:58:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98134 |
| 去重后节点数 | 27405 |
| TCP 可达数 | 3000 |
| 真测通过数 | 406 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27405 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 80.1 |
| geo | 1.5 |
| probe | 222.2 |
| real_test | 170.7 |
| tcp | 45.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 12 | 11 | 52.2% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 159 | 133 | 26 | 83.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 33 | 27 | 6 | 81.8% |
| vless | 309 | 214 | 95 | 69.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 58 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 17 |
| 204:ProxyConnectionError | 12 |
| geo:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| 204:ProxyError | 3 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6186 |
| ConnectionRefusedError | 1024 |
| gaierror | 426 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | prefer | 305 | 0.797 | 1787 |
| mheidari-all | 0.853 | prefer | 64 | 0.781 | 23162 |
| Surfboard-tg-mixed | 0.755 | prefer | 124 | 0.677 | 7144 |
| DeltaKronecker-all | 0.58 | observe | 24 | 0.5 | 5603 |
| zhangkai | 0.551 | observe | 20 | 0.55 | 144 |
| ermaozi | 0.442 | observe | 5 | 1.0 | 56 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7625 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9489 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.5 | 12 | 12 | 24 |
| zhangkai | 0.55 | 11 | 9 | 20 |
| Surfboard-tg-mixed | 0.677 | 84 | 40 | 124 |
| mheidari-all | 0.781 | 50 | 14 | 64 |
| Au1rxx-base64 | 0.797 | 243 | 62 | 305 |
| ermaozi | 1.0 | 5 | 0 | 5 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23162 | yes | 6.56 | 0 |
| SoliSpirit-all | 9489 | yes | 4.43 | 0 |
| Epodonios-all | 7625 | yes | 3.77 | 0 |
| Surfboard-tg-mixed | 7144 | yes | 4.74 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.23 | 0 |
| barry-far-vless | 6032 | yes | 2.15 | 0 |
| Surfboard-tg-vless | 5788 | yes | 4.27 | 0 |
| DeltaKronecker-all | 5603 | yes | 6.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 2.56 | 0 |
| mahdibland-V2RayAggregator | 4241 | yes | 3.41 | 0 |

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
| speed | 64 |
| 204 | 36 |
| cn-block | 25 |
| geo | 15 |
