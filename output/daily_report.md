# AutoNodes 每日报告

生成时间：2026-09-24 21:30:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98134 |
| 去重后节点数 | 26548 |
| TCP 可达数 | 3000 |
| 真测通过数 | 374 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26548 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 81.3 |
| geo | 1.5 |
| probe | 255.5 |
| real_test | 155.0 |
| tcp | 43.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 15 | 5 | 10 | 33.3% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 171 | 148 | 23 | 86.5% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 18 | 14 | 4 | 77.8% |
| vless | 223 | 188 | 35 | 84.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 16 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 8 |
| cn-block:ClientOSError | 8 |
| geo:TimeoutError | 7 |
| geo:ClientOSError | 3 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41485: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6012 |
| ConnectionRefusedError | 982 |
| gaierror | 345 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.994 | prefer | 253 | 0.933 | 1626 |
| mheidari-all | 0.846 | prefer | 75 | 0.773 | 22744 |
| Surfboard-tg-mixed | 0.788 | prefer | 104 | 0.712 | 7419 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4405 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 304 |
| ermaozi | 0.263 | observe | 14 | 0.286 | 298 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5307 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9086 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.286 | 4 | 10 | 14 |
| Surfboard-tg-mixed | 0.712 | 74 | 30 | 104 |
| mheidari-all | 0.773 | 58 | 17 | 75 |
| Au1rxx-base64 | 0.933 | 236 | 17 | 253 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22744 | yes | 5.94 | 0 |
| SoliSpirit-all | 9086 | yes | 2.33 | 0 |
| Epodonios-all | 7888 | yes | 2.93 | 0 |
| Surfboard-tg-mixed | 7419 | yes | 3.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.06 | 0 |
| barry-far-vless | 6215 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5963 | yes | 3.52 | 0 |
| DeltaKronecker-all | 5845 | yes | 4.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4405 | yes | 2.67 | 0 |

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
| 204 | 45 |
| cn-block | 17 |
| geo | 11 |
| speed | 4 |
| sing-box exited 1 | 1 |
