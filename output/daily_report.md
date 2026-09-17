# AutoNodes 每日报告

生成时间：2026-09-17 21:18:37

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 5/101 |
| 原始节点数 | 84619 |
| 去重后节点数 | 23068 |
| TCP 可达数 | 3000 |
| 真测通过数 | 427 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23068 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 80.3 |
| geo | 1.5 |
| probe | 252.7 |
| real_test | 195.4 |
| tcp | 38.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 24 | 11 | 68.6% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 138 | 129 | 9 | 93.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 19 | 14 | 5 | 73.7% |
| vless | 318 | 241 | 77 | 75.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 23 |
| geo:TimeoutError | 15 |
| 204:TimeoutError | 13 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ProxyConnectionError | 6 |
| speed:TimeoutError | 5 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5264 |
| ConnectionRefusedError | 827 |
| gaierror | 387 |
| OSError | 18 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.961 | prefer | 267 | 0.899 | 1619 |
| Surfboard-tg-mixed | 0.83 | prefer | 58 | 0.759 | 7499 |
| DeltaKronecker-all | 0.788 | prefer | 118 | 0.712 | 5931 |
| ermaozi | 0.742 | prefer | 31 | 0.742 | 357 |
| mheidari-all | 0.71 | prefer | 52 | 0.635 | 16164 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4261 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7954 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8875 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.234 | 5 | 0.4 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.4 | 2 | 3 | 5 |
| mheidari-all | 0.635 | 33 | 19 | 52 |
| DeltaKronecker-all | 0.712 | 84 | 34 | 118 |
| ermaozi | 0.742 | 23 | 8 | 31 |
| Surfboard-tg-mixed | 0.759 | 44 | 14 | 58 |
| Au1rxx-base64 | 0.899 | 240 | 27 | 267 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16164 | yes | 4.9 | 0 |
| SoliSpirit-all | 8875 | yes | 2.29 | 0 |
| Epodonios-all | 7954 | yes | 2.43 | 0 |
| Surfboard-tg-mixed | 7499 | yes | 3.88 | 0 |
| barry-far-vless | 6157 | yes | 1.43 | 0 |
| Surfboard-tg-vless | 5936 | yes | 4.13 | 0 |
| DeltaKronecker-all | 5931 | yes | 3.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 1.2 | 0 |
| mahdibland-V2RayAggregator | 4261 | yes | 3.14 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.72 | 0 |

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
| geo | 39 |
| 204 | 32 |
| cn-block | 21 |
| speed | 14 |
