# AutoNodes 每日报告

生成时间：2026-09-24 04:23:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/2 |
| 清理建议：优先/观察 | 2/103 |
| 原始节点数 | 96874 |
| 去重后节点数 | 26609 |
| TCP 可达数 | 3000 |
| 真测通过数 | 553 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26609 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 94.5 |
| geo | 1.5 |
| probe | 350.3 |
| real_test | 577.1 |
| tcp | 43.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 34 | 17 | 17 | 50.0% |
| hysteria2 | 25 | 25 | 0 | 100.0% |
| shadowsocks | 170 | 159 | 11 | 93.5% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 48 | 29 | 19 | 60.4% |
| vless | 833 | 315 | 518 | 37.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 219 |
| speed:TimeoutError | 81 |
| geo:ClientOSError | 65 |
| cn-block:ClientOSError | 57 |
| speed:ClientOSError | 52 |
| 204:ProxyError | 31 |
| 204:TimeoutError | 29 |
| cn-block:TimeoutError | 27 |
| cn-block:ProxyError | 3 |
| 204:ServerDisconnectedError | 2 |
| speed:ClientPayloadError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6181 |
| ConnectionRefusedError | 954 |
| gaierror | 333 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.937 | prefer | 253 | 0.874 | 1648 |
| Surfboard-tg-mixed | 0.845 | prefer | 100 | 0.77 | 7099 |
| ermaozi | 0.58 | observe | 28 | 0.571 | 339 |
| mheidari-all | 0.406 | observe | 724 | 0.326 | 22298 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4332 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 149 |
| Epodonios-all | 0.255 | observe | 0 | None | 7563 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8881 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5729 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.151 | 6 | 0.167 | 0 | 已测数量 >= 5 且评分偏低 |
| downweight | DeltaKronecker-all | 0.153 | 5 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 5 | 5 |
| ermaozi-get_subscribe | 0.167 | 1 | 5 | 6 |
| mheidari-all | 0.326 | 236 | 488 | 724 |
| ermaozi | 0.571 | 16 | 12 | 28 |
| Surfboard-tg-mixed | 0.77 | 77 | 23 | 100 |
| Au1rxx-base64 | 0.874 | 221 | 32 | 253 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22298 | yes | 5.88 | 0 |
| SoliSpirit-all | 8881 | yes | 3.35 | 0 |
| Epodonios-all | 7563 | yes | 4.22 | 0 |
| Surfboard-tg-mixed | 7099 | yes | 4.02 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.23 | 0 |
| DeltaKronecker-all | 6471 | yes | 6.62 | 0 |
| barry-far-vless | 5948 | yes | 0.54 | 0 |
| Surfboard-tg-vless | 5729 | yes | 4.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5131 | yes | 0.77 | 0 |
| mahdibland-V2RayAggregator | 4332 | yes | 3.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 284 |
| speed | 134 |
| cn-block | 87 |
| 204 | 63 |
