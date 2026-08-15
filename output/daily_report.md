# AutoNodes 每日报告

生成时间：2026-08-15 12:52:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77456 |
| 去重后节点数 | 22401 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1030 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22401 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.1 |
| generate | 34.8 |
| geo | 0.6 |
| probe | 68.4 |
| real_test | 187.5 |
| tcp | 33.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 154 | 133 | 21 | 86.4% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 636 | 620 | 16 | 97.5% |
| vless | 162 | 125 | 37 | 77.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 17 |
| 204:TimeoutError | 13 |
| geo:ClientOSError | 12 |
| geo:TimeoutError | 12 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4005 |
| ConnectionRefusedError | 830 |
| gaierror | 429 |
| OSError | 25 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 738 | 0.954 | 1659 |
| mheidari-all | 1.0 | prefer | 93 | 0.968 | 15977 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.89 | prefer | 56 | 0.821 | 5656 |
| DeltaKronecker-all | 0.778 | prefer | 84 | 0.702 | 5773 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2081 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 160 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5113 |
| Epodonios-all | 0.255 | observe | 0 | None | 6303 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.702 | 59 | 25 | 84 |
| Surfboard-tg-mixed | 0.821 | 46 | 10 | 56 |
| Au1rxx-base64 | 0.954 | 704 | 34 | 738 |
| mheidari-all | 0.968 | 90 | 3 | 93 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15977 | yes | 4.26 | 0 |
| SoliSpirit-all | 7258 | yes | 2.19 | 0 |
| Epodonios-all | 6303 | yes | 4.44 | 0 |
| DeltaKronecker-all | 5773 | yes | 4.77 | 0 |
| Surfboard-tg-mixed | 5656 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 5113 | yes | 1.21 | 0 |
| barry-far-vless | 4711 | yes | 0.77 | 0 |
| Surfboard-tg-vless | 4372 | yes | 2.95 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 3935 | yes | 2.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 24 |
| geo | 24 |
| cn-block | 23 |
| speed | 4 |
