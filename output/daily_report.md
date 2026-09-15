# AutoNodes 每日报告

生成时间：2026-09-15 11:38:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 90261 |
| 去重后节点数 | 25576 |
| TCP 可达数 | 3000 |
| 真测通过数 | 434 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25576 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 79.9 |
| geo | 1.4 |
| probe | 349.3 |
| real_test | 238.3 |
| tcp | 41.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 53 | 33 | 20 | 62.3% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 154 | 142 | 12 | 92.2% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 8 | 4 | 4 | 50.0% |
| vless | 334 | 235 | 99 | 70.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| geo:ClientOSError | 24 |
| cn-block:TimeoutError | 20 |
| 204:ProxyError | 19 |
| cn-block:ClientOSError | 16 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 10 |
| geo:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5520 |
| ConnectionRefusedError | 964 |
| gaierror | 439 |
| OSError | 238 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | prefer | 320 | 0.869 | 1440 |
| mheidari-all | 0.742 | prefer | 75 | 0.667 | 21594 |
| Surfboard-tg-mixed | 0.696 | observe | 110 | 0.618 | 7608 |
| ermaozi | 0.647 | observe | 52 | 0.635 | 425 |
| DeltaKronecker-all | 0.382 | observe | 14 | 0.357 | 5932 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| Epodonios-all | 0.255 | observe | 0 | None | 8009 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8760 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6177 |

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
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.357 | 5 | 9 | 14 |
| Surfboard-tg-mixed | 0.618 | 68 | 42 | 110 |
| ermaozi | 0.635 | 33 | 19 | 52 |
| mheidari-all | 0.667 | 50 | 25 | 75 |
| Au1rxx-base64 | 0.869 | 278 | 42 | 320 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21594 | yes | 5.49 | 0 |
| SoliSpirit-all | 8760 | yes | 2.59 | 0 |
| Epodonios-all | 8009 | yes | 4.87 | 0 |
| Surfboard-tg-mixed | 7608 | yes | 4.18 | 0 |
| barry-far-vless | 6343 | yes | 1.89 | 0 |
| Surfboard-tg-vless | 6177 | yes | 3.37 | 0 |
| DeltaKronecker-all | 5932 | yes | 5.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.67 | 0 |
| mahdibland-V2RayAggregator | 4258 | yes | 0.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.29 | 0 |

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
| cn-block | 38 |
| geo | 30 |
| speed | 21 |
