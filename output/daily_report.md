# AutoNodes 每日报告

生成时间：2026-09-14 12:29:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84799 |
| 去重后节点数 | 23007 |
| TCP 可达数 | 3000 |
| 真测通过数 | 451 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23007 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 77.6 |
| geo | 1.4 |
| probe | 249.0 |
| real_test | 219.9 |
| tcp | 37.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 66 | 37 | 29 | 56.1% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 157 | 152 | 5 | 96.8% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 15 | 13 | 2 | 86.7% |
| vless | 309 | 229 | 80 | 74.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 24 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 18 |
| speed:ClientOSError | 15 |
| 204:ProxyConnectionError | 9 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5043 |
| ConnectionRefusedError | 881 |
| gaierror | 464 |
| OSError | 14 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.943 | prefer | 298 | 0.879 | 1668 |
| DeltaKronecker-all | 0.872 | prefer | 22 | 0.818 | 5972 |
| mheidari-all | 0.848 | prefer | 54 | 0.778 | 15903 |
| Surfboard-tg-mixed | 0.786 | prefer | 117 | 0.709 | 7478 |
| ermaozi | 0.632 | observe | 50 | 0.62 | 417 |
| roosterkid-openproxylist-v2ray | 0.532 | observe | 9 | 0.889 | 150 |
| ermaozi-get_subscribe | 0.356 | observe | 16 | 0.375 | 444 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7910 |

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
| ermaozi-get_subscribe | 0.375 | 6 | 10 | 16 |
| ermaozi | 0.62 | 31 | 19 | 50 |
| Surfboard-tg-mixed | 0.709 | 83 | 34 | 117 |
| mheidari-all | 0.778 | 42 | 12 | 54 |
| DeltaKronecker-all | 0.818 | 18 | 4 | 22 |
| Au1rxx-base64 | 0.879 | 262 | 36 | 298 |
| roosterkid-openproxylist-v2ray | 0.889 | 8 | 1 | 9 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15903 | yes | 4.88 | 0 |
| SoliSpirit-all | 9127 | yes | 3.99 | 0 |
| Epodonios-all | 7910 | yes | 5.31 | 0 |
| Surfboard-tg-mixed | 7478 | yes | 3.53 | 0 |
| barry-far-vless | 6310 | yes | 0.5 | 0 |
| Surfboard-tg-vless | 6074 | yes | 3.97 | 0 |
| DeltaKronecker-all | 5972 | yes | 4.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 0.93 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 2.85 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.99 | 0 |

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
| 204 | 43 |
| geo | 27 |
| cn-block | 26 |
| speed | 21 |
