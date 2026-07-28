# AutoNodes 每日报告

生成时间：2026-07-28 14:26:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82917 |
| 去重后节点数 | 23077 |
| TCP 可达数 | 3000 |
| 真测通过数 | 507 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23077 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 31.7 |
| generate | 37.2 |
| geo | 1.4 |
| probe | 57.2 |
| real_test | 136.1 |
| tcp | 31.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 69 | 69 | 0 | 100.0% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 166 | 143 | 23 | 86.1% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 183 | 159 | 24 | 86.9% |
| vless | 226 | 123 | 103 | 54.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 36 |
| 204:TimeoutError | 28 |
| 204:ProxyError | 24 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 13 |
| speed:TimeoutError | 13 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| speed:ClientOSError | 3 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4254 |
| ConnectionRefusedError | 745 |
| gaierror | 303 |
| OSError | 222 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.989 | prefer | 69 | 1.0 | 81 |
| Au1rxx-base64 | 0.931 | prefer | 198 | 0.879 | 1391 |
| DeltaKronecker-all | 0.917 | prefer | 127 | 0.843 | 5965 |
| mheidari-all | 0.764 | prefer | 77 | 0.688 | 18775 |
| Surfboard-tg-mixed | 0.639 | observe | 184 | 0.56 | 5928 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4972 |
| Epodonios-all | 0.255 | observe | 0 | None | 6785 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6846 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4700 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.56 | 103 | 81 | 184 |
| mheidari-all | 0.688 | 53 | 24 | 77 |
| DeltaKronecker-all | 0.843 | 107 | 20 | 127 |
| Au1rxx-base64 | 0.879 | 174 | 24 | 198 |
| zhangkai | 1.0 | 69 | 0 | 69 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18775 | yes | 4.01 | 0 |
| SoliSpirit-all | 6846 | yes | 2.65 | 0 |
| Epodonios-all | 6785 | yes | 4.21 | 0 |
| DeltaKronecker-all | 5965 | yes | 4.08 | 0 |
| Surfboard-tg-mixed | 5928 | yes | 2.76 | 0 |
| barry-far-vless | 5220 | yes | 1.56 | 0 |
| mahdibland-V2RayAggregator | 4991 | yes | 2.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 4972 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 4700 | yes | 2.92 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 1.65 | 0 |

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
| 204 | 57 |
| geo | 51 |
| cn-block | 26 |
| speed | 18 |
