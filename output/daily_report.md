# AutoNodes 每日报告

生成时间：2026-09-20 20:44:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 83613 |
| 去重后节点数 | 23435 |
| TCP 可达数 | 3000 |
| 真测通过数 | 487 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23435 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 86.2 |
| geo | 1.6 |
| probe | 218.3 |
| real_test | 207.7 |
| tcp | 38.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 26 | 6 | 81.2% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 157 | 149 | 8 | 94.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 17 | 9 | 8 | 52.9% |
| vless | 395 | 289 | 106 | 73.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 29 |
| 204:TimeoutError | 21 |
| cn-block:TimeoutError | 16 |
| 204:ProxyError | 15 |
| geo:TimeoutError | 15 |
| cn-block:ClientOSError | 11 |
| speed:ClientOSError | 8 |
| 204:ProxyConnectionError | 5 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5284 |
| ConnectionRefusedError | 790 |
| gaierror | 384 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | prefer | 284 | 0.915 | 1574 |
| DeltaKronecker-all | 0.886 | prefer | 29 | 0.828 | 6092 |
| ermaozi | 0.834 | prefer | 26 | 0.846 | 314 |
| mheidari-all | 0.802 | prefer | 52 | 0.731 | 16265 |
| Surfboard-tg-mixed | 0.722 | prefer | 213 | 0.643 | 7207 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 74 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7615 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8753 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 3 | 3 |
| 10ium-ScrapeCategorize-Vless | 0.25 | 1 | 3 | 4 |
| Surfboard-tg-mixed | 0.643 | 137 | 76 | 213 |
| mheidari-all | 0.731 | 38 | 14 | 52 |
| DeltaKronecker-all | 0.828 | 24 | 5 | 29 |
| ermaozi | 0.846 | 22 | 4 | 26 |
| Au1rxx-base64 | 0.915 | 260 | 24 | 284 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16265 | yes | 4.58 | 0 |
| SoliSpirit-all | 8753 | yes | 2.23 | 0 |
| Epodonios-all | 7615 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 7207 | yes | 3.6 | 0 |
| DeltaKronecker-all | 6092 | yes | 5.02 | 0 |
| barry-far-vless | 5924 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5768 | yes | 3.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 1.24 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 1.75 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.76 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 44 |
| geo | 44 |
| cn-block | 29 |
| speed | 13 |
