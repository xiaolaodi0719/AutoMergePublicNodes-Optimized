# AutoNodes 每日报告

生成时间：2026-10-04 21:16:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 99286 |
| 去重后节点数 | 27467 |
| TCP 可达数 | 3000 |
| 真测通过数 | 498 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27467 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 69.2 |
| geo | 1.0 |
| probe | 268.6 |
| real_test | 223.5 |
| tcp | 47.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 4 | 1 | 80.0% |
| http | 25 | 24 | 1 | 96.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 148 | 127 | 21 | 85.8% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 93 | 80 | 13 | 86.0% |
| vless | 275 | 237 | 38 | 86.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 21 |
| 204:ProxyError | 7 |
| speed:TimeoutError | 6 |
| geo:TimeoutError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6661 |
| ConnectionRefusedError | 1055 |
| gaierror | 362 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.998 | prefer | 367 | 0.926 | 1858 |
| ermaozi | 0.952 | prefer | 25 | 0.96 | 653 |
| mheidari-all | 0.852 | prefer | 55 | 0.782 | 23222 |
| Surfboard-tg-mixed | 0.804 | prefer | 114 | 0.728 | 7257 |
| Au1rxx-clash | 0.432 | observe | 3 | 1.0 | 1844 |
| ermaozi-get_subscribe | 0.341 | observe | 4 | 0.75 | 518 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 68 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7751 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.728 | 83 | 31 | 114 |
| ermaozi-get_subscribe | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.782 | 43 | 12 | 55 |
| Au1rxx-base64 | 0.926 | 340 | 27 | 367 |
| ermaozi | 0.96 | 24 | 1 | 25 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Au1rxx-clash | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23222 | yes | 3.74 | 0 |
| SoliSpirit-all | 9655 | yes | 1.85 | 0 |
| Epodonios-all | 7751 | yes | 2.01 | 0 |
| Surfboard-tg-mixed | 7257 | yes | 2.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.51 | 0 |
| barry-far-vless | 6058 | yes | 0.58 | 0 |
| Surfboard-tg-vless | 5820 | yes | 2.17 | 0 |
| DeltaKronecker-all | 5267 | yes | 3.14 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 0.76 | 0 |
| mahdibland-V2RayAggregator | 4365 | yes | 1.75 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| cn-block | 26 |
| speed | 10 |
| geo | 8 |
