# AutoNodes 每日报告

生成时间：2026-08-04 14:31:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 86444 |
| 去重后节点数 | 24261 |
| TCP 可达数 | 3000 |
| 真测通过数 | 494 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24261 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 20.2 |
| generate | 30.0 |
| geo | 1.4 |
| probe | 53.5 |
| real_test | 114.8 |
| tcp | 37.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 51 | 50 | 1 | 98.0% |
| hysteria2 | 20 | 20 | 0 | 100.0% |
| shadowsocks | 146 | 115 | 31 | 78.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 126 | 121 | 5 | 96.0% |
| vless | 277 | 185 | 92 | 66.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 25 |
| 204:TimeoutError | 23 |
| geo:ClientOSError | 22 |
| speed:TimeoutError | 17 |
| speed:ClientOSError | 14 |
| 204:ClientOSError | 10 |
| cn-block:ClientOSError | 8 |
| cn-block:TimeoutError | 6 |
| 204:ProxyError | 5 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5008 |
| ConnectionRefusedError | 823 |
| gaierror | 250 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.947 | prefer | 52 | 0.962 | 72 |
| Au1rxx-base64 | 0.903 | prefer | 478 | 0.837 | 1684 |
| mheidari-all | 0.524 | observe | 70 | 0.443 | 20302 |
| Surfboard-tg-mixed | 0.45 | observe | 12 | 0.5 | 5397 |
| DeltaKronecker-all | 0.407 | observe | 11 | 0.455 | 5788 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 58 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5251 |
| Epodonios-all | 0.255 | observe | 0 | None | 5995 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.443 | 31 | 39 | 70 |
| DeltaKronecker-all | 0.455 | 5 | 6 | 11 |
| Surfboard-tg-mixed | 0.5 | 6 | 6 | 12 |
| Au1rxx-base64 | 0.837 | 400 | 78 | 478 |
| zhangkai | 0.962 | 50 | 2 | 52 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20302 | yes | 5.59 | 0 |
| SoliSpirit-all | 7036 | yes | 2.54 | 0 |
| Epodonios-all | 5995 | yes | 2.96 | 0 |
| DeltaKronecker-all | 5788 | yes | 5.67 | 0 |
| Surfboard-tg-mixed | 5397 | yes | 3.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 5251 | yes | 2.84 | 0 |
| xiaoji235-airport-v2ray-all | 5127 | yes | 3.34 | 0 |
| mahdibland-V2RayAggregator | 5110 | yes | 3.3 | 0 |
| barry-far-vless | 4658 | yes | 3.49 | 0 |
| Surfboard-tg-vless | 4315 | yes | 3.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 48 |
| 204 | 38 |
| speed | 31 |
| cn-block | 15 |
