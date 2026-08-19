# AutoNodes 每日报告

生成时间：2026-08-19 18:47:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 93105 |
| 去重后节点数 | 24449 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1240 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24449 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 25.2 |
| geo | 0.6 |
| probe | 73.1 |
| real_test | 241.2 |
| tcp | 38.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 92 | 87 | 5 | 94.6% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 778 | 775 | 3 | 99.6% |
| vless | 331 | 243 | 88 | 73.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 40 |
| speed:TimeoutError | 22 |
| 204:TimeoutError | 12 |
| geo:TimeoutError | 8 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4946 |
| ConnectionRefusedError | 975 |
| gaierror | 483 |
| OSError | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 690 | 0.986 | 1890 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.987 | prefer | 41 | 0.927 | 6336 |
| mheidari-all | 0.909 | prefer | 490 | 0.831 | 20423 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3330 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 5974 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7060 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7318 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 179 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| mheidari-all | 0.831 | 407 | 83 | 490 |
| Surfboard-tg-mixed | 0.927 | 38 | 3 | 41 |
| Au1rxx-base64 | 0.986 | 680 | 10 | 690 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20423 | yes | 5.28 | 0 |
| SoliSpirit-all | 7318 | yes | 3.29 | 0 |
| Epodonios-all | 7060 | yes | 5.65 | 0 |
| DeltaKronecker-all | 6390 | yes | 4.61 | 0 |
| Surfboard-tg-mixed | 6336 | yes | 3.79 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.67 | 0 |
| barry-far-vless | 5325 | yes | 0.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 5003 | yes | 3.59 | 0 |
| mahdibland-V2RayAggregator | 4086 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 48 |
| speed | 28 |
| 204 | 16 |
| cn-block | 10 |
