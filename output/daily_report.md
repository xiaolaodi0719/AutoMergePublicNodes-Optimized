# AutoNodes 每日报告

生成时间：2026-09-24 11:36:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 96310 |
| 去重后节点数 | 26222 |
| TCP 可达数 | 3000 |
| 真测通过数 | 367 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26222 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 83.5 |
| geo | 1.5 |
| probe | 246.9 |
| real_test | 215.8 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 68 | 41 | 27 | 60.3% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 163 | 146 | 17 | 89.6% |
| socks | 7 | 5 | 2 | 71.4% |
| trojan | 25 | 13 | 12 | 52.0% |
| vless | 253 | 140 | 113 | 55.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 33 |
| 204:TimeoutError | 32 |
| cn-block:ClientOSError | 26 |
| geo:TimeoutError | 24 |
| cn-block:TimeoutError | 22 |
| speed:TimeoutError | 15 |
| geo:ClientOSError | 11 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| speed:ClientOSError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5615 |
| ConnectionRefusedError | 971 |
| gaierror | 390 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.893 | prefer | 217 | 0.829 | 1658 |
| Surfboard-tg-mixed | 0.725 | prefer | 122 | 0.648 | 7027 |
| ermaozi | 0.632 | observe | 53 | 0.623 | 339 |
| mheidari-all | 0.596 | observe | 120 | 0.517 | 22399 |
| ermaozi-get_subscribe | 0.49 | observe | 17 | 0.529 | 373 |
| DeltaKronecker-all | 0.4 | observe | 4 | 0.75 | 5845 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Epodonios-all | 0.255 | observe | 0 | None | 7495 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8857 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.517 | 62 | 58 | 120 |
| ermaozi-get_subscribe | 0.529 | 9 | 8 | 17 |
| ermaozi | 0.623 | 33 | 20 | 53 |
| Surfboard-tg-mixed | 0.648 | 79 | 43 | 122 |
| DeltaKronecker-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.829 | 180 | 37 | 217 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22399 | yes | 6.2 | 0 |
| SoliSpirit-all | 8857 | yes | 3.86 | 0 |
| Epodonios-all | 7495 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 7027 | yes | 4.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.45 | 0 |
| barry-far-vless | 5899 | yes | 1.2 | 0 |
| DeltaKronecker-all | 5845 | yes | 6.31 | 0 |
| Surfboard-tg-vless | 5676 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 5307 | yes | 1.44 | 0 |
| mahdibland-V2RayAggregator | 4305 | yes | 0.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 67 |
| cn-block | 51 |
| geo | 36 |
| speed | 17 |
