# AutoNodes 每日报告

生成时间：2026-08-19 06:59:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82903 |
| 去重后节点数 | 22465 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1411 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22465 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 34.7 |
| geo | 0.8 |
| probe | 81.9 |
| real_test | 256.5 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 20 | 16 | 4 | 80.0% |
| shadowsocks | 167 | 153 | 14 | 91.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 947 | 931 | 16 | 98.3% |
| vless | 270 | 182 | 88 | 67.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 30 |
| speed:TimeoutError | 28 |
| geo:ClientOSError | 15 |
| cn-block:TimeoutError | 15 |
| 204:TimeoutError | 14 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:34673: bind: address already in use | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4298 |
| ConnectionRefusedError | 860 |
| gaierror | 393 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 803 | 0.989 | 1924 |
| mheidari-all | 1.0 | prefer | 257 | 0.926 | 16809 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.87 | prefer | 307 | 0.792 | 6315 |
| nscl5-all | 0.373 | observe | 5 | 0.6 | 3330 |
| DeltaKronecker-all | 0.299 | observe | 30 | 0.2 | 6390 |
| Epodonios-all | 0.255 | observe | 0 | None | 7030 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7119 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4850 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.2 | 6 | 24 | 30 |
| nscl5-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.792 | 243 | 64 | 307 |
| mheidari-all | 0.926 | 238 | 19 | 257 |
| Au1rxx-base64 | 0.989 | 794 | 9 | 803 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16809 | yes | 4.44 | 0 |
| SoliSpirit-all | 7119 | yes | 4.34 | 0 |
| Epodonios-all | 7030 | yes | 4.64 | 0 |
| DeltaKronecker-all | 6390 | yes | 4.63 | 0 |
| Surfboard-tg-mixed | 6315 | yes | 3.1 | 0 |
| barry-far-vless | 5173 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 3.03 | 0 |
| Surfboard-tg-vless | 4850 | yes | 4.04 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 3.13 | 0 |
| mahdibland-V2RayAggregator | 3995 | yes | 0.73 | 0 |

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
| geo | 45 |
| speed | 34 |
| 204 | 25 |
| cn-block | 18 |
| sing-box exited 1 | 1 |
