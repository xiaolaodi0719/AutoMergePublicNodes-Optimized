# AutoNodes 每日报告

生成时间：2026-09-27 16:51:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 96135 |
| 去重后节点数 | 26661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 334 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 78.9 |
| geo | 1.5 |
| probe | 185.6 |
| real_test | 139.5 |
| tcp | 44.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 39 | 23 | 16 | 59.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 131 | 117 | 14 | 89.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 8 | 6 | 2 | 75.0% |
| vless | 211 | 168 | 43 | 79.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 20 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 15 |
| speed:TimeoutError | 8 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| geo:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6233 |
| ConnectionRefusedError | 959 |
| gaierror | 312 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.916 | prefer | 296 | 0.855 | 1601 |
| Surfboard-tg-mixed | 0.84 | prefer | 17 | 0.882 | 7109 |
| mheidari-all | 0.834 | prefer | 55 | 0.764 | 22413 |
| ermaozi | 0.65 | observe | 34 | 0.647 | 289 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7600 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9194 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5703 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.158 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 2 | 2 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| ermaozi | 0.647 | 22 | 12 | 34 |
| mheidari-all | 0.764 | 42 | 13 | 55 |
| Au1rxx-base64 | 0.855 | 253 | 43 | 296 |
| Surfboard-tg-mixed | 0.882 | 15 | 2 | 17 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22413 | yes | 5.84 | 0 |
| SoliSpirit-all | 9194 | yes | 2.33 | 0 |
| Epodonios-all | 7600 | yes | 3.77 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 3.59 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.79 | 0 |
| barry-far-vless | 5938 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 5703 | yes | 4.55 | 0 |
| DeltaKronecker-all | 5466 | yes | 3.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.52 | 0 |
| mahdibland-V2RayAggregator | 4277 | yes | 2.62 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 18 |
| speed | 14 |
| geo | 7 |
