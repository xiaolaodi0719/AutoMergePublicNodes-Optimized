# AutoNodes 每日报告

生成时间：2026-08-18 13:01:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91953 |
| 去重后节点数 | 24182 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1241 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24182 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| generate | 26.1 |
| geo | 1.4 |
| probe | 75.1 |
| real_test | 234.3 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 153 | 139 | 14 | 90.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 741 | 726 | 15 | 98.0% |
| tuic | 1 | 0 | 1 | 0.0% |
| vless | 313 | 227 | 86 | 72.5% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 27 |
| 204:TimeoutError | 17 |
| geo:TimeoutError | 17 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 10 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:31282: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5166 |
| ConnectionRefusedError | 952 |
| OSError | 227 |
| gaierror | 174 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 365 | 0.959 | 21086 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Au1rxx-base64 | 0.975 | prefer | 698 | 0.905 | 1759 |
| Surfboard-tg-mixed | 0.87 | prefer | 160 | 0.794 | 6253 |
| DeltaKronecker-all | 0.372 | observe | 9 | 0.444 | 5725 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 2992 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6795 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3984 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6898 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.444 | 4 | 5 | 9 |
| Surfboard-tg-mixed | 0.794 | 127 | 33 | 160 |
| Au1rxx-base64 | 0.905 | 632 | 66 | 698 |
| mheidari-all | 0.959 | 350 | 15 | 365 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21086 | yes | 4.51 | 0 |
| SoliSpirit-all | 6898 | yes | 4.48 | 0 |
| Epodonios-all | 6795 | yes | 3.94 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.33 | 0 |
| Surfboard-tg-mixed | 6253 | yes | 3.21 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.89 | 0 |
| barry-far-vless | 5206 | yes | 0.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 4907 | yes | 4.68 | 0 |
| mahdibland-V2RayAggregator | 4045 | yes | 2.57 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| tuic | 0.0 |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 38 |
| 204 | 33 |
| geo | 28 |
| speed | 20 |
| sing-box exited 1 | 1 |
