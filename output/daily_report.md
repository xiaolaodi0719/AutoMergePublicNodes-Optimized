# AutoNodes 每日报告

生成时间：2026-08-14 02:26:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79423 |
| 去重后节点数 | 21337 |
| TCP 可达数 | 3000 |
| 真测通过数 | 993 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21337 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 28.1 |
| geo | 1.3 |
| probe | 61.4 |
| real_test | 209.5 |
| tcp | 33.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 163 | 157 | 6 | 96.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 413 | 404 | 9 | 97.8% |
| vless | 448 | 286 | 162 | 63.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 49 |
| speed:TimeoutError | 42 |
| cn-block:TimeoutError | 27 |
| geo:ClientOSError | 17 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 13 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4321 |
| ConnectionRefusedError | 773 |
| gaierror | 247 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 712 | 0.945 | 1965 |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.92 | prefer | 104 | 0.846 | 5918 |
| DeltaKronecker-all | 0.863 | prefer | 44 | 0.795 | 3656 |
| mheidari-all | 0.464 | observe | 170 | 0.382 | 16929 |
| 10ium-ScrapeCategorize-Vless | 0.352 | observe | 6 | 0.5 | 5203 |
| nscl5-all | 0.278 | observe | 2 | 0.5 | 1768 |
| Epodonios-all | 0.255 | observe | 0 | None | 6600 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7655 |

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
| ninja-vless | 0.152 | observe | 4 | 0.0 | 0 | 1791 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 4 | 4 |
| mheidari-all | 0.382 | 65 | 105 | 170 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.5 | 3 | 3 | 6 |
| DeltaKronecker-all | 0.795 | 35 | 9 | 44 |
| Surfboard-tg-mixed | 0.846 | 88 | 16 | 104 |
| Au1rxx-base64 | 0.945 | 673 | 39 | 712 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16929 | yes | 4.47 | 0 |
| SoliSpirit-all | 7655 | yes | 4.29 | 0 |
| Epodonios-all | 6600 | yes | 4.67 | 0 |
| Surfboard-tg-mixed | 5918 | yes | 5.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 2.99 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 3.04 | 0 |
| barry-far-vless | 5003 | yes | 2.63 | 0 |
| Surfboard-tg-vless | 4638 | yes | 3.48 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.77 | 0 |
| DeltaKronecker-all | 3656 | yes | 5.0 | 0 |

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
| geo | 67 |
| speed | 55 |
| cn-block | 35 |
| 204 | 21 |
