# AutoNodes 每日报告

生成时间：2026-08-06 08:49:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 88936 |
| 去重后节点数 | 24432 |
| TCP 可达数 | 3000 |
| 真测通过数 | 447 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24432 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 34.0 |
| geo | 1.5 |
| probe | 50.9 |
| real_test | 92.6 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 17 | 5 | 77.3% |
| shadowsocks | 167 | 147 | 20 | 88.0% |
| socks | 8 | 4 | 4 | 50.0% |
| trojan | 165 | 157 | 8 | 95.2% |
| vless | 185 | 101 | 84 | 54.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 40 |
| geo:ClientOSError | 19 |
| 204:ProxyError | 13 |
| 204:TimeoutError | 12 |
| 204:ClientOSError | 9 |
| cn-block:TimeoutError | 9 |
| speed:TimeoutError | 9 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4774 |
| ConnectionRefusedError | 815 |
| gaierror | 315 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | prefer | 353 | 0.932 | 1409 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.662 | observe | 132 | 0.583 | 5873 |
| DeltaKronecker-all | 0.515 | observe | 21 | 0.429 | 5897 |
| mheidari-all | 0.366 | observe | 40 | 0.275 | 20781 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5219 |
| Epodonios-all | 0.255 | observe | 0 | None | 6505 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7196 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.275 | 11 | 29 | 40 |
| DeltaKronecker-all | 0.429 | 9 | 12 | 21 |
| Surfboard-tg-mixed | 0.583 | 77 | 55 | 132 |
| Au1rxx-base64 | 0.932 | 329 | 24 | 353 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20781 | yes | 5.6 | 0 |
| SoliSpirit-all | 7196 | yes | 3.73 | 0 |
| Epodonios-all | 6505 | yes | 4.1 | 0 |
| DeltaKronecker-all | 5897 | yes | 4.53 | 0 |
| Surfboard-tg-mixed | 5873 | yes | 3.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 5219 | yes | 2.52 | 0 |
| xiaoji235-airport-v2ray-all | 5214 | yes | 2.89 | 0 |
| mahdibland-V2RayAggregator | 5212 | yes | 2.35 | 0 |
| barry-far-vless | 5049 | yes | 2.24 | 0 |
| Surfboard-tg-vless | 4677 | yes | 2.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 59 |
| 204 | 34 |
| speed | 15 |
| cn-block | 13 |
