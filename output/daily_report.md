# AutoNodes 每日报告

生成时间：2026-10-18 20:33:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97468 |
| 去重后节点数 | 27633 |
| TCP 可达数 | 3000 |
| 真测通过数 | 314 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27633 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 80.8 |
| geo | 1.4 |
| probe | 281.0 |
| real_test | 204.3 |
| tcp | 49.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 12 | 8 | 4 | 66.7% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 111 | 96 | 15 | 86.5% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 24 | 22 | 2 | 91.7% |
| vless | 240 | 175 | 65 | 72.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 20 |
| 204:ProxyError | 13 |
| cn-block:TimeoutError | 13 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 10 |
| cn-block:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7209 |
| ConnectionRefusedError | 1026 |
| gaierror | 290 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.887 | prefer | 261 | 0.82 | 1727 |
| Surfboard-tg-mixed | 0.812 | prefer | 39 | 0.744 | 7036 |
| mheidari-all | 0.793 | prefer | 85 | 0.718 | 23629 |
| ermaozi | 0.541 | observe | 13 | 0.692 | 639 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7503 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9755 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5553 |
| barry-far-vless | 0.255 | observe | 0 | None | 5766 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.25 | 1 | 3 | 4 |
| ermaozi | 0.692 | 9 | 4 | 13 |
| mheidari-all | 0.718 | 61 | 24 | 85 |
| Surfboard-tg-mixed | 0.744 | 29 | 10 | 39 |
| Au1rxx-base64 | 0.82 | 214 | 47 | 261 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23629 | yes | 3.41 | 0 |
| SoliSpirit-all | 9755 | yes | 3.31 | 0 |
| Epodonios-all | 7503 | yes | 3.65 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 3.79 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.63 | 0 |
| barry-far-vless | 5766 | yes | 1.1 | 0 |
| Surfboard-tg-vless | 5553 | yes | 2.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.76 | 0 |
| DeltaKronecker-all | 4750 | yes | 4.2 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 34 |
| cn-block | 23 |
| speed | 18 |
| geo | 13 |
