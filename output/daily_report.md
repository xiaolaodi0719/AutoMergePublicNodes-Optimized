# AutoNodes 每日报告

生成时间：2026-09-21 04:31:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 1/104 |
| 原始节点数 | 83915 |
| 去重后节点数 | 23652 |
| TCP 可达数 | 3000 |
| 真测通过数 | 658 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23652 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 74.8 |
| geo | 1.5 |
| probe | 280.7 |
| real_test | 444.0 |
| tcp | 39.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 34 | 17 | 66.7% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 182 | 169 | 13 | 92.9% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 46 | 27 | 19 | 58.7% |
| vless | 785 | 408 | 377 | 52.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 174 |
| geo:ClientOSError | 82 |
| speed:TimeoutError | 51 |
| speed:ClientOSError | 44 |
| 204:ProxyError | 24 |
| cn-block:ClientOSError | 16 |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 12 |
| 204:ClientOSError | 4 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5669 |
| ConnectionRefusedError | 789 |
| gaierror | 207 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.936 | prefer | 310 | 0.871 | 1693 |
| ermaozi | 0.696 | observe | 42 | 0.69 | 355 |
| Surfboard-tg-mixed | 0.617 | observe | 158 | 0.538 | 7202 |
| DeltaKronecker-all | 0.562 | observe | 452 | 0.482 | 6092 |
| mheidari-all | 0.561 | observe | 102 | 0.48 | 15960 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 74 |
| Epodonios-all | 0.255 | observe | 0 | None | 7661 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | 10ium-ScrapeCategorize-Vless | 0.148 | 6 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | ermaozi-get_subscribe | 0.24 | 10 | 0.3 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 6 | 6 |
| ermaozi-get_subscribe | 0.3 | 3 | 7 | 10 |
| mheidari-all | 0.48 | 49 | 53 | 102 |
| DeltaKronecker-all | 0.482 | 218 | 234 | 452 |
| Surfboard-tg-mixed | 0.538 | 85 | 73 | 158 |
| ermaozi | 0.69 | 29 | 13 | 42 |
| Au1rxx-base64 | 0.871 | 270 | 40 | 310 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15960 | yes | 5.99 | 0 |
| SoliSpirit-all | 8828 | yes | 1.69 | 0 |
| Epodonios-all | 7661 | yes | 3.46 | 0 |
| Surfboard-tg-mixed | 7202 | yes | 3.81 | 0 |
| DeltaKronecker-all | 6092 | yes | 3.63 | 0 |
| barry-far-vless | 6015 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 5800 | yes | 5.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 3.11 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 257 |
| speed | 98 |
| 204 | 43 |
| cn-block | 30 |
