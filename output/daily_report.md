# AutoNodes 每日报告

生成时间：2026-09-17 16:49:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 86881 |
| 去重后节点数 | 24278 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24278 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 86.8 |
| geo | 1.4 |
| probe | 277.9 |
| real_test | 229.0 |
| tcp | 41.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 39 | 24 | 15 | 61.5% |
| hysteria2 | 19 | 18 | 1 | 94.7% |
| shadowsocks | 160 | 143 | 17 | 89.4% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 13 | 12 | 1 | 92.3% |
| vless | 308 | 203 | 105 | 65.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 28 |
| geo:ClientOSError | 26 |
| 204:TimeoutError | 19 |
| geo:TimeoutError | 16 |
| cn-block:TimeoutError | 15 |
| speed:TimeoutError | 13 |
| speed:ClientOSError | 9 |
| cn-block:ClientOSError | 8 |
| 204:ClientOSError | 4 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5399 |
| ConnectionRefusedError | 928 |
| gaierror | 468 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.921 | prefer | 263 | 0.859 | 1619 |
| DeltaKronecker-all | 0.757 | prefer | 29 | 0.69 | 5931 |
| mheidari-all | 0.755 | prefer | 75 | 0.68 | 16008 |
| ermaozi | 0.742 | prefer | 31 | 0.742 | 357 |
| Surfboard-tg-mixed | 0.681 | observe | 136 | 0.603 | 7430 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 119 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5093 |
| Epodonios-all | 0.255 | observe | 0 | None | 7888 |
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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.075 | 8 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 8 | 8 |
| Surfboard-tg-mixed | 0.603 | 82 | 54 | 136 |
| mheidari-all | 0.68 | 51 | 24 | 75 |
| DeltaKronecker-all | 0.69 | 20 | 9 | 29 |
| ermaozi | 0.742 | 23 | 8 | 31 |
| Au1rxx-base64 | 0.859 | 226 | 37 | 263 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16008 | yes | 5.62 | 0 |
| SoliSpirit-all | 9066 | yes | 2.26 | 0 |
| Epodonios-all | 7888 | yes | 5.25 | 0 |
| Surfboard-tg-mixed | 7430 | yes | 4.28 | 0 |
| barry-far-vless | 6129 | yes | 1.09 | 0 |
| DeltaKronecker-all | 5931 | yes | 4.85 | 0 |
| Surfboard-tg-vless | 5904 | yes | 3.98 | 0 |
| 10ium-ScrapeCategorize-Vless | 5093 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4179 | yes | 0.17 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 53 |
| geo | 42 |
| cn-block | 24 |
| speed | 22 |
