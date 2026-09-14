# AutoNodes 每日报告

生成时间：2026-09-14 21:52:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 89958 |
| 去重后节点数 | 25660 |
| TCP 可达数 | 3000 |
| 真测通过数 | 450 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25660 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 78.9 |
| geo | 1.5 |
| probe | 297.4 |
| real_test | 222.7 |
| tcp | 39.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 19 | 13 | 59.4% |
| hysteria2 | 30 | 27 | 3 | 90.0% |
| shadowsocks | 153 | 143 | 10 | 93.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 9 | 6 | 3 | 66.7% |
| vless | 304 | 252 | 52 | 82.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 12 |
| 204:TimeoutError | 11 |
| geo:TimeoutError | 7 |
| cn-block:ProxyError | 6 |
| speed:ClientOSError | 6 |
| 204:ProxyConnectionError | 4 |
| geo:ClientOSError | 4 |
| speed:TimeoutError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4747 |
| ConnectionRefusedError | 967 |
| gaierror | 574 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | prefer | 303 | 0.911 | 1752 |
| Surfboard-tg-mixed | 0.913 | prefer | 64 | 0.844 | 7602 |
| mheidari-all | 0.904 | prefer | 72 | 0.833 | 21195 |
| DeltaKronecker-all | 0.752 | prefer | 59 | 0.678 | 5972 |
| ermaozi | 0.575 | observe | 32 | 0.562 | 393 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 427 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 135 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4914 |
| Epodonios-all | 0.255 | observe | 0 | None | 7941 |
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
| ermaozi | 0.562 | 18 | 14 | 32 |
| DeltaKronecker-all | 0.678 | 40 | 19 | 59 |
| mheidari-all | 0.833 | 60 | 12 | 72 |
| Surfboard-tg-mixed | 0.844 | 54 | 10 | 64 |
| Au1rxx-base64 | 0.911 | 276 | 27 | 303 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21195 | yes | 4.95 | 0 |
| SoliSpirit-all | 8691 | yes | 5.09 | 0 |
| Epodonios-all | 7941 | yes | 5.15 | 0 |
| Surfboard-tg-mixed | 7602 | yes | 6.25 | 0 |
| barry-far-vless | 6284 | yes | 2.41 | 0 |
| Surfboard-tg-vless | 6098 | yes | 3.84 | 0 |
| DeltaKronecker-all | 5972 | yes | 5.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4914 | yes | 3.29 | 0 |
| mahdibland-V2RayAggregator | 4099 | yes | 0.76 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.97 | 0 |

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
| cn-block | 36 |
| 204 | 28 |
| geo | 11 |
| speed | 8 |
