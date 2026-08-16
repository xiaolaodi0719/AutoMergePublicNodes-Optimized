# AutoNodes 每日报告

生成时间：2026-08-16 12:54:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 79021 |
| 去重后节点数 | 21934 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1106 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21934 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 39.3 |
| geo | 0.7 |
| probe | 64.6 |
| real_test | 209.7 |
| tcp | 33.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 18 | 18 | 0 | 100.0% |
| shadowsocks | 145 | 136 | 9 | 93.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 602 | 594 | 8 | 98.7% |
| vless | 312 | 229 | 83 | 73.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| geo:TimeoutError | 16 |
| speed:TimeoutError | 15 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 13 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4349 |
| ConnectionRefusedError | 820 |
| gaierror | 279 |
| OSError | 16 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 814 | 0.967 | 1994 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.982 | prefer | 100 | 0.91 | 16375 |
| Surfboard-tg-mixed | 0.762 | prefer | 146 | 0.685 | 5800 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4990 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 6483 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3989 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7383 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4502 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.171 | downweight | 20 | 0.05 | 0 | 5092 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.171 | 20 | 0.05 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.05 | 1 | 19 | 20 |
| Surfboard-tg-mixed | 0.685 | 100 | 46 | 146 |
| mheidari-all | 0.91 | 91 | 9 | 100 |
| Au1rxx-base64 | 0.967 | 787 | 27 | 814 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16375 | yes | 3.1 | 0 |
| SoliSpirit-all | 7383 | yes | 3.33 | 0 |
| Epodonios-all | 6483 | yes | 3.27 | 0 |
| Surfboard-tg-mixed | 5800 | yes | 2.46 | 0 |
| DeltaKronecker-all | 5092 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4990 | yes | 1.49 | 0 |
| barry-far-vless | 4839 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 4502 | yes | 2.74 | 0 |
| MatinGhanbari-all-sub | 3989 | yes | 1.69 | 0 |
| mahdibland-V2RayAggregator | 3950 | yes | 0.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 29 |
| 204 | 26 |
| speed | 25 |
| cn-block | 22 |
