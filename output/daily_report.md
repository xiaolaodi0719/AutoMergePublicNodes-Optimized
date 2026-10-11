# AutoNodes 每日报告

生成时间：2026-10-11 21:54:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 2/104 |
| 原始节点数 | 99284 |
| 去重后节点数 | 27441 |
| TCP 可达数 | 3000 |
| 真测通过数 | 478 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27441 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| generate | 77.4 |
| geo | 1.5 |
| probe | 294.4 |
| real_test | 304.2 |
| tcp | 46.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 1 | 6 | 14.3% |
| http | 40 | 24 | 16 | 60.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 132 | 124 | 8 | 93.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 121 | 119 | 2 | 98.3% |
| vless | 233 | 191 | 42 | 82.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 8 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| geo:ClientOSError | 6 |
| 204:ProxyConnectionError | 5 |
| cn-block:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| speed:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40536: bind: address already in use | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6215 |
| ConnectionRefusedError | 1036 |
| gaierror | 453 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.992 | prefer | 374 | 0.92 | 1858 |
| mheidari-all | 0.915 | prefer | 119 | 0.84 | 23882 |
| ermaozi | 0.611 | observe | 39 | 0.59 | 635 |
| Surfboard-tg-mixed | 0.474 | observe | 10 | 0.6 | 7031 |
| DeltaKronecker-all | 0.391 | observe | 2 | 1.0 | 5372 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 104 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5099 |
| Epodonios-all | 0.255 | observe | 0 | None | 7711 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.149 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.143 | 1 | 6 | 7 |
| ermaozi | 0.59 | 23 | 16 | 39 |
| Surfboard-tg-mixed | 0.6 | 6 | 4 | 10 |
| mheidari-all | 0.84 | 100 | 19 | 119 |
| Au1rxx-base64 | 0.92 | 344 | 30 | 374 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| DeltaKronecker-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23882 | yes | 6.7 | 0 |
| SoliSpirit-all | 9704 | yes | 2.36 | 0 |
| Epodonios-all | 7711 | yes | 7.0 | 0 |
| Surfboard-tg-mixed | 7031 | yes | 4.45 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.05 | 0 |
| barry-far-vless | 5966 | yes | 1.36 | 0 |
| Surfboard-tg-vless | 5590 | yes | 4.64 | 0 |
| DeltaKronecker-all | 5372 | yes | 6.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4284 | yes | 3.7 | 0 |

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
| 204 | 35 |
| cn-block | 25 |
| speed | 9 |
| geo | 7 |
| sing-box exited 1 | 1 |
