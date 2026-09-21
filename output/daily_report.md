# AutoNodes 每日报告

生成时间：2026-09-21 12:36:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 84513 |
| 去重后节点数 | 23453 |
| TCP 可达数 | 3000 |
| 真测通过数 | 463 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23453 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 75.3 |
| geo | 1.4 |
| probe | 215.9 |
| real_test | 217.6 |
| tcp | 39.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 26 | 23 | 53.1% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 157 | 142 | 15 | 90.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 36 | 30 | 6 | 83.3% |
| vless | 380 | 244 | 136 | 64.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 38 |
| geo:ClientOSError | 36 |
| 204:ProxyError | 32 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 13 |
| cn-block:ClientOSError | 12 |
| speed:TimeoutError | 12 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5782 |
| ConnectionRefusedError | 789 |
| gaierror | 175 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.938 | prefer | 272 | 0.875 | 1649 |
| mheidari-all | 0.937 | prefer | 33 | 0.879 | 16192 |
| Surfboard-tg-mixed | 0.709 | prefer | 200 | 0.63 | 7246 |
| DeltaKronecker-all | 0.62 | observe | 61 | 0.541 | 6181 |
| ermaozi | 0.53 | observe | 62 | 0.516 | 350 |
| Au1rxx-clash | 0.424 | observe | 3 | 1.0 | 1638 |
| tg-oneclickvpnkeys | 0.273 | observe | 3 | 0.667 | 108 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5290 |
| Epodonios-all | 0.255 | observe | 0 | None | 7697 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

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
| downweight | ermaozi-get_subscribe | 0.071 | 10 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 10 | 10 |
| ermaozi | 0.516 | 32 | 30 | 62 |
| DeltaKronecker-all | 0.541 | 33 | 28 | 61 |
| Surfboard-tg-mixed | 0.63 | 126 | 74 | 200 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.875 | 238 | 34 | 272 |
| mheidari-all | 0.879 | 29 | 4 | 33 |
| Au1rxx-clash | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16192 | yes | 2.82 | 0 |
| SoliSpirit-all | 8900 | yes | 2.42 | 0 |
| Epodonios-all | 7697 | yes | 2.99 | 0 |
| Surfboard-tg-mixed | 7246 | yes | 2.54 | 0 |
| DeltaKronecker-all | 6181 | yes | 3.62 | 0 |
| barry-far-vless | 6062 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 5845 | yes | 3.4 | 0 |
| 10ium-ScrapeCategorize-Vless | 5290 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4358 | yes | 0.93 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.5 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 74 |
| 204 | 48 |
| speed | 32 |
| cn-block | 28 |
