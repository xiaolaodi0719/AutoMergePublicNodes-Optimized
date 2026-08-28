# AutoNodes 每日报告

生成时间：2026-08-28 22:05:22

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77028 |
| 去重后节点数 | 20891 |
| TCP 可达数 | 3000 |
| 真测通过数 | 631 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 20891 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 47.4 |
| geo | 1.4 |
| probe | 57.1 |
| real_test | 126.2 |
| tcp | 34.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 25 | 24 | 1 | 96.0% |
| shadowsocks | 180 | 166 | 14 | 92.2% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 21 | 21 | 0 | 100.0% |
| vless | 477 | 389 | 88 | 81.6% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 27 |
| geo:ClientOSError | 16 |
| 204:TimeoutError | 13 |
| geo:TimeoutError | 8 |
| speed:TimeoutError | 8 |
| cn-block:ProxyError | 7 |
| speed:ClientOSError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49910: bind: address already in use | 1 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4723 |
| ConnectionRefusedError | 881 |
| gaierror | 395 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 344 | 0.945 | 1776 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| mheidari-all | 0.95 | prefer | 75 | 0.88 | 14493 |
| DeltaKronecker-all | 0.839 | prefer | 110 | 0.764 | 4065 |
| Surfboard-tg-mixed | 0.803 | prefer | 175 | 0.726 | 6713 |
| tg-oneclickvpnkeys | 0.445 | observe | 5 | 1.0 | 140 |
| nscl5-all | 0.279 | observe | 1 | 1.0 | 594 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4725 |
| Epodonios-all | 0.255 | observe | 0 | None | 6861 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| roosterkid-openproxylist-v2ray | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.726 | 127 | 48 | 175 |
| DeltaKronecker-all | 0.764 | 84 | 26 | 110 |
| mheidari-all | 0.88 | 66 | 9 | 75 |
| Au1rxx-base64 | 0.945 | 325 | 19 | 344 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14493 | yes | 4.61 | 0 |
| SoliSpirit-all | 7878 | yes | 4.54 | 0 |
| Epodonios-all | 6861 | yes | 3.49 | 0 |
| Surfboard-tg-mixed | 6713 | yes | 4.2 | 0 |
| Surfboard-tg-vless | 5540 | yes | 3.99 | 0 |
| barry-far-vless | 5468 | yes | 2.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4725 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 4081 | yes | 1.66 | 0 |
| DeltaKronecker-all | 4065 | yes | 4.63 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.55 | 0 |

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
| cn-block | 41 |
| geo | 25 |
| 204 | 21 |
| speed | 16 |
| sing-box exited 1 | 1 |
