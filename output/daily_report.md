# AutoNodes 每日报告

生成时间：2026-08-13 02:27:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79753 |
| 去重后节点数 | 22382 |
| TCP 可达数 | 3000 |
| 真测通过数 | 673 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22382 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.3 |
| generate | 37.6 |
| geo | 1.4 |
| probe | 55.6 |
| real_test | 157.4 |
| tcp | 32.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 172 | 162 | 10 | 94.2% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 149 | 129 | 20 | 86.6% |
| vless | 453 | 232 | 221 | 51.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 98 |
| speed:TimeoutError | 56 |
| geo:ClientOSError | 28 |
| speed:ClientOSError | 24 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 11 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4191 |
| ConnectionRefusedError | 783 |
| gaierror | 348 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.947 | prefer | 406 | 0.889 | 1489 |
| Surfboard-tg-mixed | 0.717 | prefer | 155 | 0.639 | 5894 |
| mheidari-all | 0.501 | observe | 162 | 0.42 | 16809 |
| DeltaKronecker-all | 0.33 | observe | 70 | 0.243 | 4975 |
| Epodonios-all | 0.255 | observe | 0 | None | 6571 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7660 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4734 |
| barry-far-vless | 0.255 | observe | 0 | None | 5066 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 2 | 2 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| DeltaKronecker-all | 0.243 | 17 | 53 | 70 |
| mheidari-all | 0.42 | 68 | 94 | 162 |
| Surfboard-tg-mixed | 0.639 | 99 | 56 | 155 |
| Au1rxx-base64 | 0.889 | 361 | 45 | 406 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16809 | yes | 4.37 | 0 |
| SoliSpirit-all | 7660 | yes | 3.05 | 0 |
| Epodonios-all | 6571 | yes | 1.8 | 0 |
| Surfboard-tg-mixed | 5894 | yes | 3.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 5328 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 2.75 | 0 |
| barry-far-vless | 5066 | yes | 1.3 | 0 |
| DeltaKronecker-all | 4975 | yes | 4.83 | 0 |
| Surfboard-tg-vless | 4734 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 126 |
| speed | 80 |
| cn-block | 26 |
| 204 | 22 |
