# AutoNodes 每日报告

生成时间：2026-08-08 13:01:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83600 |
| 去重后节点数 | 23665 |
| TCP 可达数 | 3000 |
| 真测通过数 | 404 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23665 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 48.9 |
| geo | 1.3 |
| probe | 49.6 |
| real_test | 95.0 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 159 | 146 | 13 | 91.8% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 143 | 131 | 12 | 91.6% |
| vless | 126 | 82 | 44 | 65.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 23 |
| cn-block:TimeoutError | 13 |
| speed:TimeoutError | 8 |
| geo:ClientOSError | 6 |
| 204:ProxyError | 6 |
| speed:ClientOSError | 5 |
| geo:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5011 |
| ConnectionRefusedError | 794 |
| gaierror | 282 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 341 | 0.947 | 1488 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| Surfboard-tg-mixed | 0.68 | observe | 78 | 0.603 | 6570 |
| mheidari-all | 0.461 | observe | 11 | 0.545 | 17827 |
| DeltaKronecker-all | 0.376 | observe | 25 | 0.28 | 5347 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5450 |
| Epodonios-all | 0.255 | observe | 0 | None | 7203 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7636 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.28 | 7 | 18 | 25 |
| mheidari-all | 0.545 | 6 | 5 | 11 |
| Surfboard-tg-mixed | 0.603 | 47 | 31 | 78 |
| Au1rxx-base64 | 0.947 | 323 | 18 | 341 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17827 | yes | 4.99 | 0 |
| SoliSpirit-all | 7636 | yes | 3.21 | 0 |
| Epodonios-all | 7203 | yes | 2.72 | 0 |
| Surfboard-tg-mixed | 6570 | yes | 3.85 | 0 |
| barry-far-vless | 5686 | yes | 2.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 5450 | yes | 2.04 | 0 |
| Surfboard-tg-vless | 5374 | yes | 3.63 | 0 |
| DeltaKronecker-all | 5347 | yes | 3.87 | 0 |
| mahdibland-V2RayAggregator | 5162 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.25 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| cn-block | 17 |
| speed | 13 |
| geo | 11 |
