# AutoNodes 每日报告

生成时间：2026-08-20 18:52:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 95001 |
| 去重后节点数 | 25243 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1065 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25243 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 44.7 |
| geo | 0.6 |
| probe | 65.6 |
| real_test | 179.4 |
| tcp | 38.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 110 | 110 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 87 | 83 | 4 | 95.4% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 600 | 598 | 2 | 99.7% |
| vless | 361 | 254 | 107 | 70.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 44 |
| geo:TimeoutError | 12 |
| 204:TimeoutError | 11 |
| speed:TimeoutError | 10 |
| cn-block:TimeoutError | 9 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| 204:ProxyError | 3 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5036 |
| ConnectionRefusedError | 990 |
| gaierror | 605 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 566 | 0.961 | 1789 |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| mheidari-all | 0.898 | prefer | 481 | 0.819 | 22064 |
| Surfboard-tg-mixed | 0.853 | prefer | 16 | 0.938 | 6440 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| Epodonios-all | 0.255 | observe | 0 | None | 7181 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7349 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5117 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| DeltaKronecker-all | 0.17 | observe | 3 | 0.0 | 0 | 6781 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 3 | 3 |
| mheidari-all | 0.819 | 394 | 87 | 481 |
| Surfboard-tg-mixed | 0.938 | 15 | 1 | 16 |
| Au1rxx-base64 | 0.961 | 544 | 22 | 566 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22064 | yes | 4.34 | 0 |
| SoliSpirit-all | 7349 | yes | 2.65 | 0 |
| Epodonios-all | 7181 | yes | 2.96 | 0 |
| DeltaKronecker-all | 6781 | yes | 3.61 | 0 |
| Surfboard-tg-mixed | 6440 | yes | 0.32 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 2.45 | 0 |
| barry-far-vless | 5501 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 5117 | yes | 2.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 1.63 | 0 |
| mahdibland-V2RayAggregator | 4586 | yes | 0.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 57 |
| cn-block | 20 |
| 204 | 19 |
| speed | 18 |
