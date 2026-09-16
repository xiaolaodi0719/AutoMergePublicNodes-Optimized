# AutoNodes 每日报告

生成时间：2026-09-16 21:15:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 89335 |
| 去重后节点数 | 24603 |
| TCP 可达数 | 3000 |
| 真测通过数 | 396 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24603 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| generate | 80.4 |
| geo | 1.5 |
| probe | 244.5 |
| real_test | 191.9 |
| tcp | 41.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 28 | 6 | 82.4% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 155 | 141 | 14 | 91.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 20 | 16 | 4 | 80.0% |
| vless | 238 | 186 | 52 | 78.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| geo:ClientOSError | 15 |
| speed:ClientOSError | 11 |
| 204:TimeoutError | 10 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| geo:TimeoutError | 4 |
| speed:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5728 |
| ConnectionRefusedError | 930 |
| gaierror | 432 |
| OSError | 236 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.929 | prefer | 268 | 0.866 | 1651 |
| mheidari-all | 0.867 | prefer | 78 | 0.795 | 17985 |
| Surfboard-tg-mixed | 0.867 | prefer | 59 | 0.797 | 7483 |
| ermaozi | 0.847 | prefer | 28 | 0.857 | 353 |
| DeltaKronecker-all | 0.823 | prefer | 33 | 0.758 | 6081 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 140 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4234 |
| Pawdroid | 0.256 | observe | 1 | 1.0 | 20 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 7934 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.25 | 1 | 3 | 4 |
| DeltaKronecker-all | 0.758 | 25 | 8 | 33 |
| mheidari-all | 0.795 | 62 | 16 | 78 |
| Surfboard-tg-mixed | 0.797 | 47 | 12 | 59 |
| ermaozi | 0.857 | 24 | 4 | 28 |
| Au1rxx-base64 | 0.866 | 232 | 36 | 268 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Pawdroid | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17985 | yes | 4.87 | 0 |
| SoliSpirit-all | 8999 | yes | 3.79 | 0 |
| Epodonios-all | 7934 | yes | 2.26 | 0 |
| Surfboard-tg-mixed | 7483 | yes | 3.48 | 0 |
| barry-far-vless | 6197 | yes | 1.58 | 0 |
| DeltaKronecker-all | 6081 | yes | 4.97 | 0 |
| Surfboard-tg-vless | 5919 | yes | 2.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 4234 | yes | 2.31 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.42 | 0 |

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
| cn-block | 25 |
| 204 | 22 |
| geo | 19 |
| speed | 15 |
