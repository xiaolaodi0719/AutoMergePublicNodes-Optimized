# AutoNodes 每日报告

生成时间：2026-09-23 04:30:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96642 |
| 去重后节点数 | 26618 |
| TCP 可达数 | 3000 |
| 真测通过数 | 604 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26618 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 74.8 |
| geo | 1.6 |
| probe | 399.5 |
| real_test | 697.5 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 32 | 23 | 9 | 71.9% |
| hysteria2 | 26 | 26 | 0 | 100.0% |
| shadowsocks | 143 | 139 | 4 | 97.2% |
| socks | 15 | 9 | 6 | 60.0% |
| trojan | 25 | 14 | 11 | 56.0% |
| vless | 1090 | 392 | 698 | 36.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 283 |
| speed:ClientOSError | 118 |
| speed:TimeoutError | 112 |
| geo:ClientOSError | 88 |
| cn-block:ClientOSError | 41 |
| 204:TimeoutError | 36 |
| 204:ProxyError | 22 |
| cn-block:TimeoutError | 18 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5604 |
| ConnectionRefusedError | 932 |
| gaierror | 320 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.882 | prefer | 329 | 0.821 | 1585 |
| Surfboard-tg-mixed | 0.8 | prefer | 23 | 0.739 | 7168 |
| ermaozi | 0.701 | prefer | 30 | 0.7 | 346 |
| DeltaKronecker-all | 0.514 | observe | 141 | 0.433 | 6324 |
| mheidari-all | 0.371 | observe | 802 | 0.291 | 22274 |
| ermaozi-get_subscribe | 0.283 | observe | 3 | 0.667 | 372 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4915 |
| Epodonios-all | 0.255 | observe | 0 | None | 7633 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8890 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.291 | 233 | 569 | 802 |
| DeltaKronecker-all | 0.433 | 61 | 80 | 141 |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.7 | 21 | 9 | 30 |
| Surfboard-tg-mixed | 0.739 | 17 | 6 | 23 |
| Au1rxx-base64 | 0.821 | 270 | 59 | 329 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22274 | yes | 6.58 | 0 |
| SoliSpirit-all | 8890 | yes | 4.8 | 0 |
| Epodonios-all | 7633 | yes | 5.2 | 0 |
| Surfboard-tg-mixed | 7168 | yes | 3.93 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.85 | 0 |
| DeltaKronecker-all | 6324 | yes | 5.76 | 0 |
| barry-far-vless | 6054 | yes | 3.14 | 0 |
| Surfboard-tg-vless | 5836 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4915 | yes | 2.95 | 0 |
| mahdibland-V2RayAggregator | 4252 | yes | 0.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 373 |
| speed | 230 |
| cn-block | 63 |
| 204 | 62 |
