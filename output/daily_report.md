# AutoNodes 每日报告

生成时间：2026-09-12 10:34:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83079 |
| 去重后节点数 | 22882 |
| TCP 可达数 | 3000 |
| 真测通过数 | 415 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22882 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 88.1 |
| geo | 1.5 |
| probe | 195.3 |
| real_test | 239.6 |
| tcp | 38.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 42 | 26 | 61.8% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 153 | 143 | 10 | 93.5% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 47 | 31 | 16 | 66.0% |
| vless | 260 | 178 | 82 | 68.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 29 |
| 204:ProxyError | 27 |
| 204:TimeoutError | 18 |
| speed:ClientOSError | 15 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| cn-block:TimeoutError | 10 |
| 204:ClientOSError | 4 |
| 204:ProxyConnectionError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4894 |
| ConnectionRefusedError | 885 |
| gaierror | 445 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.927 | prefer | 282 | 0.865 | 1613 |
| mheidari-all | 0.78 | prefer | 68 | 0.706 | 15628 |
| ermaozi | 0.703 | prefer | 52 | 0.692 | 434 |
| Surfboard-tg-mixed | 0.694 | observe | 81 | 0.617 | 7286 |
| DeltaKronecker-all | 0.688 | observe | 49 | 0.612 | 5970 |
| ermaozi-get_subscribe | 0.357 | observe | 16 | 0.375 | 459 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 181 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4793 |
| Epodonios-all | 0.255 | observe | 0 | None | 7695 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| Pawdroid | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.375 | 6 | 10 | 16 |
| DeltaKronecker-all | 0.612 | 30 | 19 | 49 |
| Surfboard-tg-mixed | 0.617 | 50 | 31 | 81 |
| ermaozi | 0.692 | 36 | 16 | 52 |
| mheidari-all | 0.706 | 48 | 20 | 68 |
| Au1rxx-base64 | 0.865 | 244 | 38 | 282 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15628 | yes | 4.99 | 0 |
| SoliSpirit-all | 8697 | yes | 4.81 | 0 |
| Epodonios-all | 7695 | yes | 0.28 | 0 |
| Surfboard-tg-mixed | 7286 | yes | 3.63 | 0 |
| barry-far-vless | 6084 | yes | 0.7 | 0 |
| DeltaKronecker-all | 5970 | yes | 5.62 | 0 |
| Surfboard-tg-vless | 5895 | yes | 4.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4793 | yes | 3.95 | 0 |
| mahdibland-V2RayAggregator | 4207 | yes | 3.39 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.24 | 0 |

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
| 204 | 50 |
| geo | 40 |
| speed | 27 |
| cn-block | 21 |
