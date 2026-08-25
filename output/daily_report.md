# AutoNodes 每日报告

生成时间：2026-08-25 07:01:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 78337 |
| 去重后节点数 | 22287 |
| TCP 可达数 | 3000 |
| 真测通过数 | 678 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22287 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| generate | 26.3 |
| geo | 1.4 |
| probe | 63.8 |
| real_test | 149.7 |
| tcp | 35.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 217 | 199 | 18 | 91.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 86 | 72 | 14 | 83.7% |
| vless | 497 | 360 | 137 | 72.4% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 52 |
| 204:TimeoutError | 26 |
| speed:TimeoutError | 20 |
| speed:ClientOSError | 19 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 11 |
| cn-block:ClientOSError | 10 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4733 |
| ConnectionRefusedError | 800 |
| gaierror | 326 |
| OSError | 15 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.943 | prefer | 503 | 0.877 | 1700 |
| mheidari-all | 0.839 | prefer | 52 | 0.769 | 14480 |
| Surfboard-tg-mixed | 0.788 | prefer | 152 | 0.711 | 6465 |
| DeltaKronecker-all | 0.635 | observe | 117 | 0.556 | 6340 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6957 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5306 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.556 | 65 | 52 | 117 |
| Surfboard-tg-mixed | 0.711 | 108 | 44 | 152 |
| mheidari-all | 0.769 | 40 | 12 | 52 |
| Au1rxx-base64 | 0.877 | 441 | 62 | 503 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14480 | yes | 4.24 | 0 |
| SoliSpirit-all | 6957 | yes | 4.92 | 0 |
| Epodonios-all | 6925 | yes | 4.84 | 0 |
| Surfboard-tg-mixed | 6465 | yes | 3.83 | 0 |
| DeltaKronecker-all | 6340 | yes | 5.06 | 0 |
| barry-far-vless | 5525 | yes | 2.2 | 0 |
| Surfboard-tg-vless | 5306 | yes | 4.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 0.71 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 2.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 68 |
| speed | 41 |
| 204 | 39 |
| cn-block | 24 |
