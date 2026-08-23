# AutoNodes 每日报告

生成时间：2026-08-23 06:54:17

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 98/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77609 |
| 去重后节点数 | 21147 |
| TCP 可达数 | 3000 |
| 真测通过数 | 804 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21147 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 36.7 |
| geo | 1.5 |
| probe | 57.2 |
| real_test | 158.1 |
| tcp | 33.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 19 | 19 | 0 | 100.0% |
| shadowsocks | 223 | 212 | 11 | 95.1% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 145 | 134 | 11 | 92.4% |
| vless | 450 | 320 | 130 | 71.1% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 43 |
| speed:TimeoutError | 31 |
| cn-block:TimeoutError | 16 |
| speed:ClientOSError | 15 |
| geo:ClientOSError | 14 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4530 |
| ConnectionRefusedError | 842 |
| gaierror | 360 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Au1rxx-base64 | 0.991 | prefer | 489 | 0.92 | 1821 |
| Surfboard-tg-mixed | 0.891 | prefer | 157 | 0.815 | 6303 |
| DeltaKronecker-all | 0.687 | observe | 82 | 0.61 | 5288 |
| mheidari-all | 0.594 | observe | 107 | 0.514 | 14434 |
| nscl5-all | 0.452 | observe | 6 | 0.833 | 1082 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 131 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4989 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.514 | 55 | 52 | 107 |
| DeltaKronecker-all | 0.61 | 50 | 32 | 82 |
| Surfboard-tg-mixed | 0.815 | 128 | 29 | 157 |
| nscl5-all | 0.833 | 5 | 1 | 6 |
| Au1rxx-base64 | 0.92 | 450 | 39 | 489 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14434 | yes | 3.97 | 0 |
| SoliSpirit-all | 7111 | yes | 2.88 | 0 |
| Epodonios-all | 6859 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 6303 | yes | 4.39 | 0 |
| barry-far-vless | 5430 | yes | 1.37 | 0 |
| DeltaKronecker-all | 5288 | yes | 4.99 | 0 |
| Surfboard-tg-vless | 5154 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4989 | yes | 2.1 | 0 |
| mahdibland-V2RayAggregator | 4094 | yes | 0.19 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 57 |
| speed | 46 |
| cn-block | 27 |
| 204 | 24 |
