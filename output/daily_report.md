# AutoNodes 每日报告

生成时间：2026-08-11 19:12:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 81101 |
| 去重后节点数 | 23130 |
| TCP 可达数 | 3000 |
| 真测通过数 | 570 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23130 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| generate | 45.4 |
| geo | 1.4 |
| probe | 57.3 |
| real_test | 123.2 |
| tcp | 35.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 150 | 133 | 17 | 88.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 108 | 104 | 4 | 96.3% |
| vless | 248 | 180 | 68 | 72.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 22 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 13 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 8 |
| geo:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4640 |
| ConnectionRefusedError | 793 |
| gaierror | 314 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.947 | prefer | 370 | 0.889 | 1503 |
| Surfboard-tg-mixed | 0.794 | prefer | 103 | 0.718 | 6169 |
| mheidari-all | 0.74 | prefer | 51 | 0.667 | 16649 |
| DeltaKronecker-all | 0.352 | observe | 6 | 0.5 | 5522 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 5419 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 6745 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7634 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 3 | 3 | 6 |
| mheidari-all | 0.667 | 34 | 17 | 51 |
| Surfboard-tg-mixed | 0.718 | 74 | 29 | 103 |
| Au1rxx-base64 | 0.889 | 329 | 41 | 370 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16649 | yes | 4.36 | 0 |
| SoliSpirit-all | 7634 | yes | 4.4 | 0 |
| Epodonios-all | 6745 | yes | 2.74 | 0 |
| Surfboard-tg-mixed | 6169 | yes | 3.2 | 0 |
| DeltaKronecker-all | 5522 | yes | 3.92 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 1.91 | 0 |
| barry-far-vless | 5313 | yes | 1.64 | 0 |
| mahdibland-V2RayAggregator | 5196 | yes | 2.87 | 0 |
| Surfboard-tg-vless | 5045 | yes | 3.46 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 41 |
| speed | 21 |
| cn-block | 15 |
| geo | 15 |
