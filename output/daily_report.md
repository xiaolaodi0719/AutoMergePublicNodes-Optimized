# AutoNodes 每日报告

生成时间：2026-09-26 16:15:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96750 |
| 去重后节点数 | 26317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 367 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 80.2 |
| geo | 1.5 |
| probe | 196.4 |
| real_test | 165.7 |
| tcp | 43.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 20 | 7 | 13 | 35.0% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 158 | 134 | 24 | 84.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 5 | 5 | 0 | 100.0% |
| vless | 267 | 199 | 68 | 74.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 24 |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 17 |
| 204:ProxyError | 16 |
| speed:TimeoutError | 9 |
| 204:ProxyConnectionError | 5 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6013 |
| ConnectionRefusedError | 953 |
| gaierror | 355 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | prefer | 276 | 0.87 | 1642 |
| Surfboard-tg-mixed | 0.816 | prefer | 70 | 0.743 | 7263 |
| mheidari-all | 0.722 | prefer | 104 | 0.644 | 22551 |
| ermaozi | 0.339 | observe | 18 | 0.333 | 296 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5242 |
| Epodonios-all | 0.255 | observe | 0 | None | 7742 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8947 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5823 |

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
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi | 0.333 | 6 | 12 | 18 |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.644 | 67 | 37 | 104 |
| Surfboard-tg-mixed | 0.743 | 52 | 18 | 70 |
| Au1rxx-base64 | 0.87 | 240 | 36 | 276 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22551 | yes | 6.25 | 0 |
| SoliSpirit-all | 8947 | yes | 4.2 | 0 |
| Epodonios-all | 7742 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 7263 | yes | 3.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.59 | 0 |
| barry-far-vless | 6056 | yes | 2.53 | 0 |
| Surfboard-tg-vless | 5823 | yes | 5.58 | 0 |
| DeltaKronecker-all | 5512 | yes | 6.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 3.57 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 0.19 | 0 |

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
| cn-block | 50 |
| 204 | 39 |
| speed | 13 |
| geo | 6 |
