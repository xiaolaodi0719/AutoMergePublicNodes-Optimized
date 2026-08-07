# AutoNodes 每日报告

生成时间：2026-08-07 13:18:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 82701 |
| 去重后节点数 | 23372 |
| TCP 可达数 | 3000 |
| 真测通过数 | 406 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23372 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 32.3 |
| geo | 1.3 |
| probe | 55.9 |
| real_test | 103.5 |
| tcp | 35.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 154 | 140 | 14 | 90.9% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 150 | 145 | 5 | 96.7% |
| vless | 142 | 81 | 61 | 57.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 18 |
| geo:TimeoutError | 16 |
| speed:ClientOSError | 11 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 8 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| cn-block:TimeoutError | 4 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4950 |
| ConnectionRefusedError | 794 |
| gaierror | 259 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 339 | 0.968 | 1509 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| mheidari-all | 0.71 | prefer | 71 | 0.634 | 17690 |
| Surfboard-tg-mixed | 0.389 | observe | 13 | 0.385 | 6364 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| DeltaKronecker-all | 0.258 | observe | 43 | 0.163 | 5326 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5282 |
| Epodonios-all | 0.255 | observe | 0 | None | 6987 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7685 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.163 | 7 | 36 | 43 |
| Surfboard-tg-mixed | 0.385 | 5 | 8 | 13 |
| mheidari-all | 0.634 | 45 | 26 | 71 |
| Au1rxx-base64 | 0.968 | 328 | 11 | 339 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17690 | yes | 4.2 | 0 |
| SoliSpirit-all | 7685 | yes | 2.4 | 0 |
| Epodonios-all | 6987 | yes | 4.4 | 0 |
| Surfboard-tg-mixed | 6364 | yes | 3.59 | 0 |
| barry-far-vless | 5471 | yes | 1.07 | 0 |
| DeltaKronecker-all | 5326 | yes | 4.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 0.85 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 2.56 | 0 |
| Surfboard-tg-vless | 5147 | yes | 2.91 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 34 |
| 204 | 23 |
| speed | 17 |
| cn-block | 9 |
