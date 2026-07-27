# AutoNodes 每日报告

生成时间：2026-07-27 14:52:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 85526 |
| 去重后节点数 | 22983 |
| TCP 可达数 | 3000 |
| 真测通过数 | 795 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22983 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 27.6 |
| geo | 1.6 |
| probe | 68.1 |
| real_test | 189.9 |
| tcp | 32.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 4 | 2 | 66.7% |
| http | 59 | 59 | 0 | 100.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 122 | 108 | 14 | 88.5% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 454 | 412 | 42 | 90.7% |
| vless | 431 | 198 | 233 | 45.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 112 |
| speed:ClientOSError | 75 |
| geo:ClientOSError | 27 |
| cn-block:TimeoutError | 18 |
| speed:TimeoutError | 14 |
| 204:ProxyError | 13 |
| cn-block:ProxyError | 10 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 5 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46187: bind: address already in use | 1 |
| speed:ClientPayloadError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4563 |
| ConnectionRefusedError | 711 |
| gaierror | 229 |
| OSError | 223 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.997 | prefer | 390 | 0.938 | 1507 |
| zhangkai | 0.987 | prefer | 59 | 1.0 | 74 |
| DeltaKronecker-all | 0.744 | prefer | 129 | 0.667 | 5643 |
| Surfboard-tg-mixed | 0.728 | prefer | 52 | 0.654 | 5641 |
| mheidari-all | 0.624 | observe | 448 | 0.545 | 19227 |
| tg-oneclickvpnkeys | 0.346 | observe | 6 | 0.667 | 131 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4831 |
| Epodonios-all | 0.255 | observe | 0 | None | 6520 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.545 | 244 | 204 | 448 |
| Surfboard-tg-mixed | 0.654 | 34 | 18 | 52 |
| tg-oneclickvpnkeys | 0.667 | 4 | 2 | 6 |
| DeltaKronecker-all | 0.667 | 86 | 43 | 129 |
| Au1rxx-base64 | 0.938 | 366 | 24 | 390 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 59 | 0 | 59 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19227 | yes | 2.83 | 0 |
| SoliSpirit-all | 6628 | yes | 2.21 | 0 |
| Epodonios-all | 6520 | yes | 1.57 | 0 |
| DeltaKronecker-all | 5643 | yes | 3.26 | 0 |
| Surfboard-tg-mixed | 5641 | yes | 2.43 | 0 |
| mahdibland-V2RayAggregator | 5017 | yes | 1.8 | 0 |
| barry-far-vless | 4866 | yes | 0.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4831 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 4484 | yes | 1.47 | 0 |
| MatinGhanbari-all-sub | 3970 | yes | 1.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 141 |
| speed | 91 |
| cn-block | 33 |
| 204 | 28 |
| sing-box exited 1 | 1 |
