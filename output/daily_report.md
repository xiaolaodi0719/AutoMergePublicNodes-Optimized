# AutoNodes 每日报告

生成时间：2026-09-30 22:11:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 97982 |
| 去重后节点数 | 27241 |
| TCP 可达数 | 3000 |
| 真测通过数 | 341 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27241 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 79.0 |
| geo | 1.7 |
| probe | 191.7 |
| real_test | 130.1 |
| tcp | 45.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 25 | 17 | 8 | 68.0% |
| hysteria2 | 16 | 13 | 3 | 81.2% |
| shadowsocks | 120 | 113 | 7 | 94.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 19 | 17 | 2 | 89.5% |
| vless | 244 | 177 | 67 | 72.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 43 |
| cn-block:TimeoutError | 11 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| 204:ProxyConnectionError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:TimeoutError | 2 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6284 |
| ConnectionRefusedError | 1008 |
| gaierror | 396 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.903 | prefer | 77 | 0.831 | 22901 |
| Surfboard-tg-mixed | 0.895 | prefer | 25 | 0.84 | 7200 |
| Au1rxx-base64 | 0.873 | prefer | 289 | 0.803 | 1803 |
| zhangkai | 0.745 | prefer | 15 | 0.933 | 144 |
| DeltaKronecker-all | 0.503 | observe | 12 | 0.583 | 5434 |
| tg-oneclickvpnkeys | 0.257 | observe | 1 | 1.0 | 50 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7696 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9724 |

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
| downweight | ermaozi-get_subscribe | 0.19 | 9 | 0.222 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.222 | 2 | 7 | 9 |
| DeltaKronecker-all | 0.583 | 7 | 5 | 12 |
| Au1rxx-base64 | 0.803 | 232 | 57 | 289 |
| mheidari-all | 0.831 | 64 | 13 | 77 |
| Surfboard-tg-mixed | 0.84 | 21 | 4 | 25 |
| zhangkai | 0.933 | 14 | 1 | 15 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22901 | yes | 5.62 | 0 |
| SoliSpirit-all | 9724 | yes | 1.67 | 0 |
| Epodonios-all | 7696 | yes | 4.99 | 0 |
| Surfboard-tg-mixed | 7200 | yes | 3.62 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.19 | 0 |
| barry-far-vless | 6072 | yes | 1.0 | 0 |
| Surfboard-tg-vless | 5833 | yes | 3.82 | 0 |
| DeltaKronecker-all | 5434 | yes | 6.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 3.13 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 45 |
| 204 | 19 |
| cn-block | 18 |
| geo | 6 |
