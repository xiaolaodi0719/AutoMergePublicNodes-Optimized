# AutoNodes 每日报告

生成时间：2026-10-01 05:23:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97843 |
| 去重后节点数 | 27292 |
| TCP 可达数 | 3000 |
| 真测通过数 | 336 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27292 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 81.2 |
| geo | 1.6 |
| probe | 296.0 |
| real_test | 381.5 |
| tcp | 45.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 21 | 2 | 91.3% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 166 | 149 | 17 | 89.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 46 | 32 | 14 | 69.6% |
| vless | 412 | 111 | 301 | 26.9% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 158 |
| speed:TimeoutError | 68 |
| geo:ClientOSError | 41 |
| speed:ClientOSError | 23 |
| 204:ProxyError | 18 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 9 |
| 204:ClientOSError | 4 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6341 |
| ConnectionRefusedError | 1005 |
| gaierror | 385 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | prefer | 114 | 0.921 | 1694 |
| ermaozi | 0.857 | prefer | 22 | 0.864 | 588 |
| Surfboard-tg-mixed | 0.714 | prefer | 80 | 0.637 | 7136 |
| mheidari-all | 0.427 | observe | 442 | 0.346 | 22835 |
| DeltaKronecker-all | 0.397 | observe | 12 | 0.417 | 5434 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 66 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7637 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.346 | 153 | 289 | 442 |
| DeltaKronecker-all | 0.417 | 5 | 7 | 12 |
| Surfboard-tg-mixed | 0.637 | 51 | 29 | 80 |
| ermaozi | 0.864 | 19 | 3 | 22 |
| Au1rxx-base64 | 0.921 | 105 | 9 | 114 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22835 | yes | 6.46 | 0 |
| SoliSpirit-all | 9403 | yes | 4.8 | 0 |
| Epodonios-all | 7637 | yes | 3.7 | 0 |
| Surfboard-tg-mixed | 7136 | yes | 5.44 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 4.16 | 0 |
| barry-far-vless | 6001 | yes | 3.23 | 0 |
| Surfboard-tg-vless | 5815 | yes | 4.51 | 0 |
| DeltaKronecker-all | 5434 | yes | 6.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 2.98 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 0.2 | 0 |

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
| geo | 200 |
| speed | 92 |
| 204 | 36 |
| cn-block | 11 |
