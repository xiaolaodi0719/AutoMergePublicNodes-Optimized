# AutoNodes 每日报告

生成时间：2026-10-19 22:19:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 94419 |
| 去重后节点数 | 25980 |
| TCP 可达数 | 3000 |
| 真测通过数 | 400 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25980 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 79.0 |
| geo | 1.5 |
| probe | 219.7 |
| real_test | 197.9 |
| tcp | 44.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 144 | 127 | 17 | 88.2% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 46 | 42 | 4 | 91.3% |
| vless | 260 | 194 | 66 | 74.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 14 |
| speed:ClientOSError | 13 |
| geo:ClientOSError | 11 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 6 |
| geo:TimeoutError | 6 |
| 204:ProxyConnectionError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6682 |
| ConnectionRefusedError | 1020 |
| OSError | 234 |
| gaierror | 152 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 27 |
| Au1rxx-base64 | 0.902 | prefer | 278 | 0.849 | 1390 |
| mheidari-all | 0.867 | prefer | 59 | 0.797 | 23238 |
| Surfboard-tg-mixed | 0.812 | prefer | 125 | 0.736 | 7064 |
| DeltaKronecker-all | 0.401 | observe | 7 | 0.571 | 3294 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 72 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| Epodonios-all | 0.255 | observe | 0 | None | 7515 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9850 |

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
| DeltaKronecker-all | 0.571 | 4 | 3 | 7 |
| Surfboard-tg-mixed | 0.736 | 92 | 33 | 125 |
| mheidari-all | 0.797 | 47 | 12 | 59 |
| Au1rxx-base64 | 0.849 | 236 | 42 | 278 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23238 | yes | 5.04 | 0 |
| SoliSpirit-all | 9850 | yes | 4.38 | 0 |
| Epodonios-all | 7515 | yes | 4.18 | 0 |
| Surfboard-tg-mixed | 7064 | yes | 4.43 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.39 | 0 |
| barry-far-vless | 5797 | yes | 1.83 | 0 |
| Surfboard-tg-vless | 5579 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 1.06 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 28 |
| 204 | 22 |
| speed | 21 |
| geo | 19 |
