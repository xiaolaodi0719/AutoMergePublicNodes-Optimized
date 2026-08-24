# AutoNodes 每日报告

生成时间：2026-08-24 01:44:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 78233 |
| 去重后节点数 | 21555 |
| TCP 可达数 | 3000 |
| 真测通过数 | 741 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21555 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| generate | 23.5 |
| geo | 1.3 |
| probe | 57.6 |
| real_test | 166.1 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 112 | 112 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 208 | 200 | 8 | 96.2% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 43 | 32 | 11 | 74.4% |
| vless | 541 | 370 | 171 | 68.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 69 |
| speed:TimeoutError | 41 |
| geo:ClientOSError | 23 |
| speed:ClientOSError | 20 |
| cn-block:TimeoutError | 17 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 8 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4716 |
| ConnectionRefusedError | 849 |
| gaierror | 380 |
| OSError | 20 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Au1rxx-base64 | 0.987 | prefer | 444 | 0.921 | 1688 |
| Surfboard-tg-mixed | 0.858 | prefer | 156 | 0.782 | 6383 |
| DeltaKronecker-all | 0.588 | observe | 63 | 0.508 | 5415 |
| mheidari-all | 0.503 | observe | 147 | 0.422 | 14677 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |
| Epodonios-all | 0.255 | observe | 0 | None | 6993 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7072 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | nscl5-all | 0.233 | 7 | 0.286 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| nscl5-all | 0.286 | 2 | 5 | 7 |
| mheidari-all | 0.422 | 62 | 85 | 147 |
| DeltaKronecker-all | 0.508 | 32 | 31 | 63 |
| Surfboard-tg-mixed | 0.782 | 122 | 34 | 156 |
| Au1rxx-base64 | 0.921 | 409 | 35 | 444 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14677 | yes | 2.19 | 0 |
| SoliSpirit-all | 7072 | yes | 2.23 | 0 |
| Epodonios-all | 6993 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 6383 | yes | 2.0 | 0 |
| barry-far-vless | 5618 | yes | 1.27 | 0 |
| DeltaKronecker-all | 5415 | yes | 2.44 | 0 |
| Surfboard-tg-vless | 5292 | yes | 1.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 1.37 | 0 |
| mahdibland-V2RayAggregator | 4085 | yes | 0.4 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 1.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 92 |
| speed | 62 |
| cn-block | 26 |
| 204 | 13 |
