# AutoNodes 每日报告

生成时间：2026-07-30 14:18:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78835 |
| 去重后节点数 | 22975 |
| TCP 可达数 | 3000 |
| 真测通过数 | 442 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22975 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| generate | 43.0 |
| geo | 1.4 |
| probe | 53.2 |
| real_test | 108.5 |
| tcp | 32.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 140 | 119 | 21 | 85.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 32 | 25 | 7 | 78.1% |
| vless | 244 | 170 | 74 | 69.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 25 |
| 204:TimeoutError | 18 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 10 |
| geo:ClientOSError | 9 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4524 |
| ConnectionRefusedError | 732 |
| gaierror | 248 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 113 | 1.0 | 129 |
| Au1rxx-base64 | 0.889 | prefer | 275 | 0.833 | 1460 |
| DeltaKronecker-all | 0.822 | prefer | 29 | 0.759 | 5759 |
| mheidari-all | 0.734 | prefer | 24 | 0.667 | 16526 |
| Surfboard-tg-mixed | 0.663 | observe | 101 | 0.584 | 5443 |
| Surfboard-tg-vless | 0.335 | observe | 1 | 1.0 | 4288 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5342 |
| Epodonios-all | 0.255 | observe | 0 | None | 6193 |

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
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.584 | 59 | 42 | 101 |
| mheidari-all | 0.667 | 16 | 8 | 24 |
| DeltaKronecker-all | 0.759 | 22 | 7 | 29 |
| Au1rxx-base64 | 0.833 | 229 | 46 | 275 |
| Surfboard-tg-vless | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16526 | yes | 4.12 | 0 |
| SoliSpirit-all | 6515 | yes | 3.51 | 0 |
| Epodonios-all | 6193 | yes | 1.71 | 0 |
| DeltaKronecker-all | 5759 | yes | 5.24 | 0 |
| Surfboard-tg-mixed | 5443 | yes | 2.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 5342 | yes | 3.09 | 0 |
| mahdibland-V2RayAggregator | 5029 | yes | 1.54 | 0 |
| barry-far-vless | 4667 | yes | 3.25 | 0 |
| Surfboard-tg-vless | 4288 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 35 |
| 204 | 29 |
| speed | 21 |
| cn-block | 19 |
