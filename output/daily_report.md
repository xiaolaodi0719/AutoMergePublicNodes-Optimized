# AutoNodes 每日报告

生成时间：2026-10-12 05:36:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 99742 |
| 去重后节点数 | 27633 |
| TCP 可达数 | 3000 |
| 真测通过数 | 530 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27633 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 72.5 |
| geo | 1.3 |
| probe | 414.5 |
| real_test | 559.0 |
| tcp | 47.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 51 | 34 | 17 | 66.7% |
| hysteria2 | 28 | 27 | 1 | 96.4% |
| shadowsocks | 129 | 123 | 6 | 95.3% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 132 | 127 | 5 | 96.2% |
| vless | 477 | 212 | 265 | 44.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 130 |
| speed:TimeoutError | 53 |
| geo:ClientOSError | 29 |
| 204:ProxyError | 24 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 13 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6564 |
| ConnectionRefusedError | 1049 |
| gaierror | 399 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | prefer | 383 | 0.916 | 1810 |
| ermaozi | 0.701 | prefer | 53 | 0.679 | 708 |
| Surfboard-tg-mixed | 0.519 | observe | 5 | 1.0 | 7200 |
| mheidari-all | 0.436 | observe | 369 | 0.355 | 23656 |
| DeltaKronecker-all | 0.385 | observe | 8 | 0.5 | 5372 |
| ermaozi-get_subscribe | 0.279 | observe | 1 | 1.0 | 600 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 53 |
| Epodonios-all | 0.255 | observe | 0 | None | 7699 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.355 | 131 | 238 | 369 |
| DeltaKronecker-all | 0.5 | 4 | 4 | 8 |
| ermaozi | 0.679 | 36 | 17 | 53 |
| Au1rxx-base64 | 0.916 | 351 | 32 | 383 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23656 | yes | 5.17 | 0 |
| SoliSpirit-all | 9920 | yes | 2.41 | 0 |
| Epodonios-all | 7699 | yes | 4.13 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 3.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.65 | 0 |
| barry-far-vless | 5961 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 5717 | yes | 3.04 | 0 |
| DeltaKronecker-all | 5372 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 5099 | yes | 0.78 | 0 |
| mahdibland-V2RayAggregator | 4284 | yes | 2.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 159 |
| speed | 77 |
| 204 | 36 |
| cn-block | 23 |
