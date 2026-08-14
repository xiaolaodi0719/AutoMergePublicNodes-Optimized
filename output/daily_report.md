# AutoNodes 每日报告

生成时间：2026-08-14 07:44:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81257 |
| 去重后节点数 | 23189 |
| TCP 可达数 | 3000 |
| 真测通过数 | 862 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23189 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 34.4 |
| geo | 1.4 |
| probe | 65.9 |
| real_test | 168.4 |
| tcp | 35.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 15 | 15 | 0 | 100.0% |
| shadowsocks | 182 | 169 | 13 | 92.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 364 | 350 | 14 | 96.2% |
| vless | 328 | 197 | 131 | 60.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 61 |
| geo:ClientOSError | 29 |
| speed:ClientOSError | 19 |
| speed:TimeoutError | 14 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 10 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4818 |
| ConnectionRefusedError | 764 |
| gaierror | 170 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 666 | 0.935 | 1671 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.695 | observe | 102 | 0.618 | 5896 |
| mheidari-all | 0.523 | observe | 15 | 0.533 | 16991 |
| DeltaKronecker-all | 0.456 | observe | 107 | 0.374 | 5969 |
| nscl5-all | 0.326 | observe | 1 | 1.0 | 1768 |
| Epodonios-all | 0.255 | observe | 0 | None | 6568 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7698 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4633 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.374 | 40 | 67 | 107 |
| mheidari-all | 0.533 | 8 | 7 | 15 |
| Surfboard-tg-mixed | 0.618 | 63 | 39 | 102 |
| Au1rxx-base64 | 0.935 | 623 | 43 | 666 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16991 | yes | 3.84 | 0 |
| SoliSpirit-all | 7698 | yes | 3.1 | 0 |
| Epodonios-all | 6568 | yes | 4.45 | 0 |
| DeltaKronecker-all | 5969 | yes | 4.6 | 0 |
| Surfboard-tg-mixed | 5896 | yes | 2.69 | 0 |
| mahdibland-V2RayAggregator | 5332 | yes | 2.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 5157 | yes | 2.17 | 0 |
| barry-far-vless | 4969 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 4633 | yes | 3.37 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.24 | 0 |

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
| geo | 91 |
| speed | 33 |
| 204 | 21 |
| cn-block | 14 |
