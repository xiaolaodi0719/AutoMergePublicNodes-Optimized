# AutoNodes 每日报告

生成时间：2026-08-15 18:42:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 78636 |
| 去重后节点数 | 22463 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1052 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22463 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.9 |
| generate | 32.1 |
| geo | 0.9 |
| probe | 70.3 |
| real_test | 188.7 |
| tcp | 33.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 18 | 17 | 1 | 94.4% |
| shadowsocks | 148 | 133 | 15 | 89.9% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 580 | 576 | 4 | 99.3% |
| vless | 254 | 192 | 62 | 75.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 15 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 13 |
| geo:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 6 |
| speed:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4330 |
| ConnectionRefusedError | 807 |
| gaierror | 392 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 693 | 0.96 | 1997 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.93 | prefer | 198 | 0.854 | 16339 |
| Surfboard-tg-mixed | 0.882 | prefer | 104 | 0.808 | 5684 |
| nscl5-all | 0.438 | observe | 3 | 1.0 | 2081 |
| Surfboard-tg-vless | 0.335 | observe | 1 | 1.0 | 4350 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5113 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1997 |
| Epodonios-all | 0.255 | observe | 0 | None | 6266 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.249 | 10 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.2 | 2 | 8 | 10 |
| Surfboard-tg-mixed | 0.808 | 84 | 20 | 104 |
| mheidari-all | 0.854 | 169 | 29 | 198 |
| Au1rxx-base64 | 0.96 | 665 | 28 | 693 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-vless | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16339 | yes | 4.64 | 0 |
| SoliSpirit-all | 7464 | yes | 4.25 | 0 |
| Epodonios-all | 6266 | yes | 4.82 | 0 |
| DeltaKronecker-all | 5773 | yes | 5.29 | 0 |
| Surfboard-tg-mixed | 5684 | yes | 3.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 3.3 | 0 |
| barry-far-vless | 4694 | yes | 2.93 | 0 |
| Surfboard-tg-vless | 4350 | yes | 3.69 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 3.01 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 0.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 25 |
| cn-block | 24 |
| geo | 18 |
| speed | 18 |
