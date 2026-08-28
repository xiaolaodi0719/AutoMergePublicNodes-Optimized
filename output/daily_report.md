# AutoNodes 每日报告

生成时间：2026-08-28 10:49:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 76338 |
| 去重后节点数 | 21065 |
| TCP 可达数 | 3000 |
| 真测通过数 | 474 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21065 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 40.9 |
| geo | 1.4 |
| probe | 58.1 |
| real_test | 111.7 |
| tcp | 35.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 163 | 146 | 17 | 89.6% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 17 | 12 | 5 | 70.6% |
| vless | 385 | 265 | 120 | 68.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| geo:ClientOSError | 27 |
| cn-block:TimeoutError | 24 |
| geo:TimeoutError | 16 |
| speed:TimeoutError | 16 |
| 204:ProxyError | 14 |
| 204:ClientOSError | 6 |
| speed:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:44728: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4754 |
| ConnectionRefusedError | 878 |
| gaierror | 391 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| Au1rxx-base64 | 0.958 | prefer | 310 | 0.887 | 1823 |
| mheidari-all | 0.804 | prefer | 56 | 0.732 | 14456 |
| Surfboard-tg-mixed | 0.782 | prefer | 102 | 0.706 | 6512 |
| DeltaKronecker-all | 0.564 | observe | 122 | 0.484 | 4318 |
| tg-oneclickvpnkeys | 0.362 | observe | 3 | 1.0 | 101 |
| nscl5-all | 0.279 | observe | 1 | 1.0 | 594 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4783 |
| Epodonios-all | 0.255 | observe | 0 | None | 6791 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |

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
| DeltaKronecker-all | 0.484 | 59 | 63 | 122 |
| Surfboard-tg-mixed | 0.706 | 72 | 30 | 102 |
| mheidari-all | 0.732 | 41 | 15 | 56 |
| Au1rxx-base64 | 0.887 | 275 | 35 | 310 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14456 | yes | 3.07 | 0 |
| SoliSpirit-all | 7458 | yes | 2.41 | 0 |
| Epodonios-all | 6791 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 6512 | yes | 2.32 | 0 |
| barry-far-vless | 5416 | yes | 0.64 | 0 |
| Surfboard-tg-vless | 5314 | yes | 2.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4783 | yes | 0.82 | 0 |
| DeltaKronecker-all | 4318 | yes | 3.32 | 0 |
| mahdibland-V2RayAggregator | 4061 | yes | 2.05 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 0.87 | 0 |

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
| 204 | 48 |
| geo | 45 |
| cn-block | 29 |
| speed | 21 |
| sing-box exited 1 | 1 |
