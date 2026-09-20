# AutoNodes 每日报告

生成时间：2026-09-20 11:10:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 83340 |
| 去重后节点数 | 23416 |
| TCP 可达数 | 3000 |
| 真测通过数 | 493 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23416 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 90.0 |
| geo | 1.5 |
| probe | 251.8 |
| real_test | 182.0 |
| tcp | 38.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 54 | 42 | 12 | 77.8% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 173 | 160 | 13 | 92.5% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 33 | 26 | 7 | 78.8% |
| vless | 345 | 249 | 96 | 72.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 36 |
| geo:TimeoutError | 21 |
| 204:ProxyError | 19 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 12 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 9 |
| speed:ClientOSError | 9 |
| cn-block:ProxyError | 2 |
| 204:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5424 |
| ConnectionRefusedError | 794 |
| gaierror | 334 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 268 | 0.94 | 1589 |
| mheidari-all | 0.94 | prefer | 41 | 0.878 | 15979 |
| ermaozi | 0.76 | prefer | 53 | 0.755 | 365 |
| Surfboard-tg-mixed | 0.748 | prefer | 197 | 0.67 | 7118 |
| DeltaKronecker-all | 0.588 | observe | 59 | 0.508 | 6092 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4315 |
| 10ium-ScrapeCategorize-Vless | 0.259 | observe | 3 | 0.333 | 5238 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 89 |
| Epodonios-all | 0.255 | observe | 0 | None | 7603 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| 10ium-ScrapeCategorize-Vless | 0.333 | 1 | 2 | 3 |
| DeltaKronecker-all | 0.508 | 30 | 29 | 59 |
| Surfboard-tg-mixed | 0.67 | 132 | 65 | 197 |
| ermaozi | 0.755 | 40 | 13 | 53 |
| mheidari-all | 0.878 | 36 | 5 | 41 |
| Au1rxx-base64 | 0.94 | 252 | 16 | 268 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15979 | yes | 4.28 | 0 |
| SoliSpirit-all | 8786 | yes | 3.4 | 0 |
| Epodonios-all | 7603 | yes | 5.81 | 0 |
| Surfboard-tg-mixed | 7118 | yes | 3.17 | 0 |
| DeltaKronecker-all | 6092 | yes | 5.23 | 0 |
| barry-far-vless | 5912 | yes | 2.4 | 0 |
| Surfboard-tg-vless | 5686 | yes | 3.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5238 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 4315 | yes | 0.27 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 57 |
| 204 | 32 |
| cn-block | 24 |
| speed | 20 |
