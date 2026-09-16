# AutoNodes 每日报告

生成时间：2026-09-16 16:43:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 89597 |
| 去重后节点数 | 24457 |
| TCP 可达数 | 3000 |
| 真测通过数 | 417 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24457 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.4 |
| generate | 75.0 |
| geo | 1.5 |
| probe | 289.9 |
| real_test | 249.5 |
| tcp | 42.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 30 | 25 | 5 | 83.3% |
| hysteria2 | 21 | 19 | 2 | 90.5% |
| shadowsocks | 153 | 136 | 17 | 88.9% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 6 | 5 | 1 | 83.3% |
| vless | 346 | 229 | 117 | 66.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 27 |
| geo:TimeoutError | 25 |
| 204:TimeoutError | 24 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6010 |
| ConnectionRefusedError | 924 |
| gaierror | 374 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.875 | prefer | 268 | 0.81 | 1698 |
| mheidari-all | 0.866 | prefer | 82 | 0.793 | 17973 |
| ermaozi | 0.842 | prefer | 27 | 0.852 | 353 |
| DeltaKronecker-all | 0.702 | prefer | 109 | 0.624 | 6081 |
| Surfboard-tg-mixed | 0.669 | observe | 71 | 0.592 | 7470 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4206 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 207 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5115 |
| Epodonios-all | 0.255 | observe | 0 | None | 7938 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| ermaozi-get_subscribe | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.592 | 42 | 29 | 71 |
| DeltaKronecker-all | 0.624 | 68 | 41 | 109 |
| mheidari-all | 0.793 | 65 | 17 | 82 |
| Au1rxx-base64 | 0.81 | 217 | 51 | 268 |
| ermaozi | 0.852 | 23 | 4 | 27 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17973 | yes | 5.77 | 0 |
| SoliSpirit-all | 9093 | yes | 3.06 | 0 |
| Epodonios-all | 7938 | yes | 3.24 | 0 |
| Surfboard-tg-mixed | 7470 | yes | 6.1 | 0 |
| barry-far-vless | 6195 | yes | 0.9 | 0 |
| DeltaKronecker-all | 6081 | yes | 5.97 | 0 |
| Surfboard-tg-vless | 5979 | yes | 4.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 5115 | yes | 1.79 | 0 |
| mahdibland-V2RayAggregator | 4206 | yes | 2.38 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.26 | 0 |

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
| geo | 52 |
| 204 | 40 |
| cn-block | 30 |
| speed | 23 |
