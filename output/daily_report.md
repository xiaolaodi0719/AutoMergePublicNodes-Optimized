# AutoNodes 每日报告

生成时间：2026-09-04 03:57:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82420 |
| 去重后节点数 | 22770 |
| TCP 可达数 | 3000 |
| 真测通过数 | 749 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22770 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 39.4 |
| geo | 1.5 |
| probe | 77.5 |
| real_test | 175.0 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 181 | 172 | 9 | 95.0% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 44 | 40 | 4 | 90.9% |
| vless | 747 | 486 | 261 | 65.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 98 |
| geo:ClientOSError | 42 |
| speed:TimeoutError | 40 |
| speed:ClientOSError | 27 |
| cn-block:TimeoutError | 23 |
| 204:TimeoutError | 14 |
| cn-block:ClientOSError | 13 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42549: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5355 |
| ConnectionRefusedError | 909 |
| gaierror | 248 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.995 | prefer | 384 | 0.927 | 1753 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.855 | prefer | 211 | 0.777 | 7237 |
| mheidari-all | 0.691 | observe | 191 | 0.613 | 15793 |
| DeltaKronecker-all | 0.488 | observe | 211 | 0.408 | 6335 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 71 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4671 |
| Epodonios-all | 0.255 | observe | 0 | None | 7701 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7955 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.408 | 86 | 125 | 211 |
| mheidari-all | 0.613 | 117 | 74 | 191 |
| Surfboard-tg-mixed | 0.777 | 164 | 47 | 211 |
| Au1rxx-base64 | 0.927 | 356 | 28 | 384 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15793 | yes | 3.54 | 0 |
| SoliSpirit-all | 7955 | yes | 2.8 | 0 |
| Epodonios-all | 7701 | yes | 2.28 | 0 |
| Surfboard-tg-mixed | 7237 | yes | 2.95 | 0 |
| DeltaKronecker-all | 6335 | yes | 3.48 | 0 |
| barry-far-vless | 6237 | yes | 2.12 | 0 |
| Surfboard-tg-vless | 6022 | yes | 2.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 4671 | yes | 2.08 | 0 |
| mahdibland-V2RayAggregator | 4133 | yes | 1.97 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.62 | 0 |

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
| geo | 140 |
| speed | 67 |
| cn-block | 41 |
| 204 | 27 |
| sing-box exited 1 | 1 |
